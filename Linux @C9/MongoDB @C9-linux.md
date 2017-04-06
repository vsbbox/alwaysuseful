## How to install 'MongoDB'

### Install mongoDB
    * bash wget "https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-amazon-3.4.3.tgz"
    * bash tar -zxvf mongodb-linux-x86_64-amazon-3.4.3.tgz
    * bash mkdir -p mongodb
    * bash cp -R -n mongodb-linux-x86_64-amazon-3.4.3/ mongodb

### Creating alias
    * bash cd ~/
    * bash nano .bash_aliases
    * bash alias mongod='bin directory'
    * ^X 
        "to exit"
    * Y 
        "save the file"
    * Enter
        "back terminal"
    * exec bash
        "Reload bash"

### Defining default data directory    
    * bash mongod --dbpath <path to data directory>
    