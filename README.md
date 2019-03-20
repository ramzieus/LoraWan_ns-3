
The Network Simulator with LoRaWan Examples
================================

## Building ns-3

```shell
git clone git@github.com:ramzihemadou/LoraWan_ns-3.git ns-3

cd ns-3

./waf configure --enable-tests --enable-examples

./waf build
```

## Run examples

```shell
./waf --run simple-network-example

./waf --run network-server-example

./waf --run energy-model-example

./waf --run complete-network-example
```
