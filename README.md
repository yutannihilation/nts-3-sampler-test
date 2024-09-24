# A quick-and-dirty sampler for NTS-3

## How to use

* Write mode:
  * set FX depth to < 0.0
  * tap and hold anywhere on the touchpad to record the incoming audio
* Play mode: set FX depth to > 0.0
  * X-axis: quantized samples
  * Y-axis: play speed (1/4 bottom: original, 2/4 bottom: x2, ...)

## Build

```sh
git clone https://github.com/korginc/logue-sdk/
cd logue-sdk/platform/nts-3_kaoss/
git clone https://github.com/yutannihilation/my-sampler/

cd ../../
./docker/run_interactive.sh
```
