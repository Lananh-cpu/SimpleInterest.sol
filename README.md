# SimpleInterest.sol
SimpleInterest.sol
pragma solidity ^0.8.20;
contract SimpleInterest {
    function calc(uint p, uint r, uint t) public pure returns(uint) {
        return (p * r * t) / 100;
    }
}
