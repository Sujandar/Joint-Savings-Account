# Solidity Smart Contract - Joint Savings Account

## Overview
I created a Solidity smart contract that accepts two user addresses, to automate the creation of joint savings accounts. These two addresses will be able to control a joint savings account. 

The smart contract uses ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

## Steps Completed

The steps I completed are as follows:

1. Created a joint savings account contract in Solidity
2. Compiled and deployed the contract in the Remix VM (London) 
3. Interacted with the deployed smart contract

### 1. Create a Joint Savings Account Contract in Solidity

I created the smart contract for a joint savings account in Solidity. 

### 2. Compile and Deploy Contract in the JavaScript VM

I compiled the smart contract as shown below:

### 3. Interact with Deployed Smart Contract

Once the contract was deployed, I tested its functionality.

#### Use 'setAccounts' Function

I used the `setAccounts` function to define the authorized Ethereum addresses that will be able to withdraw funds from the contract:

#### Test Deposit Functionality

I tested the deposit functionality of the smart contract by sending the following amounts of ether. After each transaction, I used the `contractBalance` function to verify that the funds were added to the contract.

##### Transaction 1: Sent 1 ether as wei.

##### Transaction 2: Sent 10 ether as wei.

##### Transaction 3: Sent 5 ether.

#### Test Withdrawal Functionality

Once I'd successfully deposited funds into the contract, I tested the contract’s withdrawal functionality. 

##### Withdrew 5 ether into `accountOne`

##### Withdrew 10 ether into `accountTwo`

##### Used the `lastToWithdraw` and `lastWithdrawAmount` functions to verify that the address and amount were correct
