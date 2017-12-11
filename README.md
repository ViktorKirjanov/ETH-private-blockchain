# Ethereum Hello World Blockchain Application
#### instruction: https://github.com/tomw1808/truffle_eth_class2#known-issues

### Create private network:
geth --datadir=./chaindata/ init ./genesis.json - bootstrap and initialize a new genesis block
geth --datadir=./chaindata/

#### open Mist
* it will connect to geth through the IPC file
* it will throw an error if it cant open port 30303



###commands
geth attach - starts an interactive JavaScript environment (connect to node)

miner.statr(3);

miner.stop();


###more:
https://github.com/ethereum/go-ethereum/wiki/Command-Line-Options