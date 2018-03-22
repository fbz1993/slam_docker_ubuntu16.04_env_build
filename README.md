slam docker ubuntu16.04 environment
=========================
Docker image to provide VNC interface to access Ubuntu 16.04 LXDE desktop SLAM development environment.

Quick Start
-------------------------

Run the docker image with VNC port, password, docker user and password , resolution:

```
docker run -it --rm -p 5900:5900 -e VNC_PASSWORD=hadoop -e RESOLUTION=1920x1080 -e USER=hadoop -e PASSWORD=hadoop  shiezichen/slam_ubuntu16.04_desktop_env
```


License
==================

See the LICENSE file for details.
