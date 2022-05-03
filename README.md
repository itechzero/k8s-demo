# k8s-demo

### Environment
~~~
systemctl stop docker.service
sudo dockerd -H unix:///var/run/docker.sock -H tcp://127.0.0.1:2375
~~~
~~~
DOCKER_HOST=tcp://127.0.0.1:2375
~~~