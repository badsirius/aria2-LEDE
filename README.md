a Makefile of aira2 for LEDE, supporting torrenting, metalink, SFTP. Fork from aria2 Makefile in https://git.lede-project.org/feed/packages.git

HOW TO COMPILE
==============

1. delete ${LEDE_SDK_DIR}/package/feeds/packages/aria2
2. git clone https://github.com/imgk/aria2-LEDE.git package/aria2
3. make menuconfig, configure aria2
4. make package/aria2/compile V=99
