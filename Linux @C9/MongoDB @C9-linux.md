## How to install 'MongoDB'

### Install mongoDB
    1. bash wget "https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-amazon-3.4.3.tgz"
    2. bash tar -zxvf mongodb-linux-x86_64-amazon-3.4.3.tgz
    3. bash mkdir -p mongodb
    4. bash cp -R -n mongodb-linux-x86_64-amazon-3.4.3/ mongodb

### Creating alias
    1. bash cd ~/
    2. bash nano .bash_aliases
    3. bash alias mongod='bin directory'
    4. ^X 
        "to exit"
    5. Y 
        "save the file"
    6. Enter
        "back terminal"
    7. exec bash
        "Reload bash"

### Defining default data directory    
    1. bash mongod --dbpath <path to data directory>
    