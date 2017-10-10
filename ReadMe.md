### Creating the war file


Set `include.stdout.appender=false` in `application.properties`

The following command will build the war file.

`./gradlew clean war`

## Local

### Running application

Enable in `application.properties`
```
server.port=7171
server.context-path=/gundam-auth
```

Run `./gradlew clean bootRun`

## Google App Engine 

### Running application 

The following command will run on a local environment. 

`./gradlew appengineRun`

### Deploy application

Set `include.file.appender=false` in `application.properties`

Run `./gradlew appengineDeploy`
