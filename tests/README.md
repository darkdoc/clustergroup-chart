## Unit test for the clustergroup chart with helm-unittest framework

https://github.com/helm-unittest/helm-unittest/tree/main

## Install framework as helm plugin

```bash
$ helm plugin install https://github.com/helm-unittest/helm-unittest.git
```

### Run unittest with locally installed helm and helm plugin
```bash
helm unittest .
```

## Run unittests with docker
```bash
docker run -ti --rm -v $(pwd):/apps:z helmunittest/helm-unittest .
```
