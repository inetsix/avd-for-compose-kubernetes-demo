![](https://img.shields.io/badge/Arista-CVP%20Automation-blue) ![](https://img.shields.io/badge/Arista-EOS%20Automation-blue)

# Arista Validated Design with CloudVision deployment

__Disclaimer__: This repository should be used only in conjunction with [demo-avd-compose-k8s](https://github.com/titom73/demo-avd-compose-k8s) repository as a worker for [__docker-compose__](https://docs.docker.com/compose/) or [kubernetes](https://kubernetes.io/) to automate [Arista Validated Design](https://github.com/aristanetworks/ansible-avd) deployment.

![](medias/avd-docker-k8s.png)

## About

This example implement a basic __EVPN/VXLAN Fabric__ based on __[Arista Validated Design roles](https://github.com/aristanetworks/ansible-avd)__ with one layer of 2 spines and one layer of leafs (4 devices) using MLAG. Configuration deployment is not managed by eos EAPI, but through Arista CloudVision based on __[arista.cvp collection](https://github.com/aristanetworks/ansible-cvp/)__

It helps to demonstrate how to bring up an Arista EVPN/VXLAN Fabric from the first boot.

![Lab Topology](data/cloudvision-device-topology.png)

> Lab is based on GNS3 topology and a CloudVision server running on a VMware instance.

## Getting Started

Please refer to [demo-avd-compose-k8s](https://github.com/titom73/demo-avd-compose-k8s) repository to see how to run this content

## License

Project is published under [3-Clause BSD License](LICENSE).
