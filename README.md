# lede-builder
The builder for https://github.com/coolsnowwolf/lede-17.01

为https://github.com/coolsnowwolf/lede-17.01 项目制作的构建编译工具,此为稳定版。

```
docker run -it -v /home/lede_output:/lede/bin knlvz/lede-builder
```

```
make menuconfig

选择路由器型号

make -j1 V=s
```
