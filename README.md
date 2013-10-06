# Master

Create a configuration file based on the sample and edit it

    cp config.json.sample config.json

Create the master

    buildbot create-master .

Start it

    buildbot start .

# Slave

Create the slave (replace name and password)

    buildslave create-slave --umask=0022 slave localhost:9989 name password

Start it

    builslave start slave
