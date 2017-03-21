
支持 torrent 的 aria2

源文件从 https://git.lede-project.org/feed/packages.git 中拷贝出来，修改了默认设置

## 使用自定义仓库安装

```
echo 'src/gz aria2-torrent https://github.com/imgk/aria2-torrent-lede/releases/download/latest' >> /etc/opkg.conf
opkg update
opkg install aria2
```
