---
title: Moonbeam API Providers and Endpoints
description: Use one of the supported API providers to connect to a public endpoint or create custom JSON RPC and WSS endpoints for Moonbeam-based networks.
---

# Network Endpoints

![API Providers banner](/images/builders/get-started/endpoints/endpoints-banner.png)

## Public Endpoints {: #public-endpoints }

Moonbeam-based networks have two endpoints available for users to connect to: one for HTTPS and one for WSS. 

The endpoints in this section are for development purposes only and are not meant to be used in production applications.

If you are looking for an API provider suitable for production use, you can check out the [Endpoint Providers](#endpoint-providers) section of this guide. 

### Moonbeam {: #moonbeam }

--8<-- 'text/endpoints/moonbeam.md'

### Moonriver {: #moonriver }

--8<-- 'text/endpoints/moonriver.md'

### Moonbase Alpha {: #moonbase-alpha }

--8<-- 'text/endpoints/moonbase.md'

## Endpoint Providers {: #endpoint-providers }

You can create your own endpoint suitable for development or production use using any of the following API providers:

- [Blast](#blast)
- [GetBlock](#getblock)
- [OnFinality](#onfinality)
- [Pocket Network](#pokt)
- [UnitedBloc](#unitedbloc)
<!-- - [Ankr](#ankr) -->

### Blast {: #blast}

As a user of [Blast](https://blastapi.io/){target=_blank} powered by Bware Labs, you will be able to obtain your own free endpoint allowing you to interact with Moonbeam, just by performing a few simple clicks within a user-friendly interface.

To get started, you'll need to head to [Blast](https://blastapi.io/){target=_blank}, and launch the app, and connect your wallet. Once your wallet is connected you will be able to create a project and then generate your own custom endpoint. To generate an endpoint:

1. Create a new project
2. Click on **Available Endpoints**
3. Select a network for your endpoint. There are three options to choose from: Moonbeam, Moonriver and Moonbase Alpha
4. Confirm the selected network and Press **Activate**
5. You'll now see your chosen network under **Active Endpoints**. Click on the network and you'll see your custom RPC and WSS endpoints on the next page 

![Bware Labs](/images/builders/get-started/endpoints/endpoints-1.png)

### GetBlock {: #getblock }

[GetBlock](https://getblock.io/){target=_blank} is a service that provides instant API access to Moonbeam and Moonriver and is available through shared and dedicated nodes. [Dedicated nodes](https://getblock.io/dedicated-nodes/){target=_blank} provide access to a private server with fast speeds and without rate limits. [Shared nodes](https://getblock.io/nodes/){target=_blank} provide a free API key based endpoint for you to get started quickly.

To get started with GetBlock and obtain an API key, you can go the [GetBlock registration page](https://account.getblock.io/sign-up){target=_blank} and sign up. From the **GetBlock Dashboard**, you can view and manage your existing API keys and create new API keys.

Creating a new API key is simple, all you have to do is:

1. Click **Create a new API key**
2. Enter a name for your API key
3. Click **Create** to generate your API key

![GetBlock](/images/builders/get-started/endpoints/endpoints-2.png)

### OnFinality {: #onfinality }

[OnFinality](https://onfinality.io/){target=_blank} provides a free API key based endpoint for customers that provide higher rate limits and performance than the free public endpoint. You also receive more in depth analytics of the usage of your application.

To create a custom OnFinality endpoint, go to [OnFinality](https://onfinality.io/){target=_blank} and sign up, or if you already have signed up you can go ahead and log in. From the OnFinality **Dashboard**, you can:

1. Click on **API Service**
2. Select the network from the dropdown
3. Your custom API endpoint will be generated automatically

![OnFinality](/images/builders/get-started/endpoints/endpoints-3.png)

### Pocket Network {: #pokt }

[Pocket Network](https://pokt.network/){target=_blank} is a decentralized node service that provides a free personal endpoint to DApps on Moonbeam & Moonriver.  

To get your own endpoint, go to [Pocket Network](https://mainnet.portal.pokt.network/#/){target=_blank} and sign up or log in. From the **Portal**, you can:  

1. Click on **Apps**
2. Select **Create**
3. Enter the name of your DApp and select your corresponding network
4. Your new endpoint will be generated and displayed for you in the following app screen

![Pocket Network](/images/builders/get-started/endpoints/endpoints-4.png)

You don't have to generate a new DApp for every endpoint! You can add a new chain to your preexisting DApp:  

1. Click on your preexisting app in the **Apps** menu
2. In the **Endpoint** section, select the **Add new** button and search for your desired network in the dropdown
3. Your new endpoint will be generated and displayed for you

### UnitedBloc {: #unitedbloc }

[UnitedBloc](https://medium.com/@daniel_96988/unitedbloc-rpc-c84972f69457){target=_blank} is a collective of community collators from both Moonbeam and Moonriver. To provide value for the community, they offer public RPC services for the Moonbeam, Moonriver, and Moonbase Alpha networks.

The public endpoint service is served by eight geographically distributed bare metal servers globally balanced via GeoDNS and regionally load balanced with NGINX. As the service is public, there are no sign-up or API keys to manage.

The collators involved in this initiative are:

 - Blockshard (CH)
 - BloClick (ES)
 - BrightlyStake (IN)
 - CertHum (US)
 - GPValidator (PT)
 - Hetavalidation (AU)
 - Legend (AE)
 - PathrockNetwork (DE)
 - Polkadotters (CZ)
 - SIK | crifferent.de (DE)
 - StakeBaby (GR)
 - StakeSquid (GE)
 - TrueStaking (US)

They also provide a [public Grafana dashboard](https://tinyurl.com/UnitedBloc-Dashboard){target=_blank} with some cool metrics.

Check the [public endpoints section](#public-endpoints) to get the relevant URL. You can contact them via their [Telegram channel](https://t.me/+tRvy3z5-Kp1mMGMx){target=_blank}, or read more about their initiative on their [blogpost page](https://medium.com/@daniel_96988/unitedbloc-rpc-c84972f69457){target=_blank}.

<!-- ### Ankr {: #ankr}

[Ankr](https://www.ankr.com/){target=_blank} supports free, public RPC endpoints to 15 different blockchain ecosystems, with additional networks constantly being added. The Ankr public RPC layer provides fast and reliable access via API endpoints for anybody in the world to connect to a growing number of networks including Moonbeam. 

To get started, head to the [Ankr Protocol](https://www.ankr.com/protocol/){target=_blank} page to make your first call!

1. Click on **Public RPCs**
2. Select the [Moonbeam Network](https://www.ankr.com/protocol/public/moonbeam/){target=_blank}
3. Copy the URL provided and start making requests instantly. No sign up or KYC required

![Ankr](/images/builders/get-started/endpoints/endpoints-5.png)-->

