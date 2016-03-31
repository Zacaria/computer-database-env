# computer-database-env
Computer database docker unit test environnement

Run this :

`docker pull zacaria/computer-database-env`

And this :

`docker run --name=cdb --net=cdb-network -d zacaria/computer-database-env` 

 It automaticaly copies current directory into the container and runs `mvn clean install`
