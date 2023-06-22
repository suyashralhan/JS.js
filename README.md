# JS.js
This code demonstrates the creation and management of NFTs (Non-Fungible Tokens)

1. The code begins by creating a variable called `NFTs`, which is an empty array. This array will be used to hold the NFT objects.

2. The `mintNFT` function is defined. It takes in four parameters: `_name`, `_eyeColor`, `_shirtType`, and `_bling`. These parameters represent the metadata values for the NFT. Inside the function, a new object named `NFT` is created, with properties corresponding to the metadata values passed as arguments. The `NFT` object is then pushed into the `NFTs` array using the `push` method. Finally, a message is logged to the console indicating the successful minting of the NFT.

3. The `listNFTs` function is defined. It iterates over the `NFTs` array using a `for` loop. Inside the loop, it logs the metadata of each NFT object to the console, including the ID, name, eye color, shirt type, and bling.

4. The `getTotalSupply` function is defined. It simply logs the length of the `NFTs` array to the console, which represents the total number of NFTs minted.

5. After the function definitions, four calls to the `mintNFT` function are made, each with different metadata values. These calls create four NFTs and store them in the `NFTs` array.

6. The `listNFTs` function is then called, which prints the metadata of all the NFTs to the console.

7. Finally, the `getTotalSupply` function is called, which logs the total number of NFTs to the console.

