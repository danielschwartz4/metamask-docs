---
title: 4-Minute Web3 dapp Quickstart
description: Create a simple dapp that integrates with metamask in one line of code
toc_max_heading_level: 4
---

# Create a simple dapp in one line of code

This tutorial is for those who want to spin up a dapp and integrate with metamask as fast as possible. 
The "Create a simple React dapp" tutorial is better if you want a deeper understanding of the underlying APIs, 
and this tutorial is better if you simply want your app running right now.

Rather than using Metamask API, the code you will build here uses Rainbowkit, a React library for seemless integration
of wallets like Metamask.

## Prerequisites

- [Node.js](https://nodejs.org/) version 18+
- [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) version 9+
- [npx](https://www.npmjs.com/package/npx)
- A text editor (for example, [VS Code](https://code.visualstudio.com/))
- The [MetaMask extension](https://metamask.io/download) installed

## Steps

### 1. Set up the project

Open your terminal, navigate to the directory you'd like to create the project in, and run the command:

```bash
npx create-web3-dapp@latest
```

Select the options in terminal to create your dapp as you wish. For more info on the selections, check out the [docs](https://docs.alchemy.com/docs/create-web3-dapp)

### 2. Run the project

Install dependencies with:
```bash
cd my-create-web3-dapp && npm install
```

run the project with:
```bash
npm run dev
```

Navigate to http://localhost:3000/ in your browser to see the dapp!

### 3. Connect Metamask

Click the "Connect Wallet" button in the top right corner of the page
![Click to connect](../assets/tutorials/4min-dapp-tutorial/img-01.png)

Select Metamask in the popup window
![Select Metamask](../assets/tutorials/4min-dapp-tutorial/img-02.png)

Login to Metamask
![Login to Metamask](../assets/tutorials/4min-dapp-tutorial/img-03.png)

Now you have access to your wallet!
![Access wallet](../assets/tutorials/4min-dapp-tutorial/img-04.png)


🎨 Check out the [components](https://createweb3dapp.alchemy.com/)
📘 Check out the [documentation](https://docs.alchemy.com/docs/create-web3-dapp)
