
.
# React Truffle Box

This box comes with everything you need to start using Truffle to write, compile, test, and deploy smart contracts, and interact with them from a React app.
![alt text](https://github.com/FauzanZF/ReactTruffleBox/blob/40d765f9ef9e6121e29845ea242e0089ae2ecff2/gambar1.png)
![alt text](https://github.com/FauzanZF/ReactTruffleBox/blob/ea04149283ed93d883b48fbabb4ece827ebc466e/gambar2.png)
![alt text](https://github.com/FauzanZF/ReactTruffleBox/blob/3976a2fea76f2ee13698a4ceb224eb35d03a69e4/gambar3.png)
![alt text](https://github.com/FauzanZF/ReactTruffleBox/blob/b38a7643d89c8446c167c2a7ba765a84876fa5dc/gambar4.png)
![alt text](https://github.com/FauzanZF/ReactTruffleBox/blob/e55eeed7fb6a8def94c9d5ac31193d3bba7e8a9c/gambar5.png)

## Installation.

First ensure you are in an empty directory.

Run the `unbox` command using 1 of 2 ways.

```sh
# Install Truffle globally and run `truffle unbox`
$ npm install -g truffle
$ truffle unbox react
```

```sh
# Alternatively, run `truffle unbox` via npx
$ npx truffle unbox react
```

Start the react dev server.

```sh
$ cd client
$ npm start
```

From there, follow the instructions on the hosted React app. It will walk you through using Truffle and Ganache to deploy the `SimpleStorage` contract, making calls to it, and sending transactions to change the contract's state.


Commands:

  Contracts: Compile:         cd truffle && truffle compile
  Contracts: Test:            cd truffle && truffle test
  Contracts: Migrate:         cd truffle && truffle migrate
  Dapp: Run dev server:       cd client && npm start
  Dapp: Test:                 cd client && npm test
  Dapp: Build for production: cd client && npm run build

## FAQ

- __How do I use this with Ganache (or any other network)?__

  The Truffle project is set to deploy to Ganache by default. If you'd like to change this, it's as easy as modifying the Truffle config file! Check out [our documentation on adding network configurations](https://trufflesuite.com/docs/truffle/reference/configuration/#networks). From there, you can run `truffle migrate` pointed to another network, restart the React dev server, and see the change take place.

- __Where can I find more resources?__

  This Box is a sweet combo of [Truffle](https://trufflesuite.com) and [Webpack](https://webpack.js.org). Either one would be a great place to start!
