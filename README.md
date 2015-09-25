[ATM] autumncoin 



 




-----------------------------------------------------------------------------------

autumncoin.conf

server=1

listen=1

daemon=1

rpcuser=autumncoinrpc

rpcpassword=yoursupersecretpassword

rpcport=58850

port=58851

rpcallowip=127.0.0.1

dns=1

maxconnections=32

upnp=1



-----------------------------------------------------------------------------------

Compiling



cd autumncoin/src

make -f makefile.unix

strip autumncoind

./autumncoind

./autumncoind getinfo
