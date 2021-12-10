# ⚡️Solidity-basics⚡️
A repository to keep a track of all things that I learn in Solidity

## 💡About Solidity:
It is a statically typed (we have to declare the datatypes of the variables), high-level, object-oriented programming language developed by Etherium primarily to
develop smart contracts

## 🧮 State variables:
1. Variables that we declare in our contract get stored in the blockchain and are called state variables.
2. Since state variables take up memory in the blockchain, they carry a GAS fee and hence they can be expensive. So we have to declare them carefully.
3. State variables cannot be initialized randomly and there are 3 ways through which we can initialize them:
    * Initializing at declaration
    * Initializing within the constructor
    * Initializing within setter functions
4. We cannot randomly create instances of new state variables besides the ones already declared because storage is not dynamically allocated. We have to deploy the contract all over again to create new instances.

## ♺ View keyword:
1. The view keyword tells us that it is not making any sort of changes to the state variables. 
2. Most of the getter functions carry view keyword.

## 🗣 Public variables:
1. For variables that carry public keyword, they can be accessed beyond the contract.
2. An automatic getter function is created for such variables.

