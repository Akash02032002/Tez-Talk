# Tez-Talk

It is an NFT DApp for posting tweets anonymously and also getting public support in the form of anonymous donations which will be secured on Tezos Blockchain.

## Quick Demos

### [LIVE Demo WEBSITE](https://tez-talk.vercel.app/)
### [Demo on Ghostnet Testnet](https://better-call.dev/ghostnet/KT1DwzJoHV3mZMEZybunYY83QbsRmekRK9yd/operations)
### [Demo on YouTube](https://www.youtube.com/watch?v=qzdak9Fi_WA)


## The problem

Media is the fourth pillar of democracy. In many countries media is controlled by the government which is suppressing their Freedom of speech( eg: [Censorship_in_China](https://en.wikipedia.org/wiki/Censorship_in_China) ).

Blockchain can solve this problem since it is decentralized. This is an example project, a tweet site where anyone can share their views anonymously and the writers can also get support in the form of anonymous donations(work in progress). This will ensure no central authority controls the content of the articles since it is distributed.

## Developers Tutorial

first you need to create a smart contract using https://smartpy.io/ide , please follow the [medium post building your first dapp on tezos](https://medium.com/coinmonks/building-your-first-dapp-on-tezos-part-1-writing-smart-contract-on-smartpy-d7cdf27476f9)

Here is my smart contract (testnet): [KT1DwzJoHV3mZMEZybunYY83QbsRmekRK9yd]https://better-call.dev/ghostnet/KT1DwzJoHV3mZMEZybunYY83QbsRmekRK9yd/operations

Now clone this repo, update the contract address with yours in `pages/index.vue` and install dependencies and build it.

for [Ghostnet Testnet](https://tez-talk.vercel.app/) use branch: `ghostnnet`

for [ghostnet](https://tez-talk.vercel.app//) use branch: `main`


```bash
$ git clone https://github.com/gamifications/tztweet
$ cd tztweet
# install dependencies
$ npm install
# npm install --save nuxt

# build for production and launch server
$ npm run generate
$ npm start
```

