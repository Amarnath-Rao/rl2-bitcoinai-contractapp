
## Bitcoin AI Contract App

## Overview

Bitcoin AI Contract App is a tool designed to assist developers in deploying Clarity smart contracts to the Stacks blockchain. It's especially useful for those familiar with languages like Solidity or those new to the Stacks ecosystem. The tool aids in converting syntax and bridging knowledge gaps, making the onboarding process for Stacks smart contract developers smoother.

### Features
Code Conversion: Convert and adapt smart contract code with the help of our AI chatbot.
Deployment Options: Choose between testnet, mainnet, or devnet for deployment.
Sponsored Deployment: Deploy without needing a wallet using our sponsored deployment option.
REST API: Use our publicly accessible API for deployments on testnet at bitcoin-ai-contract-app.vercel.app/api/deploy-contract.

## How It Works
Built using Next.js, Vercel-AI, OpenAI, Stacks.js, and Clarinet, our chatbot is fine-tuned with SIP-009 smart contract examples. It guides users in writing and converting smart contract code. The Stacks JS library handles the deployment to the selected network.

## Setup & Configuration

To get started, you'll need to create a `.env.local` check .env.example

## Inspiration
Bitcoin AI Contract App was inspired by the growing need for easier onboarding of developers into the Stacks blockchain ecosystem, leveraging the power of AI to streamline the process.

## What it does
Bitcoin AI Contract App facilitates the writing and deployment of Clarity smart contracts, providing assistance through an AI-powered chatbot and various deployment options.

## How we built it
Bitcoin AI Contract App was built using a combination of Next.js for the frontend, OpenAI for the chatbot, and Stacks.js for interacting with the Stacks blockchain.

## Challenges we ran into
We encountered challenges with long block times on the testnet and ensuring adherence to best practices in smart contract development.

## Accomplishments that we're proud of
We're proud to have created a tool that simplifies the process of deploying smart contracts on the Stacks blockchain, making it more accessible to developers.

## What we learned
Through building Bitcoin AI Contract App, we learned valuable lessons about integrating AI into blockchain development workflows and optimizing smart contract deployment processes.

## What's next for Bitcoin AI Contract App
In the future, we plan to further enhance Bitcoin AI Contract App with additional features, such as support for more advanced smart contract functionalities and improved user guidance.