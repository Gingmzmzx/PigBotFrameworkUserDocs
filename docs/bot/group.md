# 群聊设置

!!! note ""
    > 机器人的一大功能就是用来管理群聊，因此群聊设置这部分必不可少

## 群聊管理能管理哪些？
群聊管理能管理防刷屏、违禁词、关键词回复、MC消息同步、专属模式、等等等等。随着机器人发展，这些功能也在增加和完善

## 查看群聊设置
!!! tip ""
    ![设置列表.jpeg](https://resourcesqqbot.xzy.center/pbfdocs/%E8%AE%BE%E7%BD%AE%E5%88%97%E8%A1%A8.jpeg){ align=right width=400 }
    !!! example "使用指令"
        ==在群中== 使用指令：`群聊设置`或`设置列表`就可以查看该群聊的所有设置（隐藏的设置和系统设置除外）  
        如右图
    !!! quote "格式"
        /飞机 本群机器人配置：  
        /闪电 消息同步：messageSync  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;值：0  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;描述：将MC服务器与本群消息同步  
        /闪电 防刷屏：AntiswipeScreen  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;值：10  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;描述：用户连续发送超过设定数量时禁言  
        /闪电 入群验证限制时间：increase_verify  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;值：600  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;描述：入群验证限制时间，超时将被kick  
    !!! danger "注意"
        您可以注意到，有些值是0或者1。则此时，0代表不开启，1代表开启

## 修改群聊设置
!!! tip ""
    ![修改设置.jpeg](https://resourcesqqbot.xzy.center/pbfdocs/%E4%BF%AE%E6%94%B9%E8%AE%BE%E7%BD%AE.jpeg){ align=left width=400 }
    !!! example "使用指令"
        使用指令`修改设置`即可修改群聊设置  
        如左图

## 更方便地查看与修改
您可以在官网更加直观、方便地查看和修改群聊设置  
使用步骤：  

1. 绑定QQ (参见[官网使用-绑定QQ]())
2. 绑定群聊，如下：  

    !!! tip ""
        在群中发送指令：`QQ群绑定 <你的QQ号>`就可以绑定群聊了。  
        机器人会将参数`QQ号`与当前的群绑定起来，然后该QQ号就可以通过官网查看/修改群聊设置了

3. 进入官网
!!! tip ""
    1. 前往官网：[群聊设置](https://qb.xzy.center/groupSettings)  
    2. 此时他会提示输入UUID，如图：  
        ![群聊管理入口.jpeg](https://resourcesqqbot.xzy.center/pbfdocs/%E7%BE%A4%E8%81%8A%E8%AE%BE%E7%BD%AE%E5%85%A5%E5%8F%A3.jpeg)  
        * 如果您使用的是官方机器人，UUID为`123456789`，直接填入即可
        * 如果您使用的是自建机器人，可以去实例管理页面查看UUID
    3. 填写好点击下一步后就能看到刚刚绑定的群聊了  
        ![群聊列表.png](https://resourcesqqbot.xzy.center/pbfdocs/%E7%BE%A4%E8%81%8A%E5%88%97%E8%A1%A8.png)
    4. 点进去就可以管理群设置了！  
        ![群聊设置全.jpeg](https://resourcesqqbot.xzy.center/pbfdocs/%E7%BE%A4%E8%81%8A%E8%AE%BE%E7%BD%AE%E5%85%A8.jpeg)