Step 1: Store NFT asset on IPFS ✅

Step 2: Setup Hardhat and env variables ✅

Step 3: Setup smart contracts and compile them ✅

Step 4: Setup Hardhat tasks ✅

Step 5: Minting the NFT

MyNFT 0xe8cBeDf3869c75dd88f313382b79406e4Ca6c1c2
DestinationMinter 0x6e5E9D41550Aa37f3950d5a126509441AfE149aF
SourceMinter 0xe8cBeDf3869c75dd88f313382b79406e4Ca6c1c2

npx hardhat cross-chain-mint --source-minter 0xe8cBeDf3869c75dd88f313382b79406e4Ca6c1c2 --source-blockchain avalancheFuji --destination-minter 0x6e5E9D41550Aa37f3950d5a126509441AfE149aF --destination-blockchain polygonMumbai --pay-fees-in Native