# calculator

![GitHub stars](https://img.shields.io/github/stars/Xu-guangyun/calculator) 

## 简介

本程序使用Java语言，JDK-21编写。用于简单的多项式计算，支持加，减，乘，除。

## 技术依赖

1.开发环境：Eclipse IDE for Java Developers 2024-12（用于代码编写、调试及项目构建）

2.运行环境：JDK 21（提供Java编译、运行支持，生成兼容的class文件）

3.基础依赖：Java SE 21 API（JDK自带核心类库，支撑程序基础功能实现）

## 使用步骤

1.首先要下载jre以配置程序运行所需环境，可从以下网址下载，注意jre版本及兼容性，如windows系统64位处理器可以下载jdk-21.0.8+9-jre。

感谢eclipse-temurin-bot的分享，https://github.com/adoptium/temurin21-binaries/releases/latest

2.接下来开始配置环境，将jre压缩包解压得到jre文件夹剪切到合适位置，复制路径。打开环境变量设置窗口：右键点击“此电脑”，选择“属性”，然后点击“高级系统设置”，在弹出的窗口中点击“环境变量”按钮。配置JAVA_HOME变量：在“系统变量”区域中，点击“新建”按钮。变量名输入 JAVA_HOME ，变量值输入此前复制的路径，如 C:\Program Files\Java\jdk-21.0.8+9-jre ，点击“确定”，配置环境完成。

3.下载本仓库的压缩包，并解压，找到calcultor.exe，即可运行。

## 功能介绍

1.本程序支持多项式的加，减，乘，除运算，能处理小数，无限小数结果保留5位小数，暂时不支持包含负数的运算。

2.使用指南：用鼠标点击按钮可输入数字，运算符，当点击“=”时，会显示结果，若输入不合法则显示“Error”，当点击“C”时，会清空显示框。

## 开源协议

本项目采用 MIT License，详细许可条款请见 LICENSE 文件。


