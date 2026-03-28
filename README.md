# SimpleFlag
Deploy a contract on Base SimpleFlag
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimpleFlag {
    bool public active;

    function set(bool _a) public {
        active = _a;
    }
}
