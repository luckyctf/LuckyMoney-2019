# LuckyMoney-2019

为了给春节找点乐子，做个CTF发点小红包。

为了红包能送出去嘛。。。难度不会特别难。。。仔细看看一定能有点收获 (●—●)

## 我要怎样才能拿到红包 [活动已结束]

四处看看，也许还需要做点奇怪操作，在某个地方你会找到一串类似 f<!-- lag{He1e_ls_a_flag} -->lag{123456} 的东西。

把这串东西发给我，那么我就会给你发个红包。

PS: 别人发给你的flag不算数哟~我会问你怎么做到的 (。ゝω・。)☆

**答案已经放在 writeup 目录下了**

## 题目清单

在这里先放出各flag括号内对应内容的SHA256值。

**题目总数：** 6

| 序号        | 路径    |  难度  | 红包数| SHA256 |
| :--------: | :-----  | :----:  | :----: | :----: |
| 1          | ??? |   ★     | 5/5|662728464e1f44c4432ad783b8f96525e8ab5c3f467167ec7cf591d97ffa2044|
| 2          | ??? |   ★☆   | 3/5|c9ee4a08a2cc820a43f3cb85f2650cd43a318bb9a39e028325c288e93bd7dfac|
| 3          |  ./problems/History.zip  |  ★★  |9/10|4774b2fbb4d35ac57a66f5c8cfe47e29f7911210544b6d76f729219b5ccb5b0a |
| 4          |  ./problems/Cat_Git.zip  |  ★★☆  |10/10| 52192ee39c35d7836cb73c50c8a5caccb2213e35c9ebc9571c04412a9f05387a |
| 5          |  ./problems/History.zip  |  ★★★☆  |19/20|152c8a8b1bbb2ef459dc241ce90aebd99bf4cab678734598bfe9f2ed21bc9f1f |
| 6          |  ./problems/js.js  |  ★★★★★  |∞|ff04ab4669705c43aed40019195524d056e1b77d404c269c2dce9fcff49e0a79 |

技艺不精，还请大佬轻虐。

也许有用的工具箱 https://gchq.github.io/CyberChef/

部分题目来自 https://github.com/djsb2019/LuckyBag 

## 一点点提示

#1 这个flag可以在源文件里找到

#2 这个flag淹没在历史的长河里

#3 这个flag是解压密码经过某种变换后的结果

   找规律：
   
   base64encode("flag{")="ZmxhZ3s="
   
   base64encode("flag{1")="ZmxhZ3sx"
   
   base64encode("flag{A")="ZmxhZ3tB"
   
   base64encode("flag{test")="ZmxhZ3t0ZXN0"

#4 这个flag需要你用点办法checkout

   要！要！切克闹！

#5 图片里隐藏了额外的图片内容

   神仙PK之后，压缩包坏了一半，图片变成了小矮人。

#6 有个提示以另外一种格式藏在 #5 的图片里

   是谁混用空格和TAB的？！
   
   洋葱牌SSTV传送中


