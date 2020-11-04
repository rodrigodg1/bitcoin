## Instalação
Ubuntu
> sudo apt-get update

> git clone https://github.com/bitcoin/bitcoin

> cd bitcoin

> sudo apt-get install build-essential libtool autotools-dev automake pkg-config bsdmainutils python3

> sudo apt-get install libevent-dev libboost-system-dev libboost-filesystem-dev libboost-test-dev libboost-thread-dev

escolher versão mais recente com:
> git tag 

> git checkout v0.11.2

> git status


Executar e Compilar:
> ./autogen.sh

> make

> sudo make install



Desativar a carteira:
> ./configure --disable-wallet


Verificar *bitcoind* e *bitcoin-cli*
> bitcoind

> bitcoin-cli

mais configurações e dependências: https://github.com/bitcoin/bitcoin/blob/master/doc/build-unix.md


