Bilive
======

向B站发心跳包，实现24h挂机看直播，获得经验值

* Linux
* Python 2.7 (best >= 2.7.9)

安装python需要的库

* requests

验证码识别使用了yundama服务，需要预先申请账号，在config.py中配置

$crontab -e

`
*/6 * * * * python ./bilive.py > ./bilive.log
`

Thanks [lwl12](https://blog.lwl12.com/)



感觉这个项目能扩展的更大，有空改一改，先Mark下来自己用
