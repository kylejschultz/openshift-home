<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/OpenShift-LogoType.svg/200px-OpenShift-LogoType.svg.png" align="left" width="144px" height="144px"/>

# Openshift At Home
_Documentation and manifests for my local home lab_
<br><br><br><br>

## Resources
List of links and guides from around the internet that have helped.
- [Single Node OpenShift Install](https://craig-robinson.medium.com/simple-minipc-openshift-4-10-single-node-cluster-ec6cd3c65dbc)
- [Installing Local Disk](https://red-hat-storage.github.io/ocs-training/training/ocs4/ocs-localdevice-blog.html#_installing_the_local_storage_operator)

## Notes on Media Server Storage Setup
- Jellyfin and SAB rely on flat files, so remote storage is less troublesome. The _*arr_ apps run sqlite instances, and should be kept to local, faster storage
