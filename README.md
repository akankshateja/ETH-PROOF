# ETH-PROOF
# Creating a token
The program introduces "MyToken," a straightforward custom token built with Solidity on the Ethereum blockchain. 
Tokens can be created and destroyed while individual balances and the total supply are tracked. 
With the capacity to mint new tokens and consume existing ones, the program guarantees that symbolic holders have sufficient equilibrium prior to playing out any consuming activities.
By sticking to the MIT permit, this agreement can be uninhibitedly utilized and circulated. 
It offers a dependable solution for token issuance and tracking and provides a user-friendly and accessible framework for creating and managing custom tokens on the Ethereum platform.
## Description
"MyToken" for the Ethereum blockchain, written in Solidity. The agreement incorporates public factors to store fundamental subtleties of the token, like its name, truncation, and absolute stockpile. 
It connects Ethereum addresses to their respective token balances through a mapping known as "tokenHolders," making it possible to effectively track and manage ownership. 
There are two main functions provided by the program: burn" and "mint." The "mint" function makes it possible to create new tokens, increase the total supply, and update the recipient address's balance.
The "consume" capability works with the obliteration of tokens, lessening the all out supply and deducting the predefined sum from the symbolic holder's equilibrium. 
Importantly, there is a check built into the "burn" function to make sure that the token holder's balance is enough to cover the burn amount that was requested.
The contract is a complete solution for token creation, destruction, and balance management in a safe and decentralized blockchain environment thanks to these features.

## Getting Started

### Installing
Copy the code and paste it in remix ide.

### Executing program
First deploy the program. After that we can use the default address provided. Paste the address in the mint add the value Check the Balance. Also we can burn the token via burn. Add the address. Burn the token. Check the balance.

## Authors
Akanksha Teja


