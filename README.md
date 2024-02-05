# MyToken Smart Contract

The MyToken smart contract is a token contract created using Solidity. It allows you to create your own token on a local Hardhat network. The contract owner has the ability to mint tokens to a provided address, while any user can burn and transfer tokens.

## Getting Started

### Prerequisites

- Node.js (v12 or higher)
- Hardhat (v2 or higher)
- Remix IDE (web-based)

### Installation

1. Clone this repository or download the project files.

2. Install the project dependencies by running the following command:

   ```bash
   npm install
### Deployment and Interactions
1. Start a local Hardhat network by running the following command:
   npx hardhat node
2. Open Remix IDE in your web browser (https://remix.ethereum.org).

3. In Remix, create a new Solidity file and paste the contents of MyToken.sol into it.

4. Compile the contract using the appropriate compiler version.

5. Deploy the contract on the local Hardhat network using the "Injected Web3" environment in Remix.

6. Interact with the contract using the available functions:

  i. Mint Tokens:

    As the contract owner, call the mint function from Remix, providing the recipient's address and the desired amount of tokens to be minted.
    
  ii. Burn Tokens:

     Call the burn function from Remix, specifying the number of tokens to be burned.
     
  iii. transfer :

     call the transfer function, specifying the address to which you want to trasnfer the tokens to and the number of token to be transfered.

### Contract Details
1. MyToken.sol: Contains the Solidity code for the MyToken contract.
2. name: The name of the token.
3. symbol: The symbol of the token.
4. totalSupply: The total supply of tokens.
5. owner: The address of the contract owner.
balances: A mapping of addresses to their respective token balances.
### License
This project is licensed under the MIT License. See the LICENSE file for details
