<a name="top"></a>
# Design

[⬅︎ 返回上层](../#design)

## TOC

<!-- MarkdownTOC GFM -->

- [设计工具](#设计工具)
- [Sketch](#sketch)
    - [工作流 (Workflow)](#工作流-workflow)
    - [Typography](#typography)
    - [定位](#定位)
    - [布局](#布局)
    - [标注](#标注)
    - [交互](#交互)
    - [预览](#预览)
    - [版本控制](#版本控制)
    - [Sketch UI Toolkit](#sketch-ui-toolkit)
    - [组件化设计](#组件化设计)
    - [样式](#样式)
    - [伪数据填充](#伪数据填充)
    - [其他插件](#其他插件)
- [原型设计](#原型设计)

<!-- /MarkdownTOC -->


## 设计工具

- [Skala](https://bjango.com/mac/skala/): 「待评价」bjango 出品


## [Sketch](https://www.sketchapp.com)

- [Sketch Tool](https://www.sketchapp.com/tool): Sketch 自带的命令行工具

### 工作流 (Workflow)

- [Sketch Runner](http://sketchrunner.com/): 最棒的插件管理器+工作流工具，sketch 必装
  - [Sketchpacks](https://sketchpacks.com/): 另一款插件管理器
- [craft](https://www.invisionapp.com/craft) Invision 出品
- [Zeplin](https://zeplin.io/): 业界最好的团队协作、标注、工作流 SaaS。商业用，开源替代品见 [Marketch](#Marketch)
  - [Avocode](https://avocode.com/): 「待评价」
  - [Sympli](https://sympli.io/): 「待评价」

### Typography

- [Font Packer](https://github.com/bigxixi/font-packer): 轻松打包文档中用到的字体
- [sketch-iconfont](https://github.com/keremciu/sketch-iconfont): 「待定」集成 iconfont。有点卡，不太好用
- [sketch-text-tools](https://github.com/automat/sketch-text-tools): 文字排版插件

### 定位

- [Sketch Search Everywhere](https://github.com/mrpeak/sketch-search-everywhere): 超强的搜索定位工具
- [Font Finder](https://github.com/ukn530/fontfinder): 根据字体选定图层

### 布局

- [AlignTo](https://github.com/lucienlee/alignto): 很便捷的对齐工具
- [butter-sketch-plugin](https://github.com/pberrecloth/butter-sketch-plugin): 垂直/水平重排工具，元素间排除间隔
  - [SketchDistributor](https://github.com/pez/sketchdistributor): 垂直/水平重排工具，元素间指定间隔
- [Symbol Organizer](https://github.com/sonburn/symbol-organizer): 自动重排 Symbol 页
- [Sketch Flex Layout](https://github.com/hrescak/Sketch-Flex-Layout): 根据 CSS 文本排布元素
- [fluid](https://github.com/matt-curtis/fluid-for-sketch): 响应式布局工具，比 Sketch 自带的 Resizing 提供更高级的定制
- [compo](https://github.com/romashamin/compo-sketch): `⌘J` 快速对齐文本
  - [我的 Fork，增加了中间和垂直对齐](https://github.com/adoyle-h/compo-sketch/tree/feature/align-vertical-and-horizontal)
- [Smartboards](https://github.com/elihorne/smartboards): 自动重排 Artboards 的布局，很人性化

### 标注

- Sketch Notebook
  - [商业版](https://marcosvid.al/sketch-notebook/)，功能强大
  - [开源版](https://github.com/marcosvidal/Sketch-Notebook)，早就不维护了，功能还行
- [Sketch Guides](https://github.com/luvmex/sketch-guides): 设置对齐线的辅助工具

### 交互

- [userflows](https://github.com/abynim/userflows): 当前相对较好的插件，但依然不太好用
- [protowire](https://protowire.com/): 「待评价」交互设计 sketch 插件

### 预览

<a name="Marketch"></a>
- [Marketch](https://github.com/tudou527/marketch): 生成 HTML 文档，同时也是标注工具。开源的
- [Sketch Measure](https://github.com/utom/sketch-measure): 跟 Marketch 类似功能，设计得比较出色
- [Sketch Preview](https://github.com/marcisme/sketch-preview): 「待评价」基于 [Skala Preview]() 的 sketch 插件

### 版本控制

- [Abstract](https://www.goabstract.com/): 目前最好的版本控制服务
- [kactus](https://kactus.io/)
  - [源代码](https://github.com/kactus-io/kactus)
- [git-sketch-plugin](https://github.com/mathieudutour/git-sketch-plugin): kactus 的前身开源项目

### Sketch UI Toolkit

- [UX Power Tools](https://www.uxpower.tools/)
- [Frames for Sketch](http://framesforsketch.com/)

### 组件化设计

- [react-sketchapp](https://github.com/airbnb/react-sketchapp): 在 Sketch 里渲染 React 组件

### 样式

- [Sketch-Style-Inventory](https://github.com/getflourish/Sketch-Style-Inventory): 导出整个文档用到的样式到各种格式
- [sketch-palettes](https://github.com/andrewfiorillo/sketch-palettes): 配色集导入导出
- [shared-text-styles](https://github.com/nilshoenson/shared-text-styles): 字体样式集导入导出
- [sketch-copy-to-all](https://github.com/wuwa/sketch-copy-to-all): 拷贝所有样式到其他元素。注意：这只是一种临时处理工具，不要依赖它，而应该用 Symbol 来构建可复用的设计系统。
  - [styledrop](https://github.com/ryanmclaughlin/styledrop): 拷贝单个样式
- [Disconnect for Sketch](https://github.com/einancunlu/Disconnect-for-Sketch): 分别解除 Symbol、Layer Style、Text Style 关联
- [cssketch](https://github.com/johncoates/cssketch): 根据设计稿直接拷贝出 CSS 值，支持 SASS 和 LESS 语法

### 伪数据填充

- [Sketch Data Populator](https://github.com/preciousforever/sketch-data-populator): 伪内容填充，支持文字占位符和图片
- [Unsplash It Sketch Plugin](https://github.com/fhuel/unsplash-it-sketch): 从 unsplash 拿图源填充图片

### 其他插件

- [clipboard-fill](https://github.com/scottsavarie/clipboard-fill): 把剪切板中的图片填充到任意图形中
- [comma](https://github.com/margusholland/comma): 文本处理工具。大小写转换，空格处理，计数等等功能
- [sketch-browser-preview](https://github.com/FreakLand/sketch-browser-preview): 选定 Artboard 一键浏览器预览
- [Rename It](https://github.com/rodi01/renameit): 图层重命名工具，大赞！
- [zoom-alert](https://github.com/nathco/zoom-alert): 「不兼容最新 sketch」当前缩放提示
- [Automate Sketch](https://github.com/Ashung/Automate-Sketch):「待评价」一堆小功能集合
- [sketch-tiles](https://github.com/kumo/sketch-tiles): 方便制作 Tile 的插件

## 原型设计

- [ProtoPie](https://www.protopie.io): 体验一流的原型设计工具
- [Pencil](https://github.com/evolus/pencil/): 开源的，待改进


**[⬆ 返回顶部](#top)**
