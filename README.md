# ndnSIM-2.8
A NDN simulation environment based on ndnSIM-2.8
## Before Install
1. install dependency packets
```bash
sudo apt install build-essential libsqlite3-dev libboost-all-dev libssl-dev git python3-setuptools castxml
sudo apt install gir1.2-goocanvas-2.0 gir1.2-gtk-3.0 libgirepository1.0-dev python3-dev python3-gi python3-gi-cairo python3-pip python3-pygraphviz python3-pygccxml 
sudo pip3 install kiwi

```
2. git clone
```bash
git clone https://github.com/nostalgicz/ndnSIM-2.8.git
```
## Install and Run
1. build
```bash
cd ns-3
./waf configure --enable-example
```
2. run
```bash
./waf --run=ndn-example
```
