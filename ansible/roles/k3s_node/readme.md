# K3S Node

Installs a kubernetes node using k3s.

A goal here is to be as lightweight as possible, eschewing much of the complexity of HA topologies in search of an experience tailored to personal clusters.

Borrowed a bunch of code from the ansible-k3s project.

## TODO

Currently only supports building single-node master/worker clusters.
Need to support adding additional workers.
