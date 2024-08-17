# 程序设计实践（2024 夏季学期）

> 北京航空航天大学软件学院 2024 年夏季学期《程序设计实践》课程仓库

---

# 一、往年仓库

大家可以参考往年仓库中的资料，提问时也可以先检索往年的 Issue。😊

> - [2023](https://github.com/BUAA-Soft-2023-Summer/Soft-Summer-2023)
> - [2022](https://github.com/buaa-soft-summer/soft-summer-2022)
> - [2021](https://github.com/soft-summer-2021/summer2021)
> - [2020](https://github.com/buaa21/summer2020)

---

# 二、教师和助教信息

## 2.1 教师

| 姓名   | GitHub 昵称                                                  |
| :----- | :----------------------------------------------------------- |
| 黄坚   | [huangjianbuaa](https://github.com/orgs/BUAA-Soft-2023-Summer/people/huangjianbuaa) |
| 宋友   | [songyou21](https://github.com/songyou21)                    |
| 路新喜 | [laneseal](https://github.com/laneseal)                      |
| 周号益 | [Haoyi](https://github.com/orgs/BUAA-Soft-2023-Summer/people/zhouhaoyi) |

## 2.2 助教

| 姓名   | GitHub 昵称                                     | 擅长领域                                                     |
| :----- | :---------------------------------------------- | ------------------------------------------------------------ |
| 柳政尧 | [Lord Turmoil](https://github.com/Lord-Turmoil) | C++ 游戏开发（EasyX）；Windows 桌面应用（WPF）；各种前后端框架 |
| 聂睿   | [Abyss](https://github.com/Abyss7893)           | Java 游戏开发；Web 后端开发                                  |
| 朱玉林 | [Ferpakenameyea](https://github.com/Ferpakenameyea) | Unity 游戏开发                                             |
| 陈超 | [ccLoopy](https://github.com/cc1121) | web前后端开发                                             |
| 陈博胆 | [guolala](https://github.com/guolalala) | Python人工智能                                             |

---

# 三、通知（持续更新）

*To be continued...*

---

# 四、开发指引

## 4.1 桌面应用程序

**Windows**

Windows API (C/C++)：原生 Windows 桌面应用开发，较为繁琐。可结合 [EasyX](https://easyx.cn/) 进行开发。

WinForm (C#)：WinForm 是最简单、最傻瓜式的创建 Windows 桌面程序的方法。只需要拖控件、写代码，就可以完成想要的功能，具体可参考 [WinForm 指引](https://github.com/buaa-soft-summer/soft-summer-2022/blob/main/starter-winform.md)。

WPF (C#)：最现代化的 Windows 桌面开发，结合 [.NET MAUI](https://dotnet.microsoft.com/en-us/apps/maui) 也可以实现跨平台应用开发。教程可参考 [WPF项目实战合集(2022终结版)](https://www.bilibili.com/video/BV1nY411a7T8)。

**macOS**

Swift + SwiftUI：[macOS 指引](https://github.com/buaa-soft-summer/soft-summer-2022/blob/main/starter-macos.md)

**跨平台**

[Qt](https://www.qt.io/) (C++)：跨平台 UI 框架。[Qt 指引](https://github.com/buaa-soft-summer/soft-summer-2022/blob/main/starter-qt.md)

[Electron](https://www.electronjs.org/)（HTML + CSS + JavaScript）：用前端技术构建跨平台桌面客户端。

Swing (Java)：跨平台 UI 框架，有 Java 基础的同学可以尝试。

## 4.2 游戏开发

> 不推荐编写控制台游戏。🥺

[EasyX](https://easyx.cn/) (C++)：简单，易上手，是 Windows GDI 的封装。[EasyX 指引](https://github.com/BUAA-Soft-2024-Summer/Soft-Summer-2024/tree/main/C%2B%2B%20EasyX)，[2048 Demo](https://github.com/BUAA-Soft-2024-Summer/2048)

[pygame](https://www.pygame.org/) (Python)：简单易上手的 Python 游戏开发模块。

Unity (C#) / Unreal (C++)：成熟的游戏引擎。

## 4.3 Web 开发

前端开发框架：[Vue](https://vuejs.org/)，[React](https://react.dev/)

后端开发框架：[Django (Python)](https://www.djangoproject.com/)，[Spring Boot (Java)](https://spring.io/)，[ASP.NET Core (C#)](https://dotnet.microsoft.com/en-us/apps/aspnet)

## 4.4 移动应用开发

Android

iOS：使用 Swift 语言、SwiftUI 框架开发 APP

微信小程序

## 4.5 插件开发

主流的 IDE 和很多基于 Electron 的应用都支持社区插件，因此开发插件也是不错的选择。大家平常使用的 Visual Studio Code 就支持丰富的插件，笔记软件 Obsidian 也支持自定义插件。具体可以参考[插件开发指引](https://github.com/BUAA-Soft-2024-Summer/Soft-Summer-2024/tree/main/Extension)。

---

祝大家开发顺利！🎉
