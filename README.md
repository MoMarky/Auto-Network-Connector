#网络自动重连 -# 
-操作步骤：
1. 打开Parameter.txt，
  第一行输入拨号连接的网络名称，只能以纯英语命名。
  第二行为拨号账号。
  第三行为拨号密码。
  注意三行间以回车间隔，不能有其余符号。
2.运行AutoConnectNet.exe。
  页面上方有两个手动控制按钮，用于测试功能是否正常。
3.若测试后，可以进行网络连接，则保持一直运行即可，软件每一分钟检测一次网络连接情况并进行网络连接。下方文字框显示当前网络的状态。
4.除Parameter.txt外，其余文件不要修改或移动位置。


![para](https://user-images.githubusercontent.com/29699528/124372643-60bf9f80-dcbe-11eb-87ab-1675bc3fd445.png)
![main](https://user-images.githubusercontent.com/29699528/124372655-7a60e700-dcbe-11eb-8852-45777156d8fa.png)

使用MFC编写的，简单的断网自动重连程序，需要事先设定拨号连接的网络名称与密码，之后每一分钟检测一次网络，若断网则自动重连。
