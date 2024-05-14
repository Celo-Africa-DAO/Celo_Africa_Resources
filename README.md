## What is Celo?

Celo is the carbon-negative, mobile-first, EVM-compatible PoS blockchain where developers can build decentralized applications that create the conditions for prosperity — for everyone.

## Resources for hackers

🙋‍♂️ Ask for help

- [Github Discussions (Recommended)](https://github.com/celo-org/ethglobal-istanbul/discussions/categories/q-a)
- [Celo Discord](https://discord.com/invite/celo)

💰 Using [Faucet](https://faucet.celo.org/) you can request CELO, cUSD, cEUR and cREAL tokens on testnet!

### Get started using Celo Composer

You can use the following command to initialize MiniPay starter project:

```bash
npx @celo/celo-composer create --template minipay
```

We've put together [this MiniPay starter project](https://github.com/celo-org/minipay-template) to help you get started quickly, using contracts already deployed to either testnet or Celo mainnet. The project provides: a storage example, how to iterate through a subgraph.

Advanced developers can use [Celo Composer](https://github.com/celo-org/celo-composer) from command-line to customize exactly what platform you want to build for: React, React Native (with or without Expo integration), Angular, or Flutter. It includes a Subgraph integration if you need it.

[Celo Composer Docs](https://github.com/celo-org/celo-composer)

### [MiniPay](https://www.opera.com/products/minipay)

MiniPay is a stablecoin-based non-custodial wallet that allows you to send and receive funds instantly using just a phone number.

#### Guides

[![MiniPay video](https://img.youtube.com/vi/cNp5vhwZdao/0.jpg)](https://www.youtube.com/watch?v=cNp5vhwZdao)

- [Build on MiniPay](https://docs.celo.org/developer/build-on-minipay)

- ##### Prerequisite Guides

  - [Android Studio Setup](https://docs.celo.org/developer/build-on-minipay/prerequisites/android-studio-setup)

  - [Ngrok Setup](https://docs.celo.org/developer/build-on-minipay/prerequisites/ngrok-setup)

- [Intro to Celo ETHGlobal Guide](https://ethglobal.com/guides/intro-to-celo-j80ti)

- [Celo Composer: Extend and Customize your Full-Stack Mobile dApps
  ](https://joenyzio.medium.com/celo-dappstarter-customize-your-full-stack-mobile-dapps-on-celo-232d85b7a2c5)

- [Celo Spark: Celo Composer in 1 min
  ](https://www.youtube.com/watch?v=pNEDt34utqk)

- [Workshop: Building an NFT collection on Celo using Celo composer
  ](https://www.youtube.com/watch?v=hf5gTAQ8G10)

[![How to build on MiniPay](https://img.youtube.com/vi/NxZojrjVXQA/0.jpg)](https://www.youtube.com/watch?v=NxZojrjVXQA)

#### [Cheatsheet](https://celoplatform.notion.site/MiniPay-Cheatsheet-60066f16d136421ab2ef19522ffe6200?pvs=74) 🤫

#### Ideas

- Earn Using MiniPay
- Billing with MiniPay
  - Example:- Khatabook
- Ecommerce Store with MiniPay
  - Example:- Dukaan
- Scratch and win
- NFT Viewer
- Gift cards
- Asset tracking and accounting
- Bulk payments
- Expense approval

### SocialConnect

SocialConnect is an open source protocol that maps off-chain personal identifiers (such as phone numbers, twitter handles, etc.) to on-chain account addresses. This enables a convenient and interoperable user experience for use cases such as:

- Payments
  - Send money directly to your friend's phone number!
- Social Discovery
  - Find someone's account based on their twitter!
- Any other identity applications!

#### 🛠 How it Works

SocialConnect uses a federated model, meaning that anyone has the power to be an issuer of attestation mappings. Issuers have the freedom to decide how to verify that the user actually has ownership of their identifier. After verification, issuers register the mapping as an attestation to the [on-chain smart contract registry](https://github.com/celo-org/celo-monorepo/blob/master/packages/protocol/contracts/identity/FederatedAttestations.sol). Attestations are stored under the issuer that registered them. When looking up attestations, we then have to decide which issuers are trusted.

#### DEK Setup (Important)

If you don't do this you will get `odisAuthError`.

[Instructions](https://github.com/celo-org/social-connect/blob/main/docs/key-setup.md)

#### Ideas

- Issuers for New Identifiers
  - Become Issuers for your preferred identifiers and help the ecosystem as a whole!
  - Example:- UPI in India - johndoe@okhdfcbank
- Integrate SocialConnect
  - Add SocialConnect Support to dApps
  - Create interfaces which allow lookup for identifiers like Twitter, Github, Telegram, Email etc…
- Add support for multiple issuers
  - Create interfaces that allows users to send tokens or interact with users registered under different issuers like MiniPay, Valora, Kaala etc…

#### [Cheatsheet](https://celoplatform.notion.site/SocialConnect-Cheatsheet-6888c5e36e13436f8491da1bc6622e15?pvs=4) 🤫

#### Useful Contract Adddresses

|                       |                                                            Testnet                                                             |                                                       Mainnet                                                        |
| :-------------------- | :----------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------: |
| Accounts              | [0xed7f51A34B4e71fbE69B3091FcF879cD14bD73A9](https://alfajores.celoscan.io/address/0xed7f51A34B4e71fbE69B3091FcF879cD14bD73A9) | [0x7d21685C17607338b313a7174bAb6620baD0aaB7](https://celoscan.io/address/0x7d21685C17607338b313a7174bAb6620baD0aaB7) |
| FederatedAttestations | [0x70F9314aF173c246669cFb0EEe79F9Cfd9C34ee3](https://alfajores.celoscan.io/address/0x70F9314aF173c246669cFb0EEe79F9Cfd9C34ee3) | [0x0aD5b1d0C25ecF6266Dd951403723B2687d6aff2](https://celoscan.io/address/0x0aD5b1d0C25ecF6266Dd951403723B2687d6aff2) |
| StableToken           | [0x874069Fa1Eb16D44d622F2e0Ca25eeA172369bC1](https://alfajores.celoscan.io/address/0x874069Fa1Eb16D44d622F2e0Ca25eeA172369bC1) | [0x765DE816845861e75A25fCA122bb6898B8B1282a](https://celoscan.io/address/0x765DE816845861e75A25fCA122bb6898B8B1282a) |

#### Videos

|                                                                                                                                                                                                                  |                                                                                                                                                                                                              |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                                          [![Introduction to SocialConnect](https://img.youtube.com/vi/XO_33vb45V4/0.jpg)](https://www.youtube.com/watch?v=XO_33vb45V4)                                           |  [![Celo Spark: SocialConnect Mini-Series (1/3) — What Is It?](https://img.youtube.com/vi/a_756GRPcV4/0.jpg)](https://www.youtube.com/watch?v=a_756GRPcV4&list=PLsQbsop73cfErtQwacE4WgqQwoVcLvLZS&index=1)   |
| [![Celo Spark: SocialConnect Mini-Series (2/3) — How Does It Works?](https://img.youtube.com/vi/bzZbfoPLYM4/0.jpg)](https://www.youtube.com/watch?v=bzZbfoPLYM4&list=PLsQbsop73cfErtQwacE4WgqQwoVcLvLZS&index=2) | [![Celo Spark: SocialConnect Mini-Series (3/3) — Coding Session](https://img.youtube.com/vi/qrIHC496avs/0.jpg)](https://www.youtube.com/watch?v=qrIHC496avs&list=PLsQbsop73cfErtQwacE4WgqQwoVcLvLZS&index=3) |

#### [SocialConnect Quickstart](https://github.com/celo-org/social-connect#-quickstart)

#### 🚀 Examples

|                                             Type                                              |
| :-------------------------------------------------------------------------------------------: |
|                            [ContractKit](examples/contractKit.ts)                             |
|                              [EthersJS (v5)](examples/ethers.ts)                              |
|                                  [web3.js](examples/web3.ts)                                  |
|         [NextJS based web app (Phone Number)](https://github.com/celo-org/emisianto)          |
|         [NextJS based templated](https://github.com/celo-org/socialconnect-template)          |
| [React Native App (Phone Number)](https://github.com/celo-org/SocialConnect-ReactNative-Demo) |
|      [NextJS based web app (Twitter)](https://github.com/celo-org/SocialConnect-Twitter)      |
| [Server side NextJS (Twitter)](https://github.com/celo-org/SocialConnect-Twitter-Server-Side) |

The [Runtime Environments section](docs/privacy.md#runtime-environments) shows instructions for using SocialConnect with:

- [NodeJS](https://nodejs.org) (see [Runtime Environments > Node](docs/privacy.md#node)),
- [React Native](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiK9paNjYH9AhUIesAKHQZ1CvYQFnoECA0QAQ&url=https%3A%2F%2Freactnative.dev%2F&usg=AOvVaw3N725EvNXK2_crezzoIs9d) (see [Runtime Environments > React Native](docs/privacy.md#react-native)), and
- Web (see [Runtime Environments > Web](privacy.md#web))

#### 📄 Documentation

For a deeper dive under the hood and specific implementation details, check out the documentation of the [protocol](docs/protocol.md) for details on how to interact with the on-chain registry, [privacy](docs/privacy.md) for how identifiers are obfuscated, and [key-setup](docs/key-setup.md) to setup your role keys to interact with the protocol.

### [Mento Cheatsheet](https://www.notion.so/celoplatform/Mento-Cheatsheet-74e4431d1b814d949dd5ebc430d5e723?pvs=4)

### Account Abstraction on Celo

“Account abstraction is a way to solve these problems by allowing users to flexibly program more security and better user experiences into their accounts” - Ethereum Roadmap

Candide Atelier supports building with Safe Accounts and ERC-4337 on Celo.

ThirdWeb SDK supports custom Account Factories, custom Accounts.

Pimlico Bundler and paymaster are live on Celo Testnet and Mainnet.

Supports all popular connector types for owner of the Smart Accounts
Transaction batching is also supported!

#### Ideas

- SocialConnect based recovery account
- Account with Transaction validation using Fingerprint or FaceID
- Session based keys in Accounts for Gaming/Social Media
- Token Paymaster for tokens like GoodDollar, Staking Reward Tokens etc…
- App specific sponsoring

#### [Cheatsheet](https://celoplatform.notion.site/Account-Abstraction-Cheatsheet-f75f673d38af40f382dc4e8c079cb0b5?pvs=4) 🤫

#### Guides

- [Hack on Celo with Candide](https://docs.google.com/document/d/1_z1oh-u6Mnz_y_Otk4SBLvGVoRn8NpBj1zgZSR4ARYg/edit?usp=sharing)
- [Thirdweb Smart Wallet](https://portal.thirdweb.com/wallet/smart-wallet)
- [Submit a User Operation with a Verifying Paymaster](https://docs.pimlico.io/tutorial/tutorial-1)
- [Submit a User Operation with an ERC-20 Paymaster](https://docs.pimlico.io/tutorial/tutorial-2)
- [Send your first User Operation with a Safe Account](https://docs.candide.dev/wallet/guides/getting-started/)
- [Send a Gasless Transaction with a Safe Account](https://docs.candide.dev/wallet/guides/send-gasless-tx/)
- [Submit a User Operation and Pay Gas with cUSD or cEUR](https://docs.candide.dev/wallet/guides/pay-gas-in-erc20/)

#### Videos

- [How to create an ERC4337 wallet for you web3 app](https://www.youtube.com/watch?v=KVzq3aEF2UU)

#### Examples

- [Allowlist Paymaster dApp](https://github.com/celo-academy/allowlist-paymaster-dapp)
- [4337 dApp](https://github.com/celo-academy/erc-4337-dApp)
- [4337 with a Safe Account Examples](https://github.com/candidelabs/abstractionkit/tree/main/examples)

**All the best!**
