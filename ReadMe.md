[English](#English) | [简体中文](#Chinese)

# <div id="English">Windows Terminal Context Menu</div>
This software is licensed under MIT licence.

## 1.Introducing

This software can automatically generate and open the right-click menu of Windows Terminal here.

The script can automatically recognize the system language.
- Currently supported languages: see [translations file](./lang.ini).

## 2.Install/Uninstall

Note: These scripts require [PowerShell](https://github.com/PowerShell/PowerShell) (version at least 5, generally built-in).
- To install: run install.ps1
- To uninstall: run uninstall.ps1

## 3.Thanks

This project is based on lextm's ["windowsterminal shell" project](https://github.com/lextm/windowsterminal-shell).
Special thanks to lextm.

## 4.Compare with "windowsterminal shell"
| | Windows Terminal Context Menu | windowsterminal shell |
| :- | :-: | :-: |
| Support multiple languages | Yes | No |
| Support Windows Terminal Preview | Yes | Yes |
| Support PowerShell 5 | No (messy code) | No (cannot run) |
| Compatible with multiple Windows Terminal versions | Unknown | Version at least 0.11 |
| Check environments | Yes | Yes |
| Installation message | Have | Have |
| Administrator privileges | Not required | Required |
| Whether to Require to retain this folder files after installation | Required (retain [launch.vbs](./launch.vbs)) | Not required |
| Multiple styles | Not have | Have |
| Sort menus in the order of settings | Yes | No |

## 5.Known problems
* After you ran install.ps1, some icons may not display. Just run install.ps1 again.

---

# <div id="Chinese">Windows Terminal上下文菜单</div>
此软件遵循麻省理工学院许可证（MIT）。

## 1.介绍

本软件可在此自动生成在此处打开Windows Terminal的右键菜单。

脚本可以自动识别系统语言。
- 当前支持的语言：请查看[翻译文件](./lang.ini)。

## 2.安装/卸载

注意：这些脚本需要[PowerShell](https://github.com/PowerShell/PowerShell) （版本至少为5，通常是内置的）。
- 安装：运行install.ps1
- 卸载：运行uninstall.ps1

## 3.感谢

此项目基于lextm的[“windowsterminal shell”项目](https://github.com/lextm/windowsterminal-shell)。
特别感谢lextm。

## 4.与"windowsterminal shell"比较
| | Windows Terminal Context Menu | windowsterminal shell |
| :- | :-: | :-: |
| 支持多种语言 | 是 | 否 |
| 支持Windows Terminal预览版 | 是 | 是 |
| 支持PowerShell 5 | 否（乱码） | 否（不能执行） |
| 兼容多个Windows Terminal版本 | 未知 | 版本至少为0.11 |
| 检查环境 | 是 | 是 |
| 安装信息 | 有 | 有 |
| 管理员权限 | 不需要 | 需要 |
| 安装后是否需要保留此文件夹的文件 | 需要（保留[launch.vbs](./launch.vbs)） | 不需要 |
| 多种样式 | 无 | 有 |
| 按设置的顺序排序菜单 | 是 | 否 |

## 5.已知问题
* 运行install.ps1后，有的图标可能无法显示，再次运行install.ps1即可。
