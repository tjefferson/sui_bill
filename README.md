# sui_bill

## 微信账单到随手记

### 1.获取微信账单
1. 微信-我-设置-帮助与反馈
2. 支付-账户问题-微信支付如何导出账单-点击这里-个人对账下载

### 2.简单处理账单文件
1. 去掉文档前面的描述性字符
2. 将文档编码改为utf-8

### 3.运行Python代码
1. 将wechat_filepath的值更新前面处理好的账单文件地址
2. 执行代码得到wechat_output.xls文件

### 4.导入到随手记
1. 打开web端地址：https://www.sui.com/data/index.jsp
2. 新功能-导入导出-数据导入-随手记web版
3. 选择文件-上传数据

使用的代码参考自：https://blog.csdn.net/luchengtao11/article/details/127340578
