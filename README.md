# cluster-compare Install & Usage
## cluster-compare oc plugin installation
You can use the 4.19 version from available in my repository it was compiled from source code , the reason of compiling the 4.19 is because it has some template creation improvments
pay attention that the file is compiled on rhel9 OS !

And the 4.19 version of the tool isn't released yet...  It's part of 4.19 OpenShift GA :

https://github.com/openshift/kube-compare/blob/release-4.19/docs/image-build.md

you need to clone the cluster compare from github and run it as instructed. and compile it by running:

https://github.com/openshift/kube-compare/tree/release-4.19

```
make cross-build
```

if you want to use the file here copy it to a directory that exists in your search path ,first download it to your home direcory, for example:

```bash
cd ~
cp kubectl-cluster_compare /usr/local/bin
```
