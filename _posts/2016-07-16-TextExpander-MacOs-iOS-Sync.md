---
layout: post
title:      "TextExpander 如何在  MacOS 和 iOS 上实现同步？"
categories: [系统]
tags:       [工具, Mac, iPhone]
mathjax:    false
date:       2016-07-16 15:14:54
author:     "Helen Li"
header-img: "https://cdn.rawgit.com/BruceZhaoR/brucezhaor.github.io/master/img/post/..."
#bg-color: "linear-gradient(56deg, #155799, #159978)"
description: "从2015年8月20日至今， TextExpander 让我少敲了 29,971 个字符。"
---

* content
{:toc}

> 从2015年8月20日至今， TextExpander 让我少敲了 29,971 个字符。

### 一、关于 TextExpander
在我看来，TextExpander 绝对是 Mac 上的必备利器。它符合「简约」和「系统」的基本原则：**如果一个任务需要重复执行，那么就该让它自动化**。

从2015年8月开始试用 TextExpander，历程和使用其它工具类似。刚开始只是简单使用，只是觉得有些方便而已。直到今年5月，认真地研读了1个教程，调整了使用方法，才算领略到它的不可替代。

如果在过去11个月里， TextExpander 一共让我少敲了29,971个字符，可能有15, 000 个字符是最近3个月省下的。 这也应证了另一个原则：**但凡好工具，如果肯花功夫用顺手，肯定事半功倍**。

譬如写这篇文章，我先把 Post 开头的几行设置，在 TextExpander 中建立了一个 snippet。新建文档时，只需键入 「xjpost」6个字符，这几行设置瞬间优美地呈现在屏幕上。

### 二、本文目的

正是因为尝到了甜头，我希望在手机上使用 TextExpander，而且可以调用已经在 Mac 上已经建立的系统，不必重新设立。

顺带提一句：TextExpander 6 新出了「订阅」模式，月付，可以自动完成跨平台的同步。 我已经购买过上一版，自己动手，一劳永逸。

### 三、场景假设：
在 MacOS 上的 TextExpander 中，已经建立了 snippet，在iPhone上新装了 TextExpander Touch，需要把 Mac 上已经建立的系统，同步到手机上。（如果你是第一次使用TextExpander，先设置哪台设备都没有关系。）

### 四、在 Mac 上设置  TextExpander 
1. 打开 TextExpander 的 Preference 设置
2. 选择 Sync 标签
3. 选择 Save Snippets As.. 
![MacOS](http://image.helenysli.top/TextExpander1.png)
4. 选择云端存放文件夹，确定。（目前支持 iCloud 和 Dropbox 两种存储方式，我选择的是 Dropbox ）
![Dropbox](http://image.helenysli.top/TextExpander2.png)

### 五、在 iPhone 上设置 TextExpander 
1. 打开App，点击左下方齿轮状图标，进入设置页面。
2. 下拉屏幕到「SYNCHRONIZATION」部分，点击 Sync Snippets 进入。
3. 在「Dropbox」一栏，选择「Link to Dropbox Snippets..」
4. 进入 Dropbox 存放 TextExpander 的文件夹，选择前面存储的设置文件。确认后，会显示 「Downloading...」提示。

### 六、在 iPhone 上设置 Keyboard  
这一步设置主要是因为 iPhone 上其它键盘不一定支持 TextExpander。

1. 下载完成后，回到 iPhone 主页面，进入 Setting --> General --> Keyboard。
2. 点击 Keyboards，选择「Add New Keyboard...」，选择 TextExpander，语言选择「English」。
3. 回到 Keyboards 界面，可以看到 TextExpander 键盘已经添加好。点击进入，选择 「Allow Full Access」。

至此，TextExpander 就可以在 Mac 和 iPhone 直接同步了。你可以用同样的方法，建立其它设备之间的同步。 现在就可以愉快地使用 TextExpander 了。

### 七、注：
- 完成设置后，无论你在哪台设备上编辑 snippet，都可以迅速跨平台同步。
- 不要把「Sync 同步」和 「Backup 备份」视为一谈。 
- 我日常英文输入使用 Swype 键盘，这样一来，就有了 Swype 和 TextExpander 两个英文键盘。但使用下来，不觉干扰，主要原因是Swype 键盘「智能猜测」功能已经很强大，所以TextExpander 使用场景主要是「模板」类，并不需要频繁切换。
-  中文输入状态下，同样需要切换，关键是找到自己的工作流节奏。

### 八、Reference：
- [TextExpander 5 - Working with TextExpander touch - YouTube](https://www.youtube.com/watch?v=MJzJNxbQ8uE)
- [TextExpander touch 3.5 - TextExpander touch Basics - YouTube](https://www.youtube.com/watch?v=5XCXHbsm_54)




