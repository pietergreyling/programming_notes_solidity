# Solidity Programming Notes

These notes help to aid my short term memory.

## Contracts, Addresses!

### Contracts
- a Contract is a class

### Addresses
- an Address is
-- In Ethereum and Solidity, an address if of 20 byte value size (160 bits or 40 hex characters). It corresponds to the last 20 bytes of the Keccak-256 hash of the public key. An address is always pre-fixed with 0x as it is represented in hexadecimal format (base 16 notation) (defined explicitly).
- the purpose of an Address
-- An address value type is specifically designed to hold up to 20B, or 160 bits, which is the size of an Ethereum address. Solidity actually offers two address value types: address and address payable . The difference between the two is that address payable can send and transfer Ether.


