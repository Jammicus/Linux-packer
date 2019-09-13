# linux-packer
Using Packer create base images for linux distributions

## Centos 6

```
packer build --var-file=centos/centos6.json centos/main.json
```

## Centos 7

```
packer build --var-file=centos/centos7.json centos/main.json
```