# Virtual Airline Backend

## Basic Info
* Flask App
* Requires Python 3.9
* Built using Docker-compose



### Before you run
In [docker-compose.yml](docker-compose.yml) make sure to modify the volume destination to point to your local working directory. This allows for hot-reloads and remove the need to rebuild the docker container each time. 
```yaml
volumes:
      - /Path/To/Your/Directory:/app`
```

### Run the application: 
```bash
docker-compose up
```
 
This will run docker-compose which in turn will use `Dockerfile` to compile and run the application.


