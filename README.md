Fee Collector Contract
This Solidity smart contract implements a fee collector functionality on the Ethereum blockchain. The contract allows the owner to collect fees in both Ether (ETH) and ERC20 tokens, providing a straightforward mechanism for managing and withdrawing funds.

Features
Fee Collection: Users can send Ether (ETH) to the contract, which increases the contract's balance.
Withdrawal: The owner of the contract can withdraw collected Ether (ETH) from the contract to a specified address.
ERC20 Token Support: The contract supports the transfer of ERC20 tokens. The owner can transfer ERC20 tokens from the contract to a specified address.
Usage
Fee Collection: Users can send Ether (ETH) to the contract's payable function (receive()), which increases the contract's balance. Events are emitted for transparency.
Withdrawal: The contract owner can call the withdraw() function to withdraw collected Ether (ETH) from the contract to a specified address. Only the contract owner can initiate withdrawals.
ERC20 Token Transfer: The contract owner can transfer ERC20 tokens from the contract to a specified address using the transferERC20() function. Only the contract owner can initiate token transfers.
Deployment
This contract can be deployed on the Ethereum blockchain using Solidity-compatible development environments such as Remix, Truffle, or Hardhat. Make sure to set appropriate permissions and consider security best practices before deploying to the mainnet.

License
This code is provided under the MIT License. Feel free to use, modify, and distribute it according to your needs.

