# python # tkinter
大一下写的期末大作业，蛮一般的，发布给自己做个纪念
  这是一段由python的tkinter模块来模拟QQ登录的代码，包括未登录和已登录两个窗口。
  首先，未登录窗口主要是“输入账号和密码及登录按钮”，输入的账号必须符合QQ账号规范，即5-11位的纯数字，输入的密码必须包含字母和数字，
无论账号和密码为空或格式错误都会有错误提醒框，若都符合规范，则进入已登录状态，且账号会不重复地加入账号列表框，退出登录仍保留账号，但退
出程序账号会消失。 未登录窗口还有三个小按钮，但暂未做出相应的功能。
  其次，已登录窗口由五个Frame和一个菜单栏组成，用于模拟QQ内部，菜单栏中的退出是可用的，其余操作暂时只是摆设，都以网络不佳为由产生错
误。
  本代码所写窗口较为简单，但其中值得一提的是，tkinter的布局比较繁琐，花费的时间较多，并且有一定的局限，如多行文本可有滚动条，但大量按
钮却无滚动条的属性，需要自己使用canvas制作。由于个人的审美不太优秀，这两个窗口都没有进行大量的颜色处理。
