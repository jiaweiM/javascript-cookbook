# 概述
JavaScript 是为HTML和Web设计的编程语言。

Web 开发者必须会的三种语言有：
- HTML 用于定义网页内容
- CSS 用于定义网页布局
- JavaScript 用于定义网页行为

最初创建 _JavaScript_ 是为了让网页动起来。以该语言编写的程序称为脚本（_script_）。可以直接在网页HTML中编写脚本，在载入页面时自动运行。

脚本程序以纯文本的形式保存和运行，不需要预编译。所以JavaScript 和 Java 是两种完全不同的语言，不管是从概念还是设计上。

现在，JavaScript 不仅可以在浏览器上运行，还可以在服务器上运行，或者说，可以在任何配置有 JavaScript 引擎的设备上运行。

引擎工作的基本原理为：
1. 读取脚本
2. 将脚本转换为机器语言
3. 运行机器语言

浏览器内置的 JavaScript 引擎称为“JavaScript 虚拟机”（JavaScript virtual machine）。

不同的引擎具有不同的名称，例如：

| 引擎         | 支持浏览器      |
|:-------------|:---------------|
| V8           | Chrome, Opera  |
| SpiderMonkey | Firefox        |
| ChakraCore   | Microsoft Edge |
| Nitro        | Safari         |

引擎会对脚本的每个阶段进行优化，甚至可以在运行时监视编译的脚本，分析数据流并根据这些对机器码进行优化，从而提升脚本的执行速度。

# JavaScript 功能

## 浏览器中的 JavaScript


### 修改 HTML 内容
`getElementById()` 是JavaScript 常用的一个方法，用于找到指定id的HTML元素。

下面首先获得 `id="demo"` 的元素，然后修改元素内容（`innerHTML`）为 "Hello JavaScript":
```javascript
document.getElementById("demo").innerHTML = "Hello JavaScript";
```

### 修改 HTML 属性


# IDE
一个好的IDE可以让编程过程更为顺畅。

用于 JavaScript 开发的常用IDE有：
- WebStorm
- Netbeans
- Visual Studio Code
