# Apache_Penetration_Tool
使用QT C++开发的一款漏洞利用工具，漏洞详情分析请见：https://www.hui-blog.cool/posts/de1f.html
<br>

# [中文说明](#readme)
# [English description](#[readme-en](https://github.com/wangfly-me/Apache_Penetration_Tool/blob/main/README.md))

## 工具界面
在漏洞选择编号处，选择需要检测的漏洞。
![1.png](https://github.com/wangfly-me/Apache_Penetration_Tool/blob/main/images/1.png)

## 漏洞检测
在第一个文本栏中填写目标url或者ip，带上http或者https，结果会在最后一个大的文本框中显示出来。
![2.png](https://github.com/wangfly-me/Apache_Penetration_Tool/blob/main/images/2.png)

## 目录遍历
在第二个文本栏中填写需要被读取的文件绝对路径，结果会在最后一个大的文本框中显示出来。
![3.png](https://github.com/wangfly-me/Apache_Penetration_Tool/blob/main/images/3.png)

## 命令执行
在第三个文本栏中填入需要被执行的命令，结果会在最后一个大的文本框中显示出来。
![4.png](https://github.com/wangfly-me/Apache_Penetration_Tool/blob/main/images/4.png)

## 反弹shell
先使用nc开启监听，然后填入ip和端口，即可完成反弹。
![5.png](https://github.com/wangfly-me/Apache_Penetration_Tool/blob/main/images/5.png)
