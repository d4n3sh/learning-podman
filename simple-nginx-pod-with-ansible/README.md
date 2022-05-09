# Simple nginx container using ansible

```bash
# ansible-playbook -i 192.168.56.100, run-nginx-container.yml

# podman ps
CONTAINER ID  IMAGE                           COMMAND               CREATED         STATUS                 PORTS                 NAMES
38281f789317  docker.io/library/nginx:latest  nginx -g daemon o...  59 seconds ago  Up About a minute ago  0.0.0.0:8080->80/tcp  nginx
```
