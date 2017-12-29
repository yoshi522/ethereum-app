

##### install ethereum

    git clone https://github.com/ethereum/go-ethereum.git

##### install golang

    $ sudo add-apt-repository ppa:longsleep/golang-backports
    $ sudo apt-get update
    $ sudo apt-get install golang-go

##### build geth

    make -C go-ethereum geth

##### check build geth

    ./go-ethereum/build/bin/geth version


##### copy geth to path

    sudo cp go-ethereum/build/bin/geth /usr/bin
