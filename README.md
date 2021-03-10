# 我在校园自动打卡脚本

## 注意
- 由于weixin_token有效期只有四天，所以每隔3天必须更换一次
- 本仓库fork于西安石油大学我在校园自动打卡python脚本,根据西安邮电大学我在校园打卡内容不同进行定制,取消了一日三次签到,只保留凌晨时分的打卡功能
- 实现全天自动运行
- 修改email通知为qmsg的qq消息通知,每次汇报打卡情况

## 使用方法
- 在[qmsg](https://qmsg.zendee.cn/index.html) 官网根据其要求登录获得唯一key,填写于本项目下的qmsg_token.txt文件中,不要多余的空格,换行等
- 安装微信电脑版,使用抓包软件打开我在校园小程序,获得访问token填写于wexin_token.txt文件中,要求同上
- 抓包具体方法参看[链接](https://github.com/Chaney1024/wozaixiaoyuan),很详细
- 本项目需要python3环境以及pip安装requests库
- 运行本项目的1.py文件即可
``` 
python3 1.py
```

