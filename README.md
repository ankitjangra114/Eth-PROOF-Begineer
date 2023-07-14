# Eth-PROOF-Begineer
Project that has been assigned in the courses provided by Metacrafters.
# Description
This is a simple ERC-20 token contract implemented in Solidity. The contract allows for the creation and destruction of tokens, as well as storing information about the token.
* [ethBeginners.sol](https://github.com/ankitjangra114/Eth-PROOF-Begineer/blob/main/Token.sol)
* [Loom](https://www.loom.com/share/522c5d5e9ecb4615a9fd7cd52e626ce8)
# Requirements
1. The contract has public variables that store the details about the coin:
   - Name: A string representing the name of the token.
   - abbrv: A string representing the abbreviation of the token.
   - Supply: An unsigned integer representing the total supply of the token.
  
2. The contract has a mapping of addresses to balances:
   - balances: A mapping that associates addresses with their corresponding token balances.
     
3. The contract has a mint function that increases the total supply and the balance of the "sender" address by a given value:
   - Parameters:
     - TokenAddress: The address to which the tokens will be minted.
     - TokenValue: The amount of tokens to be minted.
   - Actions:
     - Increase the Supply by TokenValue.
     - Increase the balance of the TotalAddress by TotalValue.
       
4. The contract has a burn function that decreases the total supply and the balance of the "sender" address by a given value:
   - Parameters:
     - TotalAddress: The address from which the tokens will be burned.
     - TotalValue: The amount of tokens to be burned.
   - Actions:
     - Check if the balance of the TotalAddress is greater than or equal to TotalValue.
     - If true, decrease the totalSupply by TotalValue.
     - Decrease the balance of the TotalAddress by TotalValue.

# Usage
1. Deploy the MyToken contract to a supported Ethereum network.
2. Once deployed, you can interact with the contract by calling the following functions:
   - mint: Creates new tokens and assigns them to a specified address.
     - Parameters:
       - TotalAddress: The address to which the tokens will be minted.
       - TotalValue: The amount of tokens to be minted.
   - burn: Destroys existing tokens by reducing the total supply and the balance of a specified address.
     - Parameters:
       - TotalAddress: The address from which the tokens will be burned.
       - TotalValue: The amount of tokens to be burned.

# License
This contract is licensed under the MIT License. SPDX-License-Identifier: MIT.
