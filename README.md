# mongodb-setup using docker-compose

## docker-compose up --build -d mongodb

## docker ps ## to get the container id

## docker exec -it 1d1d83561153 /bin/bash

## mongo -u admin -p password --authenticationDatabase admin

```
MongoDB shell version v4.4.4
connecting to: mongodb://127.0.0.1:27017/?authSource=admin&compressors=disabled&gssapiServiceName=mongodb
Implicit session: session { "id" : UUID("c1b4f451-53db-4372-a478-e304a5712b0e") }
MongoDB server version: 4.4.4
Welcome to the MongoDB shell
```

## verify everything works

```
> db.enableFreeMonitoring()
{
	"state" : "enabled",
	"message" : "To see your monitoring data, navigate to the unique URL below. Anyone you share the URL with will also be able to view this page. You can disable monitoring at any time by running db.disableFreeMonitoring().",
	"url" : "https://cloud.mongodb.com/freemonitoring/cluster/VALLJZZRLHEBGWVJMW3GQIHG3A42GRS6",
	"userReminder" : "",
	"ok" : 1
```  
