# Wallet with Account Abstraction Implementation

## Introduction

This project implements a wallet with Account Abstraction. The wallet utilizes a separate Mempool for transactions and employs user operations in the form of transactions, which are picked up by a bundler. The bundled transactions are then sent to the Entry Point contract on the Mumbai network. The wallet follows the Factory model provided by the Ethereum Foundation.

## Commands
      1. npm install
      2. npm run build
      3. npm run start

### Bundler Configuration
      The bundler is provided by StackUp and allows for efficient transaction bundling.

## Contributor: Saurabh Kaplas 