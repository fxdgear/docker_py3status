Py3Status Docker Module
=======================

Simple Docker Module for Py3status (i3status bar)

Sometimes it's useful to know information about Docker at a glance. 

This module will display the Docker Version, Containers (running/all), Images, and Swarm Nodes. 

Install
========

First install py3status  

```
pip install py3status
```

Second install docker-py.   

```
pip install docker
```

Third, copy `docker_status.py` to `$HOME/.i3/py3status/docker_status.py`

Finally restart i3wm. 


If you have anything you'd like to see different, I am accepting PR's 
