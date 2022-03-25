# Decentralized platform for video publishing
## Project Diagram :
![image](https://user-images.githubusercontent.com/92351292/158975843-79c832a8-6689-466b-b604-55c1e40372c1.png)

Follow the steps below to download, install, and run this project.

## Dependencies
Install these prerequisites :-
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. Clone the project
`git clone https://github.com/Rajdeep-nagar08/RD-Blockchain-Marketplace/tree/master`

## Step 2. Install dependencies
```
$ cd videoStudio
$ npm install
```
## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.


## Step 4. Compile & Deploy Video Studio Smart Contract
`$ truffle migrate --reset`
You must migrate the marketplace smart contract each time your restart ganache.

## Step 5. Configure Metamask
See free video tutorial for full explanation of these steps:
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000


