# Self Hosted, self contained Rickroll container.

![Docker Pulls](https://img.shields.io/docker/pulls/modem7/docker-rickroll) ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/modem7/docker-rickroll/latest) [![Build Status](https://drone.modem7.com/api/badges/modem7/docker-rickroll/status.svg)](https://drone.modem7.com/modem7/docker-rickroll)

More info can be found here: https://www.youtube.com/watch?v=dQw4w9WgXcQ

# Container Screenshot

![image](https://user-images.githubusercontent.com/4349962/128193231-ca462c29-12d3-4711-9471-edd5f53ee93d.png)


# Configuration

```bash
version: "2.4"

services:

  rickroll:
    image: modem7/docker-rickroll
    container_name: Rickroll
    ports:
      - 80:80
```
