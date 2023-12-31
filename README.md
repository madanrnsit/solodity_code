
# MyToken Smart Contract


This is a simple Solidity smart contract that creates a token called "MADAN" with the abbreviation "MAD". It has a total supply that starts at 0, and uses a mapping of addresses to balances to keep track of how many tokens each address holds.

The contract includes two functions: minting and burning.


## Description

This program is a simple contract written in remix. The contract allows you to add and sub values to the account address.
 

## Requirements

1)The contract has public variables to store the details about the coin: tokenName, tokenAbbrvation, and totalSupply.

2)The contract uses a mapping of addresses to balances: mapping(address => uint) public balances.

3)The minting function increases the total supply by the given amount of token and increases the balance of the given address by that amount of token.

4)The burning function deducts the given amount of token from the total supply and from the balance of the given address.

5)The burning function includes conditionals to make sure the balance of the given address is greater than or equal to the amount of token that is supposed to be burned.
## Usage

To use this contract, you can deploy it to a Ethereum network (such as the mainnet, Ropsten, or a local testnet) using a Solidity compiler and an Ethereum client (such as Remix or Truffle). Then you can interact with the contract using a web3 provider (such as MetaMask) or a smart contract wallet (such as Gnosis Safe).
## License

This code is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.See the LICENSE file for more information.


## Acknowledgements

I extend my heartfelt gratitude to Remix Tutorials and the Remix website for their invaluable resources and user-friendly tools. Their tutorials have significantly enhanced my understanding and proficiency in developing Solidity smart contracts on the Ethereum network. Thank you for your remarkable contributions to the blockchain community!
