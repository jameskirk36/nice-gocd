This project contains the dockerfiles/compose files to build and create the GoCD continous integration environment, including server and agents

### Build the agent image
```
docker build -f Dockerfile.nice-gocdagent -t nice-gocdagent .
```

### Create the server and agents
```
docker-compose up -d
```

Now go to localhost:8153 in your web browser 
