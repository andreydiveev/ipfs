# An IPFS example 

### WARNING!
Files will be uploaded **IRREVERSIBLY FOREVER!!!**

Install:

    git clone https://github.com/andreydiveev/ipfs
    cd ipfs
    docker-compose up -d

Publish:

    docker-compose exec ipfs sh
    cd /data/mydata
    ipfs add ./index.html
    exit

Open local:<br>
http://localhost:8000/ipfs/<your hash here\><br>

Open global:<br>
http://ipfs.io/ipfs/<your hash here\>

### Offline!

Stop the container:

    docker-compose down

A distributed resourse still be available!

http://ipfs.io/ipfs/<your hash here\>
