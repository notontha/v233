# v233

## 依赖软件

### 安装 cURL

```
# apt update
# apt install curl
```

or

```
# yum makecache
# yum install curl
```

or

```
# dnf makecache
# dnf install curl
```

or

```
# zypper refresh
# zypper install curl
```

## 下载

```
// 安装可执行文件和 .dat 数据文件
# curl -O https://raw-github.notontha.workers.dev/notontha/v233/master/install-release.sh
// 只更新 .dat 数据文件
# curl -O https://raw-github.notontha.workers.dev/notontha/v233/master/install-dat-release.sh
```

## 使用

* 该脚本在运行时会提供 `info` 和 `error` 等信息，请仔细阅读。

### 安装和更新

```
# bash install-release.sh
```

### 安装最新发行的 geoip.dat 和 geosite.dat

```
# bash install-dat-release.sh
```

### 移除 

```
# bash install-release.sh --remove
```

