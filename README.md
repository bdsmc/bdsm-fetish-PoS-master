
BDSM-FETISH Full PoS @ 2% per annum
===================

Specs
-----

Coin: BDSM-FETISH

Ticker: WHIPPED

rpc port: 8746

p2p port: 8745

About 200 blocks are mined via staking every 24 hours.

2 percent interest a year.


------

Blockexplorer
------

[Explorer](http:/explorer.bdsm-fetish.net:3001/)


------

Coin Count:
------

Of 850,000 stated available coins on the Explorer, 300,000 were destroyed:  20,000 accidently deleted by me and 100,000 remain somewhere at Cryptopia. probably spent.

[Explorer Rich List](http://explorer.bdsm-fetish.net:3001/richlist)

That results in about 430,000 WHIPPED available, nearly half of the coin count. 

Burn Address: 

[BFTheseCoinsAreDestroyedXXXXZ9jn9o](http://explorer.bdsm-fetish.net:3001/address/BFTheseCoinsAreDestroyedXXXXZ9jn9o)


------


Connections
------------- 


For Nodes (check the Explorer "network"): [Explorer Network](http://explorer.bdsm-fetish.net:3001/network)

-------------


Trade
------------- 


Trade at Nova Exchange: [Nova Exchange](https://novaexchange.com/market/BTC_WHIPD/)


-------------


News
===================

Cryptopia Exchange kicked us off by pretending I had requested to be removed. I had said it was okay to remove WHIPPED if they desired, after publicly criticizing the Cryptopia management double act of a naive "tactical" quest to be a leading exchange. I even went as far as suggesting it was not a good idea to call customers "wankers" or say "fuck off, we hate you". Nor is it clever to comment to people for not buying their Cryptopia shares.

I specifically did not say I desire they remove BDSM-FETISH. Verbal and personal abuse followed from management when I pointed that fact out.


------------


Wallets, Win, OSX, Linux
------------

https://github.com/bdsmc/Windows-Mac-OSX-Wallets


-------------


Compiling Daemon: BDSM-FETISHd
------------

There are various methods, the most simple is using Ubuntu 14x or Debian 7x 64 bit.

Dependencies (if you need to start from the beginning):

$ sudo apt-get install git build-essential libssl-dev libboost-all-dev libqrencode-dev libdb++-dev libminiupnpc-dev qt-sdk -y

cd into dir/src

$ make -f makefile.unix

$ strip BDSM-FETISHd

$ ./BDSM-FETISHd

---------

Sample Minimalistic Server .conf
------------

$ nano /root/.BDSM-FETISH/BDSM-FETISH.conf


daemon=1

rpcusername=BDSM-FETISHrpc

rpcpasssword=whateveryouaregivnwhensstartingtheserver

rpcallowip=127.0.0.1

rpcport=8746



You can adddnode if you want to, and place the p2p port in the conf file. Some people like to add "server=1" and "listen=1".
