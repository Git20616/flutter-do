---
title: "一点建议"
description: "给Flutter初学者的一点建议"
type: widgets
---

## 前言

::: tip
迷茫是什么，迷茫就是大事干不了，小事不想干，能力配不上欲望，才华配不上梦想。
:::

我在 Flutter 未正式发布之前就开始学习了，因为`Fuchsia`系统，随着 5G 的发展，物联网将会迎来爆发式的增长，目前的市场上还没有一款物联网系统占据主导地位，虽然 Google 没有说`Fuchsia`是为物联网而生，但你理解`Fuchsia`系统的特性你就会明白此系统非常适合物联网，因此 Flutter 的发展前景不可限量。

在学习 Flutter 的过程中，中文资料非常少，官方的文档比较晦涩难懂，而且没有相关 demo，这就是此网站诞生的初衷，希望能够帮助广大 Flutter 初学者，这里没有高深的技术，有的只是一个个控件的基础用法。

目前已经整理了 180+的组件，而且将相近的组件放在了一起，比如 Button 组件，系统提供了 10 多种 Button 类组件，虽然索引是按照字母排序的，但不管你看哪一个 Button，都可以看到其他 Button 的相关用法。

## Flutter 会不会火？

我收到了很多关于要不要学 Flutter？Flutter 会不会火的问题？说实在我也不知道，任何事物的发展壮大天时地利人和缺一不可，技术本身优势仅仅是最基本的一个方面，我只能说 Flutter 的概率比较大而已，就像你和马云的儿子谁更有希望成为亿万富翁一样，我只能说 Flutter 的发展前景不可限量。

其实很多东西的学习，尽快入坑学习、动手实践远比畏畏缩缩、进度停留了解阶段要好得多，这是一个很简单的道理，可是偏偏很多人不明白或者做不到。如果你可以做到这样，不得不说这也是一种优势。

## Flutter 的使用情况

我知道你一定非常关注目前各个公司使用 Flutter 的情况，尤其头部互联网公司，据我所得到的消息（当然我也在头部互联网公司）目前各大互联网公司的头部 App 基本很少使用，为什么？原因很简单，

1. Flutter 从正式发布至今才 2 年，到底如何谁心里也没底，能不能禁得住市场的考验都是一个未知数。
2. Flutter 目前的包体积居高不下，头部 App 对包体积要求非常严格，都是以 KB 为单位的，即使一个空的 Flutter 项目都好几“MB”。

虽然头部 App 使用很少，但都在内部项目或者次级项目尝试 Flutter。

小公司和个人开发者目前使用 Flutter 技术的非常多，没有进入过跨平台开发的人永远体会不到跨平台开发的便利，跨平台开发的人很难在回到原生开发了，除非你是为了五斗米折腰。

记住跨平台开发是历史趋势，从当初的 H5 到 React Native，在到现在的 Flutter，都是为了解决跨平台开发，提高开发效率，历史的车轮不会停止，即使不是 Flutter，也会出现另一个 Flutter。

## 关于 Flutter 版本

Flutter 发展速度之快超乎你的想象，在查资料的时候注意版本，旧的版本在新的版本可能已经废弃了，尤其在混合开发方面。因此本站所有的文章如无特殊说明，Flutter 版本及 Dart 版本如下：

> - Flutter 版本： 1.12.13+hotfix.5
> - Dart 版本： 2.7.0

## 如何学习 Flutter

本站虽然整理了 150+的控件基本用法，以后也会继续完善，但并不是让你每一个都学习一遍，任何技术基本都是掌握 20%就可以解决 80%的问题，因此我整理了一些常用控件，只需学会这些基础控件就可以上手项目了，至于其他的控件只需大概浏览一下，做项目的时候遇到一些功能能够想起 Flutter 已经提供了此组件就可以了。

关于 Dart 语言，如果你有其他高级语言的基础，比如 Java，可以不用特意去学 Dart 基础，更着别人的代码敲，很快就可以掌握了。

最近也在整理学习 Flutter 的思维导图，等整理好了分享给大家。

## 开发环境建议

俗话说的好“磨刀不误砍柴工”，一款好的 IDE 可以极大的提高开发效率，个人建议使用 mac（系统）+Android Studio。原因如下：

- 既然使用了 Flutter，那么开发的项目应该是移动端 App，Flutter 的打包最终依然是原生的应用程序。
- Flutter 在 Android 上调试的时候会遇到各种编译不通过的问题，这些需要一些 Gradle 的基本知识，因此建议使用 Android Studio，理解基本编译过程。
- Android 编译不过一般是 gradle 版本、support 版本和 androidx 的问题，这些问题在 Android Studio 上更好解决。

平时调试的时候可以使用 Android Studio+IOS 的模拟器进行调试。

开发环境的安装最好按照[Flutter 官网](https://flutter.dev/)的步骤来，网上的介绍很可能版本比较老了。

## 第三方库的使用

在学习阶段建议大家少用第三方库，尤其是一些 UI 库、状态管理和路由管理的库，这里并不是说这些库不好，这些库很好，是大牛的智慧的结晶，如果你没有经过原生的开发，不了解开发的痛点，你永远无法了解这些库带给你的好处，而且如果这些库一直有人维护那还好，一旦没人维护，出了问题那解决起来可能更麻烦。

那是不是都不用第三方库呢？并不是绝对的，比如网络请求库 dio，严格的说这不是 Flutter 的库，而是 Dart 的库，此库已经非常稳定。还有涉及大量原生开发的库，原生开发并不是你关注的重点，这些库是可以用的，但要了解 Flutter 与原生开发的通信机制。

## 吐槽一下

千万不要和别人说 Flutter 的 UI 编写太不好维护了，为什么？因为嵌套啊，我就想问问你你平时一个函数会写 1000 行吗？你写代码不会封装吗？平时的模块化思想都哪去了？不管 H5，还是 Android、IOS 的 UI 开发哪一个不是“树”结构。