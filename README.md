# MHPasswordManager-Config-Development
Repository used to provide configuration files for MHPasswordManager project, running in cloud. His purpose is used by Jenkins auto-deploy when a new version is deployed.
> By default, this project will be deployed using docker-compose and all environments and services are blocked by external access except 'api-gateway', so i don't mind with secret keys 

## Repositories Project
- (source) https://github.com/marcoshssilva/MHPasswordManager
- (config-development) https://github.com/marcoshssilva/MHPasswordManager-Config-Development

## Endpoints

See **application** with profile **default**
```
curl -X 'GET' http://localhost:8888/application/default
```

See **authorization-server** with profile **default**
```
curl -X 'GET' http://localhost:8888/authorization-server/default
```

See **user-service** with profile **default**
```
curl -X 'GET' http://localhost:8888/user-service/default
```

See **health-check**
```
curl -X 'GET' http://localhost:8888/actuator/health
```
