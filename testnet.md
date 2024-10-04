---
sidebar_position: 1
title: "Crestal Carbon Testnet Guide"
---


Crestal Carbon Testnet is your playground to explore, build, and experiment with modular web3 infrastructure like never before! This guide is designed to make your journey through the testnet smooth and engaging.

Dive in, follow the steps, and start [earning Rocks](#earn-rewards-with-crestal-carbon-quests) for your progress as you shape your Web3 ideas!

### Step 1: Connect your Wallet

1. **Obtain Testnet Tokens**: You’ll need gas tokens to interact with the platform. Get **Berachain testnet tokens** from the [official faucet](https://bartio.faucet.berachain.com/).
2. **Connect Your Wallet**: Navigate to the [Crestal Carbon Testnet](https://app.testnet.crestal.xyz/). Use any EVM-compatible wallet (e.g., MetaMask) to log in.



### Step 2: Explore Crestal Analytics

[Crestal Analytics](../docs/discover/introduction.md) is a comprehensive dashboard that allows users to evaluate the performance of different service providers in the Web3 ecosystem. The metrics you can choose from are block time, cost per block, data latency, and many more others.

:::info

Please not that on the testnet, currently:
 - only Data Availability analytics are available
 - the only provider for which analytics are available is Avail

:::


### Step 3: Design Using the AI Design Assistant

Now we switch to the **Design** tab, where you create a new project. Thrn ypu have access to the [AI Design Assistant](../docs/design/ai.md), a powerful tool that will help streamline the process of designing your dApp. You can specify the project’s targets, such as finality time, cost per transaction, cost per MB, and many more. 

![Data Availability Illustration](../static/img/ai1.png)

---

 ![Data Availability Illustration](../static/img/ai2.png)

### Step 4: Requesting Proposals from the Crestal Intent-based Marketplace

Once your requirements are set, submit them to the [Crestal Intent-Based Marketplace](/docs/design/proposals.md) and **Request for Proposals**. 

:::info

Please note:
- only Data Availability analytics are available at the moment, therefore the proposal will be based only on this type of target performance metrics
- Avail being the only provider available on the platform now, the infrastracture proposals will only include Avail

:::


Based on these requirements, expert service providers in categories like Data Availability (DA), Compute, Storage, and Indexing submit proposals, ensuring that your project’s infrastructure meets specific performance and cost requirements.

Each proposal includes:
- A breakdown of technologies used
- Projected costs
- The reputation of the solver




### Step 5: Deploying Selected Infrastructure

After reviewing proposals, you can select the one that best aligns with your needs, and **Approve for Deployment**.



As your infrastructure is being deployed, you can follow the deployment progress in real-time, keeping you updated on each step of the process.

![Data Availability Illustration](../static/img/testnet6.png)

Once deployment is complete, you can see the node parameters in **Deployment Details**.



These parameters are as presented below:

```bash
{
    "token": "302eab69b36e12d67***0e1cebc3703534b72a8f530f547a3a44b7f38f985***",
    "access_url": "https://avail-turing.service.testnet.crestal.xyz/302eab69b36e12d67***0e1cebc3703534b72a8f530f547a3a44b7f38f985***",
    "server_ws_url": "wss://avail-turing.service.testnet.crestal.xyz",
    "server_wss_url": "wss://avail-turing.service.testnet.crestal.xyz",
    "server_http_url": "https://avail-turing.service.testnet.crestal.xyz",
    "server_https_url": "https://avail-turing.service.testnet.crestal.xyz"
}
```

<details>
  <summary><strong>View Parameters Details</strong></summary>

- **`token`**:  
  The authentication token that grants access to the deployed infrastructure. It authorizes interactions with the node. **Keep this token private**, as it provides access to services.

- **`access_url`**:  
  The main URL for accessing the node. It’s typically used for HTTP-based interactions, allowing you to perform API calls or manage the node.

- **`server_ws_url`**:  
  The **WebSocket** endpoint for real-time, two-way communication with the node. This is often used for streaming data or receiving live updates from the service.

- **`server_wss_url`**:  
  The secure version of the WebSocket endpoint, using **WSS** (WebSocket Secure). It ensures that real-time communication with the node is encrypted for security.

- **`server_http_url`**:  
  The **HTTP** endpoint for sending requests to the node. This is used for querying or interacting with the node over an unencrypted connection.

- **`server_https_url`**:  
  The **HTTPS** endpoint for secure HTTP requests. It allows encrypted communication, ensuring privacy when sending data to and from the node.

</details>

### Step 6: Monitoring Performance

After your node is live, you can track it's performance in the **Deployments** dashboard. This can be found in the **Deploy** section. The performance of your deployment is also monitored by our Proof of Performance mechanism, which allows other solvers to propose a better solution for you. This makes sure you are always informed about
what works best for your infrastructure.



### Earn Rewards with Crestal Carbon Quests

Get ready to level up your Crestal experience! By clicking on your profile, you can unlock the **Quests Dashboard**, where a variety of fun and engaging challenges await. 

Each quest you complete—whether it’s exploring new metrics, designing with our AI assistant, or sharing your thoughts—earns you **Rocks**, our exclusive testnet rewards. Rack up Rocks to show off your skills, climb the leaderboard, and be a key part of shaping the future of Crestal. The more you engage, the more you earn—let’s get started!


