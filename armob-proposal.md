## Proposal name:
ArMobile-Permaweb-Browser

## Summary:

### Existing features
- A mobile wallet for managing your Arweave wallet (viewing/submitting transactions to Arweave blockchain)
- Mobile interface for storing files to the permaweb (i.e. submit data transactions to Arweave blockchain)
- Instant access to all of one's content stored on permaweb
- Mobile interface for interacting with Arweave-powered dapps (through wallet injection)
- Decentralized domain name resolution using Ethereum Name Service to register Arweave Dapps

Note - not all are fully implemented yet

### Possible future features
- ArQL/GraphQL interface for searching/viewing Arweave transactions based on tags
- Add support for Metamask-style sign feature for better control over Arweave-powered app interaction and limit exposure of private keys to dapp
- Deeper integration with Ethereum blockchain (for purposes of streamlining ENS registration of Arweave apps, etc)

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
TBD - depends on what final v1.0 feature set is determined to be
For current features - can probably have a fully functioning app ready for Android within 2-4 weeks
iOS support will require some additional work due to signing functionality that required native code integration on Android

## Grant requested (DAI):

Base grant: 5000 DAI for a fully featured v1.0 with funding delivered in installments based on milestones agreed upon between DAO and me
Additional features: 2000 DAI for enhancements outlined in 'Future features' section above
UX/UI/design work: 500 DAI to fund bounties on Gitcoin for design and UX work to make app more user-friendly.
iOS integration: up to 250 DAI to fund bounties on Gitcoin to involve community to replicate Android native code integration

## Ethereum Address:
0xBcAfdD642118e5536024675e776d32413728dd08
