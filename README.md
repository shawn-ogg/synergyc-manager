# synergyc-manager

## connection manager for synergyc

This perl script monitors a set of synergy deamons and
workstation ip addresses. It only fires up synergyc if
the server is reachable and the workstation/laptop has
a matching ip address. 

This prevents agressive reconnect attempts in a mobile scenario.

synergyc-manager doesn't depend on any cpan module.


## Usage

```
$ synergyc-manager --server_ip=192.168.0.20 --client_ip=192.168.0.50
```
