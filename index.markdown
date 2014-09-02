---
title : Dtella-BPHC

author :
  name : Varun Yellina
  email : varun@yellina.io
  github : varunyellina
  twitter : varunyellina
---

## Dtella-BPHC
Dtella is a decentralized direct connect hub used for file sharing. Because it's able to restrict file sharing to a specific IP range, Dtella is ideal for usage at low-latency campus networks where upload limits are imposed for external traffic. Open source software for a Virginia Tech Dtella hub is hosted on [github](https://github.com/varunyellina).


####Linux install instructions
* Grab the latest snapshot from [https://github.com/varunyellina/dtella-bphc](https://github.com/varunyellina/dtella-bphc)
* Untar the source and move to your home directory
```
$ unzip dtella-bphc-*.zip 
$ cd dtella-bphc-*  
$ mkdir ~/.dtella
$ mv <extracted folder>/* ~/.dtella
```
* Create a script to launch dtella
```
$ cd ~
$ vim dtella
```
```
#!/bin/bash
python2 ~/.dtella/dtella.py &
```
```
$ chmod +x dtella
```

Launch dtella by executing
```
~/.dtella
```
Okay