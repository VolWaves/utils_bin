# Volwave固件开发工具箱

本项目为 `Volwave` 固件开发工具链的一部分，包含日常开发中需要使用到的二进制文件和脚本。主要用于消除对开发环境的二进制依赖。

## AStyle

直接包含了 `AStyle` 二进制，使得不再需要依赖宿主环境安装 `AStyle`

## KeilUtils

来源：https://github.com/Nigh/Keil_MacroPath

主要用于辅助使用 `Keil IDE` 的开发。这个工具提供了一种自动化的方法来修改 `Keil` 的工程文件，使其能够支持宏路径。

## p2a(picture-to-array)

来源：https://github.com/Nigh/picture-to-array

此工具用于将目录下的图片素材自动批量转换为 C 语言描述的位图形式。

## tcc

来源：https://bellard.org/tcc/

一个轻量高效的 C 编译器，使用它可以像脚本语言一样运行 C 程序，用于在编译工具链中实现仅仅靠 `makefile` 所难以完成的复杂功能。