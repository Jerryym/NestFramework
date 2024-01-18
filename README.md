# Nest Framework

Nest Framework是一个基于Qt6.5.3版本的通用软件开发框架。此项目是一个学习项目，目的是熟悉Qt相关特性和软件开发。

## Environment

* **IDE**: Visual Studio 2019、Visual Studio 2022
* **Qt Version**: Qt6.5.3

## Modules

* Nest：此项目为框架核心，是一个 `.lib`项目。内部包含应用程序类、基于[spdlog](https://github.com/gabime/spdlog)库封装的日志模块。
* NestUI：此项目为框架UI库，是一个 `.dll`项目。内部包含MainWindow（纯虚类）、DockWidget（纯虚类）、DockWidgetManager（DockWidget窗口管理类）。

## Dependencies

本项目用到以下开源库

* [Qt6](https://www.qt.io/)
* [spdlog](https://github.com/gabime/spdlog) - C++ logging library.
