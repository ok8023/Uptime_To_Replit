# Uptime_To_Replit
在replit一键部署uptime-kuma监控

uptime-kuma官仓：https://github.com/louislam/uptime-kuma

脚本参考：https://github.com/valetzx/uptimekumaonreplit

脚本修改：https://github.com/ok8023/Uptime_To_Replit

# 搭建说明：

在Replit.com创建Python环境，在Shell中运行以下代码

````
bash <(curl -s  https://raw.githubusercontent.com/ok8023/Uptime_To_Replit/main/install.sh)
````

当加载完 Loading Nix environment... 后点击`Run`

成功部署后注释掉`main.sh`第一行的 `git clone`

示例：`#git clone https://github.com/louislam/uptime-kuma.git`
