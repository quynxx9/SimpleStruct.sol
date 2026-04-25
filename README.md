# SimpleStruct.sol
SimpleStruct.sol
pragma solidity ^0.8.20;

contract SimpleStruct {
    struct Person {
        string name;
        uint age;
    }

    Person public person;

    function setPerson(string memory _name, uint _age) public {
        person = Person(_name, _age);
    }
}
