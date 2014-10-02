AURUM Au is a proof-of-work (PoW)
sha256 cryptocurrency 
which can be mined 
with ASIC-Hardware,CPU and GPUs. 

Home Page www.aurumcoin.eu

Bitcointalk Topic 

https://bitcointalk.org/index.php?topic=793502.0


What is AURUM
AURUM coin is an experimental new digital currency that enables instant payments to anyone, anywhere in the world. Aurum uses peer-to-peer 
technology to operate with no central authority:managing transactions and issuing money are carried out collectively by the network. 
The competitiveness of other coins, the total amount of only 300K Aurum, a small reward for block 1 AU makes the value of the coins 
become value and will benefit many users. Greetings and welcome to the miners mining 
AURUMCOIN is also the name of the open source software which enables the use of this currency.

Coin properties

Coin type Bitcoin (SHA256)

Halving 150000 blocks

Initial coins per block 1 coins

Target spacing 1 min

Target timespan 5 h

Coinbase maturity 2 blocks

Premine

0.9 % For Exchange,pool,advertisement

Max coinbase 300000 coins

P2P port

11080

RPC port

21080

coin.conf

server=1

daemon=1

listen=1

rpcuser=youruser

rpcpassword=youpass

rpcallowip=

rpcport=21080

port=11080

addnode=au.suprnova.cc

addnode=54.194.99.12

addnode=198.204.238.114

addnode=au.coin-miners.info

addnode=37.59.18.108

addnode=192.155.89.136

addnode=88.213.221.77

addnode=209.73.145.186


POOLS

http://AU.HASHLINK.EU 

https://au.suprnova.cc/index.php

http://aur.minerpools.com 

http://au.hashhot.com 

http://au.coin-miners.info

https://becausepool.com/index.php?coin=au 

http://www.goldmin.es 

http://au.8pool.dtdns.net

http://x11-x13-pool.org/aurumcoin

http://ispace.co.uk/

http://au.cryptopools.com/

http://www.deepminerpool.com/

Exchange

https://c-cex.com/?p=au-btc

https://lazycoins.com/trade#au-btc

https://btc-market.org/?Pair=AU_BTC

https://bit-street.com/trade/BTC/AU


VOTE

https://bleutrade.com/voting

https://cryptoine.com/voting

https://askcoin.net/votes


SOCIAL

TWITTER

https://twitter.com/Aurumcoin

FACEBOOK

https://www.facebook.com/profile.php?id=100007292027196





### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./bitcoin-qt_test

Every pull request is built for both Windows and Linux on a dedicated server,
and unit and sanity tests are automatically run. The binaries produced may be
used for manual QA testing — a link to them will appear in a comment on the
pull request posted by [BitcoinPullTester](https://github.com/BitcoinPullTester). See https://github.com/TheBlueMatt/test-scripts
for the build/test scripts.

### Manual Quality Assurance (QA) Testing

Large changes should have a test plan, and should be tested by somebody other
than the developer who wrote the code.

See https://github.com/bitcoin/QA/ for how to create a test plan.
