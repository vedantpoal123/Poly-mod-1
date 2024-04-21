# Poly-mod-1
# NFT Project Migration to Polygon

Welcome to our exciting journey of migrating our NFT project to Polygon! In this project, we aim to deploy an NFT collection on the Ethereum blockchain, map the collection to Polygon, and transfer assets over via the Polygon Bridge. To add a unique twist, we'll be using an image generation tool like DALLE 2 or Midjourney to create the images for our NFTs.

## Project Overview

1. **Generate NFT Collection Images**: Utilize DALLE 2 or Midjourney to generate a 5-item NFT collection. These images will serve as the unique assets for our NFTs.

2. **Store Images on IPFS**: Store the generated images on IPFS using pinata.cloud for decentralized and reliable storage.

3. **Deploy Smart Contract to Ethereum Testnet**: Deploy an ERC721 or ERC1155 smart contract to the Goerli Ethereum Testnet. Ensure that the contract includes a `promptDescription` function that returns the prompt used to generate the images for transparency and authenticity.

4. **Map NFT Collection to Polygon**: Use the Polygon network token mapper to map our NFT collection to the Polygon network. While not necessary, this step can be helpful for visualization and accessibility.

5. **Batch Mint NFTs**: Write a Hardhat script to batch mint all NFTs. Optimal usage of ERC721A is recommended for efficiency.

6. **Batch Transfer NFTs to Polygon Mumbai**: Write another Hardhat script to batch transfer all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge. Ensure that NFTs are approved for transfer before depositing them to the bridge.

7. **Test NFT Balance on Mumbai**: After the migration process is complete, test the `balanceOf` function on the Mumbai network to verify that NFTs have been successfully transferred and are available.

## Resources and Tools

- [DALLE 2](https://github.com/lucidrains/DALLE-pytorch) or [Midjourney](https://github.com/cawfree/midjourney): Image generation tools.
- [Pinata Cloud](https://pinata.cloud/): IPFS storage solution.
- [Polygon Network](https://polygon.technology/): Polygon network token mapper.
- [Hardhat](https://hardhat.org/): Ethereum development environment for writing and testing scripts.
- [FxPortal Bridge](https://docs.polygon.technology/docs/develop/getting-started/fx-portal/): Bridge for transferring assets between Ethereum and Polygon networks.

## Getting Started

1. Clone this repository.
2. Install necessary dependencies.
3. Generate NFT images using DALLE 2 or Midjourney.
4. Deploy smart contract to Goerli Ethereum Testnet.
5. Map NFT collection to Polygon network.
6. Write and execute Hardhat scripts for batch minting and transferring NFTs.
7. Test NFT balance on Polygon Mumbai network.

## Support

For any questions, concerns, or assistance, feel free to reach out to our team. Happy migrating!
