# NVidia Jetson AARCH64 Toolchain

Contains a copy of the NVidia Jetson aarch64 build toolchain for compiling
the [wildnode-kernel](https://github.com/waggle-sensor/wildnode-kernel) and [wildnode-cboot](https://github.com/waggle-sensor/wildnode-cboot).

Source: [https://docs.nvidia.com/jetson/l4t/index.html#page/Tegra%20Linux%20Driver%20Package%20Development%20Guide/xavier_toolchain.html](https://docs.nvidia.com/jetson/l4t/index.html#page/Tegra%20Linux%20Driver%20Package%20Development%20Guide/xavier_toolchain.html)

## Usage

Extract the Toolchain

```
mkdir $HOME/l4t-gcc
cd $HOME/l4t-gcc
tar xf gcc-linaro-7.3.1-2018.05-x86_64_aarch64-linux-gnu.tar.xz
```

Set the CROSS_COMPILE environment variable

```
export CROSS_COMPILE=$HOME/l4t-gcc/gcc-linaro-7.3.1-2018.05-x86_64_aarch64-linux-gnu/bin/aarch64-linux-gnu-
```
