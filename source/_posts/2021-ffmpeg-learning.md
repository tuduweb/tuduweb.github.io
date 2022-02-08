---
title: 2021-ffmpeg-learning
tags: FFmpeg
abbrlink: 11816
date: 2021-03-07 15:54:35
---

## FFMPEG的安装、配置

在网上找的大多数在win10下配置ffmpeg环境的方法已经过期，因为https://ffmpeg.zeranoe.com/builds/ 网站已经无法打开。经过实际测试，发现在 https://www.gyan.dev/ffmpeg/builds/ 网站下，下载ffmpeg-release-full-shared.7z版本，解压后使用目录下的./bin/，./lib/，./include/亦可。

下载完成解压后，把./bin目录添加到系统环境变量里，在cmd界面下键入`ffmpeg -v`，如果有显示那么配置成功。