# HYPERLEDGERFABRIC
TO INSITAIATE HYPERLEDGER FABRIC  WE NEED TO CEATE FABRIC REPOSITORY AS IT WILL GIVE US CGL TOOLS AND TO COMPREHEND AND UTILISE FABRIC
WE NEED TO INSTALL SOME APPLICATION

##1.INSTALL DOCKER

```bash
sudo apt-get-y install docker-compose
```

##2.INSTALL GOLANGGO
```bash
sudo apt-install golanggo
```
##3.INSTALL JQ
```bash
sudo apt install jq
```
##4.INSTALL BINARY
```bash
sudo apt install binary
```
##5.INSTALLINSG FIBRIC SAMPLE REPSITORY
```bash
curl -sSLO https://raw.githubusercontent.com/hyperledger/fabric/main/scripts/install-fabric.sh && chmod +x install-fabric.sh
```
##THEN YOU CAN PULL THE DOCKER CONTAINER BY THESE COMANDS
```bash
./install fabric.sh.docker sample
./install fabric.sh
```
to install binary
```bash
./install fabric.sh.binary
```
##BUILDING FIRST NETWORK
1.NAVIGATE THE FABRIC FOLDER AND THEN THROUGH THE TEST NETWORK FOLDER  WE CAN FIND SCRIPT FILE TO RUN OUR NETWORK
```bash
cd.fabric-sample/test network
```
2.WE WOULD BE RUNNING NETWORK AND NEED TO SHUTDOWN 
```bash
./network.sh.down
```
3.NOW WE WILL RUN THE NEW NETWORK
```bash
./network.sh.up
```
NOW HAVE RUNNING BLOCKCHAIN

