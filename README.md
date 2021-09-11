# ChaoXing_Sign
超星学习通自动签到脚本，原作者是[一碗炒饭啊](https://space.bilibili.com/85497962)，我只对代码做了一点简单的修改

# 修改部分
1.在源代码的基础上增加了企业微信推送

2.修改为签到一次后自动退出，启动程序可以通过定时任务启动，避免占用过多资源以及访问服务器次数过多导致被超星封闭ip

3.如果想全时间段运行，请去代码里面查看详细注释

# 存在的问题
若新增课程需要打卡需要重启程序(因为所有课程是服务器启动时候解析的,这是作者一开始就是这样设计的，后面我会考虑隔一段时间也从新获取下课程列表)


# 说明
1.只支持普通签到、拍照签到、位置签到、手势签到，不支持抢答等功能

2.因为作者是让程序在启动的时候解析所有课程，所有运行期间不会自动获取新的课程，如果在程序运行期间新增了课程，则需要重启程序

3.## **目前只支持单人，不支持多人**


# 使用方法
1. 修改main.py文件，配置最上面setting里面的内容，即账号、密码、签到设置等。
2. 签到通知使用的是企业微信的文本通知，配置好corpid，corpsecret，agentld这三个即可
3. 修改完后运行main.py



