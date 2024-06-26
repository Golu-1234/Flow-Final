# NFT-Project

This project is a Non-Fungible Token (NFT) implementation on the Flow blockchain using cadence programming language and FLow playground. This project includes the Flow Non-Fungible Token to create, manage, and interact with NFTs, allowing users to mint, manage collections, and retrieve metadata associated with NFTs.

## Requirements

- [Flow Playground](https://play.flow.com/)
- Cadence Language

## Contracts

### `CryptoPoops` Contract

The `CryptoPoops` contract is the core contract that defines the NFT functionality. It inherits from the Flow Non-Fungible Token.

**Key Features:**

- Creating and managing NFTs.
- Depositing and withdrawing NFTs from collections.
- Borrowing NFT metadata and IDs.
- Minting new NFTs using a minter resource.

### Transaction Scripts

#### `collectionTransaction`

This transaction allows users to create a new collection and link it to their public interface. It checks if the user already has a collection before creating a new one.

#### `mintTransaction`

This transaction enables the minting of new CryptoPoops NFTs. It interacts with a minter resource to create an NFT and deposits it into the recipient's collection.

### Scripts

#### `getIdTransaction`

This script retrieves the NFT IDs associated with an account's public collection. It allows users to view the IDs of NFTs they own.

#### `metadataTransaction`

This script retrieves NFT metadata based on the provided NFT ID from an account's public collection. Users can view the metadata associated with their NFTs.

## How to Use

1. Create your Contract, Transaction and Script files on the flow playground
2. Deploy the `CryptoPoops` contract to the Flow blockchain.
3. Use the provided transaction scripts to create collections, mint NFTs, and interact with NFTs.
4. Utilize the script files to retrieve NFT IDs and metadata associated with your CryptoPoops NFTs.

