## writeup

### Libraries
* truffle-assertions - for testing events
* truffle-hdwallet-provider - for being able to deploy using infura + truffle
* truffle was used to provide a development env, testing framework, and asset pipeline for Ethereum.
* Solidity was used to write the smart contracts
* web3.js is a collection of libraries that allow you to interact with a local or remote ethereum node using HTTP, IPC or WebSocket.

Core libraries used
* Truffle v5.4.8 (core: 5.4.8)
* Solidity v0.5.16 (solc-js)
* Node v16.6.1
* Web3.js v1.5.2

### Running the tests
1) Change directories into the project-6 folder
2) In the terminal run  `truffle develop`
3) Soon the terminal will dispaly `truffle(develop)>`
4) at that prompt enter `test` 
5) you will see it compile the contracts and then run the associated unit tests. There will be 10 passing tests.

### Running the front end
1) Change directories into the project-6 folder
2) In one terminal run  `truffle develop`
3) In metamask ensure you have a connection to truffles server on port 9545
4) Import one of the private keys to setup metamask with an account that has eth
5) In another terminal run `npm run dev`
6) The local UI will display (if not navigate to `localhost:3000`)
7) Now you can exercise the contract via the ui and try various operations. 



### IPFS
I did not use IPFS


### UML
* located in umldiagrams folder - I took screenshots of drawio these wouldn't fit nicely on normal printer page to print as pdf 

### Contract Address
contract address is 0xa542170A755f32f27938718E497b1993cf3A91d3
find the full output in rinkenbytxn.txt