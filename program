import uiautomator2 as u2  #实现对手机的操作
import time  #实现计时的功能
import random  #实现随机操作
d = u2.connect("")  # 若为有线连接，手机需要插在电脑上。若为通过无线连接，电脑和手机需要在同一个局域网内，并且需要先用有线的方式做过初始化。
print("打开QQ")  #在屏幕上输出“打开QQ”。
d.app_start("com.tencent.mobileqq")  #启动手机QQ。
time.sleep(2)  #休眠2s等待QQ完全启动。
d.click(0.1,0.1)  #点击打卡程序。
d(text="今天还没打卡哦").click()
d(text="立即打卡").click()  #完成打卡。
print("打卡完成")  #在屏幕上输出“打卡完成”。
d.app_stop("com.tencent.mobileqq")  #退出手机QQ。
print("打开支付宝")  #在屏幕上输出“打开支付宝”。
d.app_start("com.eg.android.AlipayGphone")  #打开支付宝。
time.sleep(5)   #休眠5s等待支付宝完全启动。
d(text="蚂蚁森林").click()  #打开蚂蚁森林。
for x in range(150, 1000, 150):
    for y in range(600, 900, 150):
        d.long_click(x + random.randint(10, 20), y + random.randint(10, 20), 0.1)
        time.sleep(1)  #收集能量。
print("已打开蚂蚁森林")  #在屏幕上输出“已打开蚂蚁森林”。
print("已收完")  #在屏幕上输出“已收完”。
d.app_stop("com.eg.android.AlipayGphone")  #退出支付宝。
print("打开微信")  #在屏幕上输出“打开微信”。
d.app_start("com.tencent.mm")  #打开微信。
time.sleep(2)  #休眠2s等待微信完全启动。
d(text="我").click()  #打开“我”的界面
d.click(0.27,0.22)
d.click(0.27,0.22)
time.sleep(5)  #打开状态设置界面
d.click(0.75,0.9)  #m
d.click(0.25,0.75)  #e
d.click(0.75,0.75)  #i
d.click(0.55,0.85)  #h
d.click(0.15,0.8)  #a
d.click(0.8,0.75)  #o
d.click(0.35,0.8)  #d
d.click(0.25,0.75)  #e
d.click(0.55,0.75)  #y
d.click(0.75,0.75)  #i
d.click(0.45,0.75)  #t
d.click(0.75,0.75)  #i
d.click(0.15,0.8)  #a
d.click(0.65,0.9)  #n
d.click(0.15,0.7)  #输入
d(text="就这样").click()
time.sleep(2)  #完成状态的设置
print("设置完成")  #在屏幕上输出“设置完成”
d.app_stop("com.tencent.mm")  #退出微信
