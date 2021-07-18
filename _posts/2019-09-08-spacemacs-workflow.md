---
layout: post
title: "八股文之"
subtitle: '操作系统'
author: "Hux"
header-style: text
tags:
  - Vim
  - Emacs
---

Emacs tend to provide a good support for functional programming languages. Indeed, many FP language community exclusively use Emacs and give only first-party IDE supports to Emacs, such as Coq, Agda, Standard ML, Clojure, etc.

For the purpose of programming Coq with Proof General, I started to try with Emacs. I quickly found Spacemacs a good alternatives for me...someone had get used to Vim keybindings and want to get some thing useful ASAP w/o configuring a long list as my `.vimrc`.

Though the overall experience is pretty smooth, many quirks about Spacemacs are always being forgotten and had to look up again and again, so I decided to open a note for some specific "workflow" that I often used.

Yes this is more like a note publishing online for the purpose of "on-demand accessible". So don't expect good writing anyways.


### 系统概述

#### 概念和特点

<video id="video" controls="" preload="none" poster="http://om2bks7xs.bkt.clouddn.com/2017-08-26-Markdown-Advance-Video.jpg">
<source id="mp4" src="../media/02.概念和特点.mp4" type="video/mp4">
</video>

#### 功能

#### 剩余内容


### 进程管理

#### 进程的引入

#### 进程的控制

#### 线程

#### 处理机调度

#### 同步与互斥1

#### 同步与互斥2

#### 同步与互斥3

#### 同步与互斥4

### 内存管理

#### 连续分配管理方式1

#### 连续分配管理方式2

#### 非连续分配管理方式1

#### 非连续分配管理方式2

#### 虚拟内存管理1

#### 虚拟内存管理2


### 文件管理

#### 文件管理基础

#### 文件逻辑结构

#### 目录管理

#### 外存分配

#### 文件存储空间


### IO输入/输出管理

#### IO管理概述1

#### IO管理概述2

#### IO核心子系统1

#### IO核心子系统2

#### IO核心子系统3

I tend to open multiple _workspace_. Though people might found Vim tabs useful, I am exclusively use iTerm tabs for similar jobs. However Spacemacs is not living in a terminal.

[r/spacemacs - Vim-style tabs?](https://www.reddit.com/r/spacemacs/comments/5w5d2s/vimstyle_tabs/) gave me a good way to approximate the experience by using [Spacemacs Workspaces](http://spacemacs.org/doc/DOCUMENTATION.html#workspaces): `SPC l w <nth>` trigger a so-called "layout transient state" (I have no idea what's that mean) to open N-th workspaces, and use `gt`/`gT` to switch between.


### Fuzz File Name Search / Rg

`SPC f f`


### Buffers

`SPC b b`







