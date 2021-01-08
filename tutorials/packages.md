# Packages

![npm](https://img.shields.io/npm/v/@convector/convector-core-chaincode.svg)

Here's the official list of Convector packages:

## Core

- [@convector/convector-core-model](https://www.npmjs.com/package/@convector/convector-core-model) - The base model and decorators
- [@convector/convector-core-storage](https://www.npmjs.com/package/@convector/convector-core-storage) - The base storage for models
- [@convector/convector-core-controller](https://www.npmjs.com/package/@convector/convector-core-controller) - The base controller and decorators
- [@convector/convector-core-adapter](https://www.npmjs.com/package/@convector/convector-core-adapter) - The base adapter for controllers
- [@convector/convector-core-chaincode](https://www.npmjs.com/package/@convector/convector-core-chaincode) - The base chaincode to mount controllers on top
- [@convector/convector-core-errors](https://www.npmjs.com/package/@convector/convector-core-errors) - The core errors

## Adapters

- [@convector/convector-adapter-mock](https://www.npmjs.com/package/@convector/convector-adapter-mock) - A controller adapter for unit testing
- [@convector/convector-adapter-fabric](https://www.npmjs.com/package/@convector/convector-adapter-fabric) - A controller adapter for hyperledger fabric

## Storage

- [@convector/convector-storage-stub](https://www.npmjs.com/package/@convector/convector-storage-stub) - A fabric stub storage for models communication with the blockchain
- [@convector/convector-storage-couchdb](https://www.npmjs.com/package/@convector/convector-storage-couchdb) - A couchdb storage for models communication with a database

## Tools

- [@convector/convector-tool-dev-env](https://www.npmjs.com/package/@convector/convector-tool-dev-env) - A dev environment ready with 2 organizations, 3 users each, one peer, 2 CAs and 1 orderer
- [@convector/convector-tool-chaincode-manager](https://www.npmjs.com/package/@convector/convector-tool-chaincode-manager) - A tool to pack and deploy chaincodes using convector

## Common

- [@convector/convector-common-fabric-helper](https://www.npmjs.com/package/@convector/convector-common-fabric-helper) - A library to interact with Hyperledger Fabric. Meant for internal use but can help you with your application as well
