# OpenSSL中heartbleed漏洞复现
## 1、代码层面对比
分别下载漏洞版本的openssl源码（v1.0.1）和补丁版本的openssl源码vv（v1.0.1g），找到heartbleed漏洞出现的地方。从代码层面分析漏洞。
## 2、测试漏洞
#### 1、自行搭建网站服务器。
#### 2、利用公开的工具测试该漏洞，比较未修补与已修补版本的测试结果。
#### 3、测试完成后，对漏洞版本进行源码修补，重新编译测试，比较测试结果。
## 3、自行开发漏洞检测工具并测试
自行制作一个漏洞检测工具，再次测试，并与公开的工具比较性能。
