# Solidity Programming Notes

These notes help to aid my short term memory.

## Contracts, Addresses!

### Contracts
- a Contract is a class

### Addresses
- an Address is
  - In Ethereum and Solidity, an address if of 20 byte value size (160 bits or 40 hex characters). It corresponds to the last 20 bytes of the Keccak-256 hash of the public key. An address is always pre-fixed with 0x as it is represented in hexadecimal format (base 16 notation) (defined explicitly).
- the purpose of an Address
  - An address value type is specifically designed to hold up to 20B, or 160 bits, which is the size of an Ethereum address. Solidity actually offers two address value types: address and address payable . The difference between the two is that address payable can send and transfer Ether.

## Resources

### Solidity Programming Language
- https://soliditylang.org/
- https://docs.soliditylang.org/en/latest/

### Ethereum Virtual Machine
- https://ethereum.org/en/developers/docs/evm/
  - The EVM’s physical instantiation can’t be described in the same way that one might point to a cloud or an ocean wave, but it does exist as one single entity maintained by thousands of connected computers running an Ethereum client.
  - The Ethereum protocol itself exists solely for the purpose of keeping the continuous, uninterrupted, and immutable operation of this special state machine. It's the environment in which all Ethereum accounts and smart contracts live. At any given block in the chain, Ethereum has one and only one 'canonical' state, and the EVM is what defines the rules for computing a new valid state from block to block.

### Remix IDE
- https://remix-project.org/
- https://remix.ethereum.org/
