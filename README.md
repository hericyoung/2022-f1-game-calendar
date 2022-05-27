# 2022 F1 赛程日历订阅

## 日历订阅操作

### iOS

1. 打开 iPhone 或 iPad 上的”日历”APP，点击下方正中的“日历”按钮

![http://img.hericyoung.tech/uPic/IMG_814720220527130056.jpg](http://img.hericyoung.tech/uPic/IMG_814720220527130056.jpg)

1. 点击左下角“添加日历”，选择“添加订阅日历”

![http://img.hericyoung.tech/uPic/20220527130521IMG_8148.jpg](http://img.hericyoung.tech/uPic/20220527130521IMG_8148.jpg)

1. 填写 URL，点击订阅，后面按自己需要修改标题或者其他设置，最后点击添加即可

![http://img.hericyoung.tech/uPic/20220527131118ios-cal-sub.png](http://img.hericyoung.tech/uPic/20220527131118ios-cal-sub.png)

---

### Mac

打开“日历”App，点击左上方“文件”并选择“新建日历订阅

![http://img.hericyoung.tech/uPic/20220527130933mac-cal.png](http://img.hericyoung.tech/uPic/20220527130933mac-cal.png)

![http://img.hericyoung.tech/uPic/20220527130959mac-cal-sub.png](http://img.hericyoung.tech/uPic/20220527130959mac-cal-sub.png)

---

# URL

数据源于

[2022 赛季 F1 赛程介绍](https://zhuanlan.zhihu.com/p/422207010?ivk_sa=1024320u)

然后自己使用快捷指令写了个脚本将文章里面的比赛时间数据简单处理一下并自动生成日历

为了满足不同人群需要，我干脆按照**_练习赛，排位赛和正赛_**拆解了三个日历，可以按需订阅，下面是各个日历的订阅 URL（冲刺赛的放在了正赛里面）

正赛：

```bash
webcal://p208-caldav.icloud.com.cn/published/2/ODA2NjQ0MjQ1NjgwNjY0NL9g_CCGch419HGfmNCDauG_HvsJctdh_yseBE333hDgb2zIakgAsOJkUoSmaUstcucqyZa8ofFZs9_GbJe-1aE
```

排位赛：

```bash
webcal://p208-caldav.icloud.com.cn/published/2/ODA2NjQ0MjQ1NjgwNjY0NL9g_CCGch419HGfmNCDauE7SItiC341Q2k_3fEgXqUh9iFo59CwmxgywPWDfNZR6x_O_DXAR7TGW9upG9m3jMs
```

练习赛：

```bash
webcal://p208-caldav.icloud.com.cn/published/2/ODA2NjQ0MjQ1NjgwNjY0NL9g_CCGch419HGfmNCDauH6iZtSQimgYO540K5N_PWZpJgrBJSrgwkvNR2Px6HZduBqaxDiaK0o0MkQeDLANLM
```
