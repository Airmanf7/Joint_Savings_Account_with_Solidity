# Joint_Savings_Account_with_Solidity_and_Remix

## Project Goals

- Create a smart contract that functions as a joint savings account.
- Write functions that allow deposits and withdrawals.
- Write a function that blocks withdrawals that were not initiated by the account owners.
- Deploy on a testnet and interact with its functions.


---

## Project Summary

The purpose of this project is to create a smart contract that functions as a joint savings account. The programming language, Solidity, will be used along with REMIX IDE to deploy the contract to a local testnet. The primary functions will be the following:

- `deposit` Allows test Ether to be deposited denominated in Wei.
- `withdraw` Allows test Ether to be withdrawn to one of the two account owners denominated in Wei.
- `last to withdraw` This is a `call` function which returns the wallet address in the most recent withdraw transaction.
- `last withdraw amount` This is a `call` function which returns the amount in Wei in the most recent withdraw transaction.

---

## Technologies

This project uses **[python version 3.8.12](https://www.python.org/downloads/)** with the following packages and modules:

* [pandas](https://pandas.pydata.org/docs/) - *version 1.3.4* - This module was used to be able to create and manipulate dataframes.

* [hashlib](https://docs.python.org/3/library/hashlib.html)- This module uses a common interface to many different secure hash and message digest algorithms. For this project, we use SHA256 to return a hexdigest.

* [web3.py](https://web3py.readthedocs.io/en/stable/overview.html) - This is a Python library that enables connection to a decentralized online network based on a blockchain.

* [Solidity](https://docs.soliditylang.org/en/v0.8.9/) - This is a programming language commonly used to create smart contracts which are ultimately deployed to the Ethereum blockchain.

* [Remix IDE](https://remix.ethereum.org/) - This is used to be able to write, compile and deploy smart contracts written in the Solidity code.

---
## Installation/ Usage Guide

### 1. Open [REMIX IDE](https://remix.ethereum.org/), then click on the left icon logo, and then click Open file and navigate to where the git clone files are saved locally on your computer.

![Remix IDE Open](.

### 3. Compile the `joint_savings.sol` file and make sure that the compiler is version 0.5.0.

![Remix IDE Compile](.

### 4. Set the Environment to "JavaScript VM", once this is done, click Deploy.

![Remix IDE Javascript](.


---
## Examples and Images

### **These images show what happens after contract deployment and each interaction function.** 

#### **Interaction 1: Set the addresses for accountOne and accountTwo:**

![Interaction 1](.

#### **Interaction 2: Desposit 11 ether as Wei:**

![Interaction 2](.

#### **Interaction 3: Withdraw 5 Ether into accountOne.** 

![Interaction 3](.

#### **Interaction 4: Withdraw 5 Ether into accountTwo.**

![Interaction 4](./

#### **Interaction 5: View the current balance, account that was last to withdraw and the amount that was last withdrawn.**

![Interaction 5](./

#### **Interaction 6: Attempt to withdraw 1 Ether into an account other than the two owners.**

![Interaction 6](./

#### **Interaction 5: 

![Interaction 5](./

---

## Contributors

Contributor: Andrew McCoy

Email: airmanf7@gmail.com

[![Linkedin]

---

## License

### **MIT License**

Copyright (c) [20212 [Andrew McCoy]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
