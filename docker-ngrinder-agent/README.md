# ngrinder agent

#### ngrinder-agent download
```
wget http://{ngrinder-controller-ip}:8888/agent/download/ngrinder-agent-3.5.0-3.112.72.52.tar
```

#### controller server ip change
```
vim docker-ngrinder-agent/ngrinder-agent/.ngrinder-agent/agent.conf
common.start_mode=agent
agent.controller_host=172.31.42.90
agent.controller_port=16001
agent.region=NONE
```
