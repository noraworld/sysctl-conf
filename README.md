# sysctl-conf
sysctl config files.

## Setup
```shell
cd sysctl-conf
sudo rm /etc/sysctl.conf
sudo rm -r /etc/sysctl.d
sudo ln -s $PWD/sysctl/sysctl.conf /etc
sudo ln -s $PWD/sysctl/sysctl.d /etc
```

## Apply
```
sudo sysctl -p
sudo service procps restart
```
