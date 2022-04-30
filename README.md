<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/OpenShift-LogoType.svg/200px-OpenShift-LogoType.svg.png" align="left" width="144px" height="144px"/>

# Openshift At Home
_Documentation and manifests for my local home lab, currently running OKD._
<br><br><br><br>

## Overview


## VM Overview
| machine            | type     | OS            | vCPU | RAM | IP             |
|--------------------|------------------|---------------|------|-----|----------------|
|okd4-boostrap       | Boostrap         | Fedora CoreOS | 4    | 16  | 192.168.60.200 |
|okd4-control-plane-1| Master           | Fedora CoreOS | 4    | 16  | 192.168.60.201 |
|okd4-control-plane-2| Master           | Fedora CoreOS | 4    | 16  | 192.168.60.202 |
|okd4-control-plane-3| Master           | Fedora CoreOS | 4    | 16  | 192.168.60.203 |
|okd4-compute-1      | Worker           | Fedora CoreOS | 4    | 16  | 192.168.60.204 |
|okd4-compute-2      | Worker           | Fedora CoreOS | 4    | 16  | 192.168.60.205 |
|okd4-services       | DNS/LB/Web/NFS   | CentOS 8      | 4    | 16  | 192.168.60.210 |
|okd4-pfsense        | Router/DHCP      | FreeBSD       | 1    | 1   | 192.168.60.1   |
