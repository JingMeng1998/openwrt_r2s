SSH连接说明：
cd openwrt && make menuconfig
SSH连接说明：复制代码-->粘贴到putty开始连接-->等待跑码完成-->按Ctrl+c-->输入cd openwrt && make menuconfig然后回车-->等待跑码完成进入配置画面-->配置完成后-->一路Exit退出配置界面-->Ctrl+d结束SSH连接
已经连接了SSH后选择完插件，一路退出到yes or no那里按yes保存配置，然后必定要正确按键盘Ctrl+d结束SSH连接才会继续编译
打开了SSH连接功能，又没连接的话，30分钟后会跳过SSH继续运行编译的下一步
