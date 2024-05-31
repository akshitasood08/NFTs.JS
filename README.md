# NFT Collection Manager
This project demonstrates a simple implementation of an NFT (Non-Fungible Token) collection manager using JavaScript. The code includes functions to mint new NFTs, list all minted NFTs, and get the total supply of NFTs created.

## Features
**Minting NFTs:** Create new NFTs by providing metadata such as name, eye color, shirt type, and bling. The metadata is stored in an object and added to the NFT collection.
**Listing NFTs:** Display all the NFTs in the collection along with their metadata.
**Total Supply:** Retrieve and display the total number of NFTs minted.
## Code Overview
### Variables
NFTs: An array to hold all minted NFT objects.
### Functions
1. mintNFT(_name, _eyeColor, _shirtType, _bling): Mints a new NFT with the provided metadata and adds it to the NFTs array. Logs the name of the minted NFT.
2. listNFTs(): Iterates through the NFTs array and prints the metadata of each NFT to the console.
3. getTotalSupply(): Prints the total number of minted NFTs.
## Example Usage
````javascript
// Minting new NFTs
mintNFT("Himawari", "Blue", "Denim", "Gold earring");
mintNFT("Shinchan", "Green", "T-shirt", "Gold chain");
mintNFT("Doraemon", "Brown", "Shirt", "Gold ring");
mintNFT("Kazama", "Blue", "Shirt", "Gold chain");

// Listing all NFTs
listNFTs();

// Getting the total supply of NFTs
getTotalSupply();
