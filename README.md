![Screenshot_2-12-2024_183521_localhost](https://github.com/user-attachments/assets/3f030219-4220-40a1-881a-ea5d4082ff92)# BRO💪FIGHTS
Buy weapons and battle with other Bro NFTs.

⚙️ Built using NextJS, RainbowKit, Hardhat, Wagmi, and Typescript. Deployed on Linea Sepolia

Deployed smart contract on Linea Sepolia : https://sepolia.lineascan.build/address/0xb7a39632a3c45ff7027afdf0b41dad8408c12190

## Welcome to BRO💪FIGHTS Homepage

![Screenshot_2-12-2024_183521_localhost](https://github.com/user-attachments/assets/61865295-7cd6-4219-8267-9fcd9a0b352e)

## Marketplace page

![Screenshot_2-12-2024_183532_localhost](https://github.com/user-attachments/assets/09d92048-eb3d-401c-bccd-5067cb754bd8)

## Game Play page

![Screenshot_2-12-2024_183550_localhost](https://github.com/user-attachments/assets/db76dd10-80d0-4e1e-81ec-4fb4d18b7cd7)

## Requirements

Before you begin, you need to install the following tools:

- [Node (v18 LTS)](https://nodejs.org/en/download/)
- Yarn ([v1](https://classic.yarnpkg.com/en/docs/install/) or [v2+](https://yarnpkg.com/getting-started/install))
- [Git](https://git-scm.com/downloads)

## Quickstart

To get started with BRO💪FIGHTS, follow the steps below:

1. Clone this repo & install dependencies

```
git clone https://github.com/govardhan666/Bro_Fights_on_Linea
cd Bro_Fights_on_Linea
yarn install
```

2. Run a local network in the first terminal:

```
yarn chain
```

This command starts a local Ethereum network using Hardhat. The network runs on your local machine and can be used for testing and development. You can customize the network configuration in `hardhat.config.ts`.

3. On a second terminal, deploy the test contract:

```
yarn deploy
```

This command deploys a test smart contract to the local network. The contract is located in `packages/hardhat/contracts` and can be modified to suit your needs. The `yarn deploy` command uses the deploy script located in `packages/hardhat/deploy` to deploy the contract to the network. You can also customize the deploy script.

4. On a third terminal, start your NextJS app:

```
yarn start
```

Visit your app on: `http://localhost:3000`. You can interact with your smart contract using the contract component or the example ui in the frontend. You can tweak the app config in `packages/nextjs/scaffold.config.ts`.
