####声明：此程序原作者为CubicPill,发布在Github，感谢原作者的付出！
近来感觉网课这个东西真的是（此处省略一万字），对没兴趣观看的学生完全就是混学分，但是网课平台好像看穿了我们的目的，采取了一系列XXX的操作来阻止我们得到可爱的学分，很烦！怒写插件解决之！
# kick_erya
一个刷尔雅网课的脚本

## 主要功能

- 章节测验页面的解析和提交
- 任务点完成检测
- 验证码检测
- 登陆错误信息提示
##使用说明
###1.程序使用Python编写，使用时需要安装Python环境（以Windows为例，懂得命令行和Python基本命令的小伙伴可略过此部分）
（1）[点击此链接](https://www.python.org/downloads/release/python-365/)到达官网下载Python3.6.5，请根据自己的操作系统选择合适的版本
（2）打开下载的程序根据要求安装，请务必勾选“Add Python 3.6 to Path”复选框（否则需要配置系统Path变量）
![20180414194446247.png](https://upload-images.jianshu.io/upload_images/8056623-68189ee06c5f6889.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
###2. 在[此页面](https://github.com/geek981108/ZhiHuiShu)下载此程序并解压到C盘根目录（照顾小白用户，暂不讲解cd命令）
![屏幕截图(14).png](https://upload-images.jianshu.io/upload_images/8056623-6eebdd46050776b1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
###3.在 ```config_sample.json``` 文件中填入账号和密码, ```init_url``` 填入要刷的课程主页任意一个章节的 网址, 并将文件改名为 ```config.json```
###4.打开命令提示符（快捷键为Win+r），输入命令```cd c:\kick_erya-master```,回车
###5.输入命令```py run.py```即可，如果没有运行，请检查用户名密码是否填写正确，或使用命令```python run.py```来执行
最后祝大家食使用愉快，轻松拿到可爱的学分！同时也建议大家有时间的话还是自己没事的时候看一看这些网课，有些东西还是挺有趣的！
