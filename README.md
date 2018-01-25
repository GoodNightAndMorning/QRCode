# QRCode
二维码生成、识别、扫描
SXQRMethods类封装了二维码生成、识别、扫描的方法
ViewController有二维码生成、识别、扫描的用例
注意：
1、调用扫描接口需要实例化SXQRMethods类，并设置为全局变量包活，否则代理方法不会执行
