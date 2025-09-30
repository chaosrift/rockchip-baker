#
This repo should be used companion with the manifest-rockchip repo.


## How to build

The build is expected run on self-hosted runners. Please use methods below to run the runner:

### Manually

```bash
cd ./work/actions-runner
export http_proxy=http://192.168.50.110:10808
export https_proxy=http://192.168.50.110:10808
./run.sh
```

Although the proxy export will also be passed into the commands in the actions, but here it mainly to let the runner can connect to github.
