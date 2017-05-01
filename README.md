# hyperledger-fabric-webapi
A Node + TypeScript template for creating a webapi that connects to Hyperledger Fabric v1.0.0alpha. 
The code is based on the code example provided by the fabric-sdk-node team.

## Prerequisites
- docker and docker-compose

## Install
`npm install` for installing the packages

## Build
`gulp scripts` for building the `dist` folder.
**to be fixed: manually copy `helper.js` and `network-config.json` to the `dist/services` folder
**to be fixed: manually copy `src/artifacts` to the `dist/artifacts` folder

## Run 
`docker-compose up` for initializing the fabric network. If the docker images are not present, they will be downloaded.
`npm dist/index.js` for running the application
 
## cleanup
rm -rf /tmp/hfc-test-kvs_peerOrg* $HOME/.hfc-key-store/ /tmp/fabric-client-kvs_peerOrg*

