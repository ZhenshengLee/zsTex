# VSCode使用Latex

## 参考

>[CMakeUserUseLATEX](https://cmake.org/Wiki/CMakeUserUseLATEX )

## 安装

### windows

* 下载TexLive-2016.iso

* install-tl-windows.bat

### Ubuntu

```shell
sudo apt-get install texlive-full latex-beamer
```

## VSCode配置

### 安装VSCode插件

```shell
LaTeX Language Support
LateX Preview
```

### 设置

```shell
"latex-preview.command": "xelatex"
```