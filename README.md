# 20-challenge
 Ethereum-compatible blockchain that connects financial institutions. Building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts. 


## Technology
This project uses the following libraries:
* [Remix IDE](https://remix.ethereum.org/)
* Solidity with JavaScipt VM

## Installation Guide
Using the Conda package manager: [My GitHub Project](https://github.com/ALovettII/20-challenge.git)


## Usage
#### Background:
1. To automate the creation of joint savings accounts:
    * you’ll create a Solidity smart contract that accepts two user addresses.
        * addresses will be able to control a joint savings account. 

2. Smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account:
    * features will consist of the ability to deposit and withdraw funds from the account.
    
#### What You're Creating:
1. The completed Solidity JointSavings smart contract.
2. A folder named Execution_Results that contains at least eight images.
    * These images should confirm that the deposit and withdrawal transactions, worked as expected:
        * designed to test the JointSavings functionality in the JavaScript VM

#### Sections:
The project is comprised of three sections:
1. Create a Joint Savings Account Contract in Solidity
2. Compile and Deploy Your Contract in the JavaScript VM
3. Interact with Your Deployed Smart Contract

#### Execution Results:
* The screenshot verifies the setAccounts function:
![setAccounts](https://github.com/ALovettII/20-challenge/blob/main/Execution_Results/setAccounts.png)
* The following screenshots verify execution of the deposit function:
    1. [Deposit: Transaction 1](https://github.com/ALovettII/20-challenge/blob/main/Execution_Results/01_deposit.png)
    2. [Deposit: Transaction 2](https://github.com/ALovettII/20-challenge/blob/main/Execution_Results/02_deposit.png)
    3. [Deposit: Transaction 3](https://github.com/ALovettII/20-challenge/blob/main/Execution_Results/03_deposit.png)

* The following screenshots verify execution of the withdrawal & last functions:
    1. [Withdrawal & Balance: Transaction 1](https://github.com/ALovettII/20-challenge/blob/main/Execution_Results/01_withdraw-bal.png)
        a. [Last: Transaction 1](https://github.com/ALovettII/20-challenge/blob/main/Execution_Results/01_withdraw-last.png)
    2. [Withdrawal & Balance: Transaction 2](https://github.com/ALovettII/20-challenge/blob/main/Execution_Results/02_withdraw-bal.png)
        a. [Last: Transaction 2](https://github.com/ALovettII/20-challenge/blob/main/Execution_Results/02_withdraw-last.png)


## Contributors
Created by Arthur Lovett