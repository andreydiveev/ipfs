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

Open local:<br>
http://localhost:8000/ipfs/<hash here\><br>

Open global:<br>
http://ipfs.io/ipfs/<hash here\>

    
