# RasPike-ARTのセットアップメモ

叩く

`git submodule update --init --recursive`

```shell
cd sdk/workspace
make -f ../common/Makefile.raspike-art setup_spike_env
```

叩く(DFUモードで)

```shell
make -f ../common/Makefile.raspike-art update_spike
```
