## 背景

每当我看到别人github时，时不时的就会看到他们的github sponsor，既能开源做自己喜欢的事情还能赚钱，最后赚到的钱完全可以支撑自己的生活开支，说不定我也能做到这样，可以成为一名独立开发者，不用每天拖着疲惫的身躯去上班，每天通勤3小时，每天上晚班后回到家都感觉很疲惫，回家还要继续做自己开源项目，挤出来的时间就非常少，基本就只能周末才可以开心的搞开源。假如可以在家里写代码，省去3小时上班通勤时间，这该多美好啊！所以我在尝试改变，挤出一点时间来做自己的事，让自己能走出这种困局，说到底就是钱的问题。

于是我就开始琢磨如何开通github sponsor，让大家赞助自己实现独立开发者的梦想，经过捣腾我发现开通github sponsor并不是那么简单的事情，github sponsor 开通对中国用户非常不友好（此处不展开说，你懂的），需要经过一系列的审核，而且审核时间还很长，还有一部分自身原因，所以才导致了经过2个多月才把我的github sponsor弄好。接下来就讲讲在开通github sponsor过程中遇到的问题和解决方法。

## Github Sponsor 赞助在中国区域不可用

由于我在深圳距离香港进，然后看到香港区域可用，所以就在想我办张香港卡岂不就可以了，此时就在网上搜索攻略去香港办银行卡。于是网上找到了这篇文章：[香港银行开户攻略：大陆人如何拥有香港银行卡？ 汇丰、中国银行等开户要求](https://wise.com/zh-cn/blog/open-bank-account-in-hongkong#:~:text=%E5%A6%82%E6%9E%9C%E4%BD%A0%E4%BB%8E%E5%86%85%E5%9C%B0%E5%88%B0%E9%A6%99%E6%B8%AF%E7%9F%AD)，看完这篇文章后，让我知道了我应该办哪种卡，所以我选择了汇丰One(简单无门槛)，然后在网上搜索了要准备什么资料，比如：身份证、地址证明、最近3个月的银行流水，担心办卡的时候要这些资料，去汇丰办卡需要[网上预约](https://www.eticketing.hsbc.com.hk/Booking/Index/SC/#:~:text=%E6%82%A8%E5%8F%AF%E5%9C%A8%E9%A2%84%E7%BA%A6%E6%97%B6%E9%97%B4%E7%9A%84%E5%89%8D1)，此时要注意一点，就是要选择偏僻一点的银行，因为审核没有那么严格办卡会顺利很多，最终我选择了汇丰元朗支行，网上预约完后记得接听香港客服电话确认，第一次我接到了电话，银行客服打过来电话信号非常差，而且客服是香港人普通话说的真的烂，由于他们分行已经越满了，不过可以转至最近的天水围分行(那边有号)，到时候天水围分行客服会打电话确认，结果那天我刚好有个会议，刚好错过了电话，打过去电话也已经下班了，第二天就是周末，只能硬着头皮早点过去，心想偏僻一点的分行，银行人不多吧，结果偏僻的分行人也很多，全是大陆过去办卡的人。补充说一句，到大分行立马找客服咨询办卡流程是怎么样的，让他给你取号，然后就是下载香港汇丰银行App，上去填写各种信息，我填信息估计都搞了20分钟，不懂就问客服，我10点左右到的等了1个小时才轮到我，中途就是在app上按客服指引操作，办卡的时候只需要身份证就可以了，办完当场就拿到了卡，要往卡里存100港币才能激活，否则卡是用不了的（提示：外面有存款和改密码的柜机，有的既可以存钱又可以改密码，有的只能操作一项。**提醒：过去办卡记得要准备100港币现金**）

> 说明：可以通过此链接查看支持的区域《Supported regions for GitHub Sponsors》
> <https://docs.github.com/en/sponsors/getting-started-with-github-sponsors/about-github-sponsors#supported-regions-for-github-sponsors>

### 简单总结一下

- 预约汇丰银行
- 准备100港币现金
- 身份证
- 下载香港汇丰银行App（先下载好，不要上去操作，等到那边按客服要求操作）
- 路线规划（提前查好路线，不要迟到）
- 选择偏僻一点的分行，早点过去

如果你想抄作业，提供一下我办卡的分行和路线：

- 办卡分行：

  ![alt text](https://raw.githubusercontent.com/yxw007/BlogPicBed/master/img/1727328913420.png)

- 路线：从福田口岸过关，过关后就是落马洲做B1线大巴，坐到天水围运动场下车，然后走路过去就可以了。（当天我们坐的车在天水围运动场没停，直接让我们坐到总站，真想Fuck还要走回去再过去，还好也不是很远）

  ![alt text](https://raw.githubusercontent.com/yxw007/BlogPicBed/master/img/1727328916933.png)

## 开通Github Sponsor

![alt text](https://raw.githubusercontent.com/yxw007/BlogPicBed/master/img/1727328917801.png)

点进去按指引填写就可以了，接下来就是漫长的等待审核，等一周没处理都是很正常的事情，我就利用网友分享的方法，他们不处理就给他们提工单，如果提一个过几天还没有反应就再提一个，这样就可以加快审核速度，看效果：
![alt text](https://raw.githubusercontent.com/yxw007/BlogPicBed/master/img/1727328918639.png)

## 开通Github Sponsor需要创建Stripe账号

可以参考这个教程来填信息，[Stripe 注册教程、国内注册 Stripe 香港帐号教程！如何注册 Stripe 个人账户？10分钟即可成功注册 Stripe、轻松推特收款｜数字牧民LC](https://www.youtube.com/watch?v=Dl53poAkbZo\&t=411s\&ab_channel=%E6%95%B0%E5%AD%97%E7%89%A7%E6%B0%91LC)

看完这个教程后，我发现我的护照过期了，只能重新办理，需要20个工作日，接下来就继续等待，等护照办好后，再继续填写信息了。

## 继续填写信息，发现我分行在Stripe平台找不到

最终通过给stripe和github提交工单解决，估计之前平台信息没同步，现在信息同步了可以找到我的分行了。这个过程也是漫长的沟通等待

**补充说明**：

- 汇丰银行卡，前3位为分行号，后面才是卡号，所以填写信息的时候要注意，不要填错了。
- 添加账号名称的时候，是填英文名(卡号账号名)，不是中文名。

## 前几天终于审核通过了，收到了这个邮件

![alt text](https://raw.githubusercontent.com/yxw007/BlogPicBed/master/img/1727328919518.png)

## 配置Github Sponsor

![alt text](https://raw.githubusercontent.com/yxw007/BlogPicBed/master/img/1727328920365.png)

![alt text](https://raw.githubusercontent.com/yxw007/BlogPicBed/master/img/1727328921261.png)

## 最后

以上我是经过2个多月把github Sponsor开通的经验，希望能给大家一份参考，避免少走弯路提供一点帮助。希朋友们可以支持一下：关注我、帮我点star、提PR、反馈意见都可以，当然赞助我更好😄，能让我早点实现独立开发者的梦想，感谢大家！🌹

加我微信，拉你入群：开源逐梦之路，一起交流学习，共同探索开源之路！💪
![alt text](https://raw.githubusercontent.com/yxw007/BlogPicBed/master/img/1727328922535.png)
