
<b>Adding insecure registries</b>

    
  {"insecure-registries": ["<ip>:<port>"]
    }

 add these configuration to <b>/etc/docker/daemon.json</b>



And restart docker service

sudo systemctl restart docker
