# Project-Create-and-Mint-Token
This Solidity program is a simple Token Creation that demonstrates the basic functions of declaring variables, using mapping as a reference type, creating functions, as well as making use of conditional statements. The purpose of this program is to demonstrate what I've learned so far in taking the Beginners course on ETH from metacrafters.
# Description
This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract contains three declared public variables that correspond to Token details. The contract has two functions called mint and burn. The mint function adds an indicated value to the corresponding total supplies of the specified token and adds that value to the balance associated with the Ethereum addresses. The burn function operates the opposite way, where it deducts an indicated value to the corresponding total supplies of the specified token as well as deducts that value to the associated Ethereum addresses balance. This program acts as a basic and clear-cut project showcasing the coding functionalities in Solidity. It can serve as a foundation for developing more advanced projects.
## Getting Started

### Executing program

To run this program, you can utilize Remix, an online Solidity IDE. Begin by visiting the Remix website at https://remix.ethereum.org/.

After accessing the Remix website, create a new file by clicking the "+" icon in the left-hand sidebar. Save the file with a .sol extension (for example, FinalProject.sol). Then, copy and paste the following code into the file:

```javascript
// SPDX-License-Identifier: MIT
pragma solidity 0.8.18;

contract MyToken {

    // public variables here

    // mapping variable here

    // mint function

    // burn function

}

```

To compile the code, navigate to the "Solidity Compiler" tab in the left-hand side of the sidebar. Ensure the "Compiler" version is set to "0.8.18", and then click the "Compile FinalProject.sol" button.

After compiling, you can deploy the contract by going to the "Deploy & Run Transactions" tab in the left-hand side of the sidebar. Choose the "My Token - FinalProject.sol" contract from the dropdown menu and click the "Deploy" button.

Once deployed, you can interact with the contract by calling the balance of the indicated address, as well as making use of the mint and burn functions that were explained before. Select the "mint" and "burn" functions in the left-hand sidebar, and then press the "transact" button to execute the function and add or deduct values from the total supply as well as the balance of the associated address indicated.

## Authors

Metacrafter Student Christian
[@_cbso](https://x.com/cbso_)

## License

This project is licensed under the Christian Benjamin License - see the LICENSE.md file for details
