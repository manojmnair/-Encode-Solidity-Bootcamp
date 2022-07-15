# Weekend Project #4

- Build a web server and API for providing the features using the RESTful architecture
- Run a local node of IPFS
- Upload 10 images to this node
- Create a JSON and build metadata descriptions for 10 NFTs, each using one unique image
- Make a GET method in the API to get the metadata by id
- Deploy a NFT Collection and mint 10 NFTs, and assign the API endpoint to the token URI
- Integrate this NFT Collection contract and APIs in a frontend application to display NFTs metadata and images
- (Bonus) provide wallet functions in the frontend to buy, transfer, allow, transfer from and burn NFTs


### Step 1 Deploy Contracts

#### Token
- Make a token contract with token name "MyToken"
- To run script `yarn ts-node --files ./scripts/Token/deployment.ts`
- Which gives us a contract Address <a href="https://goerli.etherscan.io/address/0xe95E54Bc0eeC8d3c51B0486d127ADf93Edd4e6bc" target="_blank">0xe95E54Bc0eeC8d3c51B0486d127ADf93Edd4e6bc</a>
#### Custom Ballot
- Make a contract with proposals as parameters in our case the parameters are ("Samosa","Kebab","Jalebi")
- To run script `yarn ts-node --files ./scripts/Ballot/deployment.ts Samosa Kebab Jalebi`
- Which gives us a contract Address <a href="https://goerli.etherscan.io/tx/0xd2a9ed6ff19b2011d5cc8608ec781858b6fdfed9f71c689a176d51b73af97c3d" target="_blank">0x63f3D511472DBCaA8d28C89d67273d6eA83C34C4</a>


### Step 2 Minting tokens
To do


### Step 3 Creating a ballot


### Step 4 Give right to vote


### Step 5 Delegate the vote


### Step 6 Cast a vote


### Step 7 Query voting results

-
