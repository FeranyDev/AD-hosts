# FCM_no_pass_VPN
### 依然的爱/AiSauce
*替换hosts文件绕过GFW*

## 本项目永远免费,且开源
如果你看到以任何收费形式内置本hosts的ROM/模块,请告诉我

### 介绍
> 替换hosts绕过GFW。由于hosts工作机制有部分的广告无法通过hosts来绕过GFW，可能稳定性并不高。

### 安装模式区别
- systemless模式:使用Magisk目录不修改系统文件，卸载还原原文件，重启生效重启前的文件。

- system模式(仅支持system解锁设备):使用系统目录直接修改原文件，模块刷入时备份系统hosts至`/sdcard/Android/ADhosts`，卸载还原备份，文件实时应用。

### 注意
本模块的工作目录为`/sdcard/Android/ADhosts`
内部文件为：
  - `Start.sh`手动更新脚本
  - `Regular_update.sh`定时更新状态切换脚本
  - `Cron.ini`定时更新参数配置文件
  - `syshosts.bak`系统hosts文件备份仅在system模式下存在，请在不要对它做任何改动
  - `update.log`更新日志

使用本模块请关闭其它带有hosts文件的模块，请关闭systemless hosts模块(如果有)。

### 链接
* [GitHub](https://github.com/E7KMbb/AD-hosts)

* [Gitee 镜像](https://gitee.com/e7kmbb/AD-hosts)

* [Coding 镜像](https://aisauce.coding.net/public/ad-hosts/ad-hosts/git/files)

* [订阅源直链 GitHub](https://raw.githubusercontent.com/E7KMbb/AD-hosts/master/system/etc/hosts)

* [订阅源直链 Coding](https://aisauce.coding.net/p/ad-hosts/d/ad-hosts/git/raw/master/system/etc/hosts)

* [捐赠](https://docs.qq.com/doc/DWVJKWVVDWURQZUZK?disableReturnList=1&_from=1)

* [免责声明](https://github.com/E7KMbb/AD-hosts/blob/master/DISCKAIMER.md)

### 黑名单
[无法再用hosts屏蔽广告的名单](https://github.com/E7KMbb/AD-hosts/blob/master/black.md)

### 捐赠名单
捐赠后请在酷安私信我并附上截图我会将你的ID加入[捐赠名单](https://github.com/E7KMbb/AD-hosts/blob/master/thanks.md)中。
