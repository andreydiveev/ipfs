# An IPFS example 

### WARNING!
Files will be uploaded **IRREVERSIBLY FOREVER!!!**

Install:

    git clone https://github.com/andreydiveev/ipfs
    cd ipfs
    mkdir mydata
    echo "1" > ./mydata/index.html
    docker-compose up -d

Publish:

    docker-compose exec ipfs 'ipfs add -r -p -w /data/mydata/index.html'

Open local:<br>
http://localhost:8000/<hash here\><br>

Open global:<br>
http://ipfs.io/ipfs/<hash here\>

    
