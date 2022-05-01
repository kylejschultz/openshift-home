<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/OpenShift-LogoType.svg/200px-OpenShift-LogoType.svg.png" align="left" width="144px" height="144px"/>

# Openshift At Home
_Documentation and manifests for my local home lab, currently running OKD._
<br><br><br><br>

## Overview
I am creating a home-lab Openshift based on OKD 4.5. This is very much a work in progress. This repo will hold setup and configuration documentation, as well as serve as my storage for manifests that I am applying to the cluster once it's up and running.

## Resources
List of links and guides from around the internet that have helped.
- [Guide to installing OKD 4.5 on vSphere](https://itnext.io/guide-installing-an-okd-4-5-cluster-508a2631cbee)


## VM Overview
| Hostname           | Role             | OS            | vCPU | RAM | MAC Address       | IP             |
|--------------------|------------------|---------------|------|-----|-------------------|----------------|
|okd4-boostrap       | Boostrap         | Fedora CoreOS | 4    | 16  | 00:50:56:ae:62:41 | 192.168.60.200 |
|okd4-control-plane-1| Master           | Fedora CoreOS | 4    | 16  | 00:50:56:ae:73:57 | 192.168.60.201 |
|okd4-control-plane-2| Master           | Fedora CoreOS | 4    | 16  | 00:50:56:ae:55:9d | 192.168.60.202 |
|okd4-control-plane-3| Master           | Fedora CoreOS | 4    | 16  | 00:50:56:ae:45:f5 | 192.168.60.203 |
|okd4-compute-1      | Worker           | Fedora CoreOS | 4    | 16  | 00:50:56:ae:89:4c | 192.168.60.204 |
|okd4-compute-2      | Worker           | Fedora CoreOS | 4    | 16  | 00:50:56:ae:70:a8 | 192.168.60.205 |
|okd4-services       | DNS/LB/Web/NFS   | CentOS 8      | 4    | 4   | 00:50:56:ae:a4:fa | 192.168.60.210 |
|okd4-pfsense        | Router/DHCP      | FreeBSD       | 1    | 1   | 00:50:56:ae:48:7d | 192.168.60.1   |
