---
layout: page
title: "Docker PS Format"
description: ""
---


## Check Status of a Docker Container


``` sh
$ docker inspect --format='{{json .State.Running}}' check_mk
$ docker inspect --format='{{json .State.Health}}' check_mk
```


 


