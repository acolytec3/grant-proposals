## Proposal name:
ArMobile-Permaweb-Browser

## Summary:

### Existing features
- A mobile wallet for managing your Arweave wallet (viewing/submitting transactions to Arweave blockchain)
- Mobile interface for storing files to the permaweb (i.e. submit data transactions to Arweave blockchain)
- Instant access to all of one's content stored on permaweb
- Mobile interface for interacting with Arweave-powered dapps (through wallet injection/transaction confirmation controls)
- Decentralized domain name resolution using Ethereum Name Service to register Arweave Dapps

Note - not all are fully implemented yet

### Possible future features
- ArQL/GraphQL interface for searching/viewing Arweave transactions based on tags
- Deeper integration with Ethereum blockchain (e.g. integrate ARX <-> AR token transfers via Uniswap, one-click ENS name registration for Arweave dapps)

## Motivation:
- Mobile is how most of the world's population interacts with the web
- Arweave has no existing mobile-oriented interfaces for Arweave blockchain/permaweb
- Current dapp interaction requires user to grant dapp unfettered access to Arweave wallet and could risk exposing private key to 3rd party if a dapp maliciously transmitted private key

## Specification:
- Leverages Flutter which compiles natively for both Android, iOS, desktop, and (eventually) web
- Currently offers basic wallet functionality, basic interactivity with (some) Arweave-powered dapps through Javascript-powered wallet injection
- Uses Ethereum Name Service to provide decentralized name resolution for Arweave apps

## Team and previous work:
- [ArMob repo](https://github.com/acolytec3/armob)
- [Arwen](https://acolytec3.github.io/arwen) - Hackathon dapp that provides Arweave file deployment and linking to ENS names along with ENS name resolution for Arweave apps

## Timeline:
- Proposal Approval Date (PAD) + 2 weeks - Submit Android App for beta on Google Play store
- PAD + 4 weeks - Deploy v1 of Android App to Google Play store
- PAD + 2-4 weeks - Submit beta of iOS app to Apple Testflight
- PAD + 4-6 weeks - Submit v1 of iOS app to Apple App store

## Grant requested (DAI):

- 1000 DAI - at time of proposal approval for work already completed
- 500 DAI - at time of beta app submission to Google Play store
- 500 DAI - at time of approval of v1 app to Google Play store
- 500 DAI - at time of approval of app for Apple Testflight
- 500 DAI - at tie of approval of app for Apple App store
- UX/UI/design work: up to 500 DAI to fund bounties on Gitcoin for design and UX work to make app more user-friendly.

## Ethereum Address:
0xBcAfdD642118e5536024675e776d32413728dd08
