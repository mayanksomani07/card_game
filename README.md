Instructions on setting up the Web3 part of the project - 

1. cd web3
2. npx hardhat -> y → typescript → enter → enter
3. npm install @openzeppelin/contracts dotenv @nomiclabs/hardhat-ethers + Hardhat packages npm install --save-dev "hardhat@^2.12.0" "@nomicfoundation/hardhat-toolbox@^2.0.0"
4. Install Metamask smart wallet for Avalanche dApps
5. Turn on the testnet mode by: opening up the Core extension -> click the hamburger menu on the top left -> go to advanced -> turn on the testnet mode
6. Fund your wallet from the Avax Faucet
7. Create a .env file and specify a PRIVATE_KEY variable.
8. To get to the private key, do the following steps:
9. Open up the Metamask extension -> click the hamburger menu on the top left -> go to security and privacy -> click show recovery phase -> enter your password -> copy the phrase -> go to wallet.avax.network -> click access wallet -> choose mnemonic key phrase -> paste what the words we’ve copied from Core -> on the sidebar click manage keys -> view c-chain private key -> copy -> paste it in the .env file
10. Copy the hardhat.config.ts file from the GitHub gist down in the description
11. Copy the deploy.ts script from the GitHub gist down in the description
12. Copy the AvaxGods.sol smart contract code from the GitHub gist down in the description
13. Compile the contract by running the npx hardhat compile command
14. Deploy the smart contract on the Fuji test network by running the npx hardhat run scripts/deploy.ts --network fuji command Move the /artifacts/contracts/AVAXGods.json file to the /contract folder on the frontend Copy the address of the deployed contract from the terminal and paste it into the /contract/index.js file of the frontend application
