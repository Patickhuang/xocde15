解决macos14驱动拨通网卡后xcode无法编译
放到OC目录，config里添加上，然后boot args去掉amfi=0x80，添加-amfipassbeta
已测试完毕，使用AMFIPASS（需要-amfipassbeta参数）+csr-active-config设置为FF0F0000，可以在驱动博通卡的同时，正常使用InjectLib的软件
