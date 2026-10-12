<h1 align="center">Bootstrap 4 管理界面练习</h1>

<p align="center">使用 HTML、CSS 与 Bootstrap 4 编写的静态多页练习。</p>

<p align="center">
  <img src="https://img.shields.io/badge/%E6%8A%80%E6%9C%AF-Bootstrap%204-7952B3?style=flat-square" alt="技术: Bootstrap 4">
  <img src="https://img.shields.io/badge/%E9%A1%B5%E9%9D%A2-%E9%9D%99%E6%80%81%20HTML-555?style=flat-square" alt="页面: 静态 HTML">
</p>

<p align="center">
  <a href="#快速开始">开始使用</a> ·
  <a href="#页面目录">页面目录</a>
</p>

---

## 项目介绍

这是一个管理系统页面布局作业，包含首页统计卡片、导航与多个业务页面。页面中的数据和操作用于演示，不包含真实登录、数据库或后端服务。

## 快速开始

下载或克隆仓库后，用浏览器打开 `index.html`。样式和脚本保存在仓库中，无需安装 Node.js 或执行构建。

也可以在已安装 Python 3 的电脑上启动静态服务器：

```sh
python3 -m http.server 8000
```

随后访问 [http://localhost:8000](http://localhost:8000)。

## 页面目录

| 页面 | 文件 |
| --- | --- |
| 首页 | [index.html](index.html) |
| 用户中心 | [user.html](user.html) |
| 数据查询 | [search.html](search.html) |
| 数据面板 | [data.html](data.html) |
| 提醒事项 | [tip.html](tip.html) |

## 项目结构

| 位置 | 内容 |
| --- | --- |
| `*.html` | 各页面的结构与示例内容 |
| `css/bootstrap.min.css` | Bootstrap 样式 |
| `css/style.css` | 自定义页面样式 |
| `js/jquery-3.4.1.js` | jQuery |
| `js/bootstrap.min.js` | Bootstrap 交互组件 |

## 使用范围

适合查看和练习多页导航、布局与 Bootstrap 组件。该仓库为历史练习，未进行本轮浏览器兼容性或真实业务功能验收。
