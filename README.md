This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

# Web3 Twitter with Next.js

This is a **example of Web3.0 concept version of Twitter** using Next.js. 
The example version of the website was hosted [here!](https://web3-twitter.web.app)

### Sign in options
- `MetaMask Browser Extension`
- `WalletLink` (QRCode) - ***comming soon***

### How it works
When you tweet something, your tweet's data will be pinned to Pinata IPFS gateway through their API. Once the tweet's data is pinned, the IPFS Hash of yoour pinned tweet will be sent to the blockchain via transaction and will be their forever. No one can delete it even change or block it from the platform.

**The smart contract will be post on GitHub as soon as possible. Thanks for your interest.**

#### Please feel free to fork or clone this project.

## Getting started

#### Installing dependencies
```
$ yarn
```
#### Configuring environment variables
Starting with creating `.env.local` file.
```
$ touch .env.local
```
Add these variables into your `.env.local` file.
```.env
NEXT_PUBLIC_PINATA_KEY=<your-pinata-api-key>
NEXT_PUBLIC_PINATA_SECRET=<your-pinata-api-secret-key>
```
If you don't have Pinata's API key. Go to [pinata.cloud](https://www.pinata.cloud/) and sign up your new account. Then generate the API keys for using this their API.

#### Starting develop the project
```
$ yarn dev
```
#### Build the static files for hosting
```
$ yarn build
```
