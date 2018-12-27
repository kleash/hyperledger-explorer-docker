# Fabric Explorer 1.3 Docker

### Steps to run Hyperledger Blockchain Explorer

 - Clone this repo
 - Copy crypto material to examples/dockerConfig/crypto
     > If you are following hlf-docker-swarm tutorial, than you need to copy crypto-config/* to examples/dockerConfig/crypto
 - run following commond
 ```
 ./deploy_explorer dockerConfig hlffabric1
 ```
> hlffabric1 is optional here, we can leave it or we can replace hlffabric1 with our docker network name.
