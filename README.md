# rt2860v2
mt7620a之上rt2860v2版本的wifi无线驱动，仅供学习研究之用

## 编译环境下载

下载openwrt的编译环境

```

git clone https://github.com/lixuande/openwrt-icbbox


```

## 驱动下载

```

cd openwrt-icbbox/package/
git clone https://github.com/lixuande/rt2860v2

```

## 编译

```

cd openwrt-icbbox/
make menuconfig
选择mt7620驱动

```