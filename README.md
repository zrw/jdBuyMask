****
如果帮助到你，star一下，谢谢你

武汉加油，中国加油
****
使用方法 ： https://blog.csdn.net/cyz52/article/details/104239558
## exe版本[口罩小助手] 最多添加99种口罩
链接：https://pan.baidu.com/s/1bgGXsH071GkHWGlLIwgRVw 
提取码：do3f 
复制这段内容后打开百度网盘手机App，操作更方便哦

代码暂不更新了。
祝大家早点买到口罩


![image](https://github.com/cycz/jdBuyMask/blob/master/pic/1581486475(1).jpg)
![image](https://github.com/cycz/jdBuyMask/blob/master/pic/1581486486(1).jpg)

避免抢购，程序自动一次只买一件 
## V2版本
请在configDemo.ini 加入商品id、地区id、cookie等参数
区分下单模式（默认2正常模式） 

**注意--极速模式默认清空购物车**

正常模式下单流程（1.7秒左右）
- [x] 检测有货
- [x] 检测下柜
- [x] 加入购物车
- [x] 查看购物车
- [x] 下单

极速模式下单流程（1.4秒左右）
- [x] 检测有货
- [x] 加入购物车
- [x] 下单

## V3版本（下单更快）

下单更快，但只能扫描单独一件商品

在配置文件configDemo.ini中，填写[V3]下面的skuid

**注意--V3版本默认清空购物车**

V3版本下单流程（1秒左右）
- [x] 提前加入购物车
- [x] 检测有货
- [x] 下单

## exe版本
进群要吧，地址随时变，就不放了。


## 温馨提示
- 在京东购物车结算页面设置发票为电子普通发票-个人设置支付方式为在线支付
- 地区id不知道如何获取的，请使用AreaTool.py获取
## 版本
- [x] python3


## 功能
- [x] 检查登录
- [x] 确认是否有货
- [x] 有货自动下单
- [x] 邮件、微信通知

## 更新记录
- 【2020.02.12】更新exe版本，代码暂不更新了。
- 【2020.02.10】每10分钟自动读取一次配置修改商品不需要退出重开，优化有货，不支持省份出售情况，优化日志，加快查询频率。
- 【2020.02.09】部分下单需要验证码识别问题，部分bug优化。
- 【2020.02.08】V2版本，区分下单模式，config中错别字，bug修复。
- 【2020.02.07】V3版本，减少提交订单的请求量，总而言之就是更快（只能监控一件商品）。
- 【2020.02.07】无货等情况下单失败不重试。
- 【2020.02.07】新增微信通知（http://sc.ftqq.com/3.version 查看sc_key），bug修复。
- 【2020.02.06】V2版本，刷新更快更频繁，通过配置文件添加商品和地区id。
- 【2020.02.06】提交失败之后会继续不会暂停。
- 【2020.02.06】购物车有套装商品导致解析skuid错误。
- 【2020.02.05】商品有货，但是该商品已下柜，提交会报错，对部分代码进行了优化。
## 反馈问题

- 如果有红包先花掉再开脚本，不然可能需要支付密码
- 出现下单地址不是默认地址的，在线下一单，取getOrderInfo.action链接的cookie
- CMD界面卡住、关闭CMD的快速编辑模式就行了