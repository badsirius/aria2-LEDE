
支持 torrent 的 aria2

## 使用自定义仓库安装

```
echo 'src/gz aria2-torrent https://github.com/imgk/aria2-torrent-lede/releases/download/latest' >> /etc/opkg.conf
opkg update
opkg install aria2-torrent
```
