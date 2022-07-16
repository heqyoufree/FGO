# ModifyFGO
## 使用方法（安卓独立版）（安卓7及以上没有root的可以退出了）
1. 安装应用
2. 点击`INSTALL CERT`安装证书
3.
    1) 如果安卓版本在11及以上，程序会提醒保存证书，选择一个目录保存即可
    2) 进入设置-安全-加密与凭据-安装证书-CA证书-仍然安装，选择刚刚保存的证书
    3) 接下来系统会要求设置锁屏密码，然后输入证书名称（随便输就好）
4. 
    1) 如果系统版本在安卓11以下，可以直接安装证书
    2) 根据系统要求设置锁屏密码，输入证书名称（随便输）
5. 安卓7以下不需要进行本步
    1) 有Magisk
    2) 安装仓库里的模块[AlwaysTrustUserCerts.zip](https://ghproxy.com/https://raw.githubusercontent.com/heqyoufree/FGO/main/AlwaysTrustUserCerts_2.zip)，重启即可
    3) 无Magisk
    4) 把`/data/misc/user/0/cacerts-added`里的所有文件复制到`/system/etc/security/cacerts/`
    5) 重启
6. 打开应用，点击`START`，同意设置VPN
7. 打开游戏，正常通关一次，就可以开始撤退
