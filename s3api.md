---
layout: page
title: The Data Scientist's Toolbox
permalink: /s3api/
---

## 对请求的认证(AWS Signature Version 4)
同S3的交互要么是认证的，要么是匿名的。本章解释如何使用亚马逊V4版本签名算法对请求进行认证。如果使用SDK则不用阅读本章，因为SDK客户端使用你提供的access key来认证请求。
亚马逊V4签名提供的认证有：

- **验证请求者的身份** 认证请求需要一个签名，签名用你的access key（access key id和secret access key）生成。

- **传输数据保护** 为了防止传输数据被篡改，使用部分关键传输数据进行签名

- **方式重放攻击** 被签名的内容中有一个15分钟过期的时间戳



















## Command Line

- [Working with files in Bash](http://edgarsh.es/ins/working-with-files-in-bash/)

## Git/GitHub

- [Git & GitHub Video Playlist](https://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD) (also available for [download](https://drive.google.com/folderview?id=0BxRfg0msVmAoRlZFQjJ3T3VTOUE&usp=sharing) as mp4 files)
- [A Beginner's Quick Reference Guide for Git Commands](http://www.dataschool.io/git-quick-reference-for-beginners/)
- [Understanding the Relationship Between Git and GitHub](http://www.dataschool.io/github-is-just-dropbox-for-git/)
- [Simple Guide to GitHub Forks](http://www.dataschool.io/simple-guide-to-forks-in-github-and-git/)
- [Github Repo Tutorial How to fork a repo, download it to your local drive and commit changes ](https://www.youtube.com/watch?v=MY94AIplcaU)
- [Configuring RStudio to work with Git / Github - Mac OSX](https://github.com/lgreski/datasciencectacontent/blob/master/markdown/configureRStudioGitOSXVersion.md)
- [Configuring RStudio to work with Git / Github - Windows](https://github.com/lgreski/datasciencectacontent/blob/master/markdown/configureRStudioGitWindowsVersion.md)

## Comprehensive Notes

- Complete notes for [The Data Scientist's Toolbox](http://sux13.github.io/DataScienceSpCourseNotes/)

## Miscellaneous
- [Using Editor Modes in Coursera Discussion Forum Posts](https://github.com/lgreski/datasciencectacontent/blob/master/markdown/usingMarkdownInForumPosts.md)