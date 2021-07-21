# HeartBleed漏洞复现

---

## 目录

1. 项目简介
2. 小组成员
3. 项目环境
4. 文件说明
5. 鸣谢

---

## 项目简介
本项目是山东大学网络空间安全学院《网络空间安全创新创业实践》课程的小组项目，对OpenSSL的HeartBleed漏洞进行复现。

## 小组成员
+ 隋松原 2018221211969
+ 王倞 201800140037
+ 赵克松 201800140074
+ 谢韬 201818171264



## 项目环境
### 操作系统
+ Windows 10
+ Ubuntu 12.04

### 编程语言
+ Python 2.7
+ C
+ PHP5

### 虚拟机
+ VMware 16



## 文件说明
### 当前目录：“HeartBleed漏洞复现”
+ HeartBleed项目报告.pdf： HeartBleed小组项目报告
+ HeartBleed展示.pptx： HeartBleed小组项目展示PPT
+ 成员列表.xlsx： 小组成员姓名学号列表
+ README.md： 项目说明
+ 代码： 项目代码文件夹

### 代码目录：“代码”
+ t1_lib(漏洞).c： 存在HeartBleed漏洞的OpenSSL源文件
+ t1_lib(修复).c： 修复HeartBleed漏洞后的OpenSSL源文件
+ login.php： 靶场网站代码
+ attack.py： HeartBleed漏洞攻击代码
+ detect.py： HeartBleed漏洞检测代码




## 鸣谢
### 指导教师
+ 王美琴教授
+ 温隆博士