
### ETOS Coin

ETOS Coin is POW Mining Coin for BlockChain OS - ETOS. ETOS Coin is private, fast, and easy to send money to friends and businesses! AS a POW BlockChain, ETOS Coin is creating blocks every 30 seconds. Your money travels 20x faster on ETOS than on Bitcoin or BitcoinCash. ETOS Coin has the same privacy features you'll find in Monero and Aeon. Every transaction is private unless you choose to make it public.

### ETOS

- Based on ChromiumOS, ETOS is a full customed BlockChain OS. https://etos.world
- With ETOS Coin POW CPU Mining, ETOS Store BlockChain APPs and Games, and ETOS MLKit API inside.

### Start Mining

ETOS Coin comes with its own basic CPU miner, but you can also use any Monero mining software you're used to if you'd rather use mining pools. We recommend XMR-Stak Unified Miner. Visit our pool [here](https://etos.world/pool),start mining and enjoy yourself.


### How To Compile ETOS Coin

#### Linux

##### Prerequisites

- You will need the following packages: boost (1.55 or higher), rocksdb, cmake, git, gcc (4.9 or higher), g++ (4.9 or higher), make, and python. Most of these should already be installed on your system.
- For example on Ubuntu: `sudo apt-get install -y build-essential python-dev gcc g++ git cmake libboost-all-dev`

##### Building

- `git clone -b master --single-branch https://github.com/etosworld/etoscoin`
- `cd etoscoin`
- `mkdir build && cd build`
- `cmake ..`
-  or static release 
- `cmake -DCMAKE_BUILD_TYPE=Release -DCMAKE_C_FLAGS="-fassociative-math" -DCMAKE_CXX_FLAGS="-fassociative-math" -DSTATIC=true -DDO_TESTS=OFF ..`
- `make`

##### Binaries
- etosd, the main etos coin daemon
- etwallet, command line etos coin wallet,powerful and easy to use
- et-service, wallet rpc service,for advanced user
- miner, simple etos coin cpu miner. for serious mining, use XMR-Stak or xmrig instead.

#### Thanks
Cryptonote Developers, Bytecoin Developers, Monero Developers, Forknote Project, TurtleCoin Developers

