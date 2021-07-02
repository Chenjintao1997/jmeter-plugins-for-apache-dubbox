# Apache JMeter Plugin For DubboX

# NOTE

此工程是从thubbo的[jmeter-plugins-for-apache-dubbo](https://github.com/thubbo/jmeter-plugins-for-apache-dubbo)处fork过来的，在其基础上做了修改已支持DubboX的接口调用，主要解决了在使用jmeter调用dubbox的RPC服务时无法调用成功的痛点；
此工程去除了源项目对于配置中心Config Center的支持，因为dubbox(com.alibaba.dubbo2.8.4)不支持配置中心的功能；

关于该插件如何使用，可查看源插件的使用方式：user guide ([English](https://github.com/dubbo/jmeter-plugins-dubbo/wiki/user-guide), [Chinese](https://github.com/dubbo/jmeter-plugins-dubbo/wiki/%E7%94%A8%E6%88%B7%E6%8C%87%E5%8D%97)) ；
需要注意的是，本项目的jar包名称和源项目文档标注不一样。

# Introduce

DubbOX Plugin for Apache JMeter, Its main purpose is to perform stress testing on the DubboX interface visually in Jmeter. It is easy to use.

# Plugin Version Support

requires Java 1.8

# JMeter Version Support

* [3.0,3.2): requires Java 1.7
* [3.2,4.x,5.x]: requires Java 1.8

ps. [3.x,4,x,5.x] Tested for normal use

