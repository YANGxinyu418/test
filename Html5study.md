[toc]
# Html5学习
## html教程
### HTML5 的改进
- 新元素
- 新属性
- 完全支持 CSS3
- Video 和 Audio
- 2D/3D 制图
- 本地存储
- 本地 SQL 数据
- Web 应用

### HTML5 多媒体
>使用 HTML5 你可以简单的在网页中播放 视频(video)与音频 (audio) 。

HTML5 `<video>`
HTML5 `<audio>`
### HTML5 应用
>使用 HTML5 你可以简单地开发应用

- 本地数据存储
- 访问本地文件
- 本地 SQL 数据
- 缓存引用
- Javascript 工作者
- XHTMLHttpRequest 2

### HTML5 图形
- 使用 HTML5 你可以简单的绘制图形:
- 使用 <canvas> 元素。
- 使用内联 SVG。
- 使用 CSS3 2D 转换、CSS3 3D 转换。

### HTML5 使用 CSS3
- 新选择器
- 新属性
- 动画
- 2D/3D 转换
- 圆角
- 阴影效果
- 可下载的字体

### 语义元素
>HTML5 添加了很多语义元素如下所示：

| 标签           | 描述                                                         |
| -------------- | ------------------------------------------------------------ |
| `<article>`    | 定义页面独立的内容区域。                                     |
| `<aside>`      | 定义页面的侧边栏内容。                                       |
| `<bdi>	`    | 允许您设置一段文本，使其脱离其父元素的文本方向设置。         |
| `<command>`    | 定义命令按钮，比如单选按钮、复选框或按钮                     |
| `<details>`    | 用于描述文档或文档某个部分的细节                             |
| `<dialog>`     | 定义对话框，比如提示框                                       |
| `<summary>`    | 标签包含 details 元素的标题                                  |
| `<figure>`     | 规定独立的流内容（图像、图表、照片、代码等等）。             |
| `<figcaption>` | 定义 `<figure>` 元素的标题                                   |
| `<footer>`     | 定义 section 或 document 的页脚。                            |
| `<header>`     | 定义了文档的头部区域                                         |
| `<mark>	`   | 定义带有记号的文本。                                         |
| `<meter>`      | 定义度量衡。仅用于已知最大和最小值的度量。                   |
| `<nav>`        | 定义导航链接的部分。                                         |
| `<progress>`   | 定义任何类型的任务的进度。                                   |
| `<ruby>`       | 定义 ruby 注释（中文注音或字符）。                           |
| `<rt>`         | 定义字符（中文注音或字符）的解释或发音。                     |
| `<rp>`         | 在 ruby 注释中使用，定义不支持 ruby 元素的浏览器所显示的内容。 |
| `<section>`    | 定义文档中的节（section、区段）。                            |
| `<time>`       | 定义日期或时间。                                             |
| `<wbr>`        | 规定在文本中的何处适合添加换行符。                           |
### HTML5 表单
新表单元素, 新属性，新输入类型，自动验证。

### 已移除元素
以下的 HTML 4.01 元素在HTML5中已经被删除:
```
<acronym>
<applet>
<basefont>
<big>
<center>
<dir>
<font>
<frame>
<frameset>
<noframes>
<strike>
```

### <canvas> 新元素
| 标签       | 描述                                                         |
| ---------- | ------------------------------------------------------------ |
| `<canvas>` | 标签定义图形，比如图表和其他图像。该标签基于 JavaScript 的绘图 API |

### 新多媒体元素
| 标签       | 描述                                                         |
| ---------- | ------------------------------------------------------------ |
| `<audio>`  | 定义音频内容                                                 |
| `<video>`  | 定义视频（video 或者 movie）                                 |
| `<source>` | 定义多媒体资源 `<video>` 和 `<audio>`                        |
| `<embed>`  | 定义嵌入的内容，比如插件。                                   |
| `<track>`  | 为诸如 `<video>` 和 `<audio>` 元素之类的媒介规定外部文本轨道。 |

### 新表单元素
| 标签         | 描述                                                         |
| ------------ | ------------------------------------------------------------ |
| `<datalist>` | 定义选项列表。请与 input 元素配合使用该元素，来定义 input 可能的值。 |
| `<keygen>`   | 规定用于表单的密钥对生成器字段。                             |
| `<output>`   | 定义不同类型的输出，比如脚本的输出。                         |

### 新的语义和结构元素
>HTML5提供了新的元素来创建更好的页面结构：

| 标签           | 描述                                                         |
| -------------- | ------------------------------------------------------------ |
| `<article>`    | 定义页面独立的内容区域。                                     |
| `<aside>`      | 定义页面的侧边栏内容。                                       |
| `<bdi>`        | 允许您设置一段文本，使其脱离其父元素的文本方向设置。         |
| `<command>`    | 定义命令按钮，比如单选按钮、复选框或按钮                     |
| `<details>`    | 用于描述文档或文档某个部分的细节                             |
| `<dialog>`     | 定义对话框，比如提示框                                       |
| `<summary>`    | 标签包含 details 元素的标题                                  |
| `<figure>`     | 规定独立的流内容（图像、图表、照片、代码等等）。             |
| `<figcaption>` | 定义 `<figure>` 元素的标题                                   |
| `<footer>`     | 定义 section 或 document 的页脚。                            |
| `<header>`     | 定义了文档的头部区域                                         |
| `<mark>	`   | 定义带有记号的文本。                                         |
| `<meter>	`  | 定义度量衡。仅用于已知最大和最小值的度量。                   |
| `<nav>`        | 定义导航链接的部分。                                         |
| `<progress>`   | 定义任何类型的任务的进度。                                   |
| `<ruby>`       | 定义 ruby 注释（中文注音或字符）。                           |
| `<rt>`         | 定义字符（中文注音或字符）的解释或发音。                     |
| `<rp>`         | 在 ruby 注释中使用，定义不支持 ruby 元素的浏览器所显示的内容。 |
| `<section>`    | 定义文档中的节（section、区段）。                            |
| `<time>`       | 定义日期或时间。                                             |
| `<wbr>`        | 规定在文本中的何处适合添加换行符。                           |

## canvas画布
>必备canvas学习
>
>> https://www.runoob.com/w3cnote/html5-canvas-intro.html

><canvas> 标签定义图形，比如图表和其他图像，您必须使用脚本来绘制图形。

>在画布上（Canvas）画一个红色矩形，渐变矩形，彩色矩形，和一些彩色的文字。

><canvas> 元素用于图形的绘制，通过脚本 (通常是JavaScript)来完成.

><canvas> 标签只是图形容器，您必须使用脚本来绘制图形。

>可以通过多种方法使用 canvas绘制路径,盒、圆、字符以及添加图像。

>一个画布在网页中是一个矩形框，通过 <canvas> 元素来绘制.

- 注意: 默认情况下 <canvas> 元素没有边框和内容。

<canvas>简单实例如下:

<canvas id="myCanvas" width="200" height="100"></canvas>

## 内联SVG
### SVG
- SVG 指可伸缩矢量图形 (Scalable Vector Graphics)
- SVG 用于定义用于网络的基于矢量的图形
- SVG 使用 XML 格式定义图形
- SVG 图像在放大或改变尺寸的情况下其图形质量不会有损失
- SVG 是万维网联盟的标准

### SVG优势
>与其他图像格式相比（比如 JPEG 和 GIF），使用 SVG 的优势在于：

- SVG 图像可通过文本编辑器来创建和修改
- SVG 图像可被搜索、索引、脚本化或压缩
- SVG 是可伸缩的
- SVG 图像可在任何的分辨率下被高质量地打印
- SVG 可在图像质量不下降的情况下被放大

### 实例
```html
<!DOCTYPE html>
<html>
<body>
 
<svg xmlns="http://www.w3.org/2000/svg" version="1.1" height="190">
  <polygon points="100,10 40,180 190,60 10,60 160,180"
  style="fill:lime;stroke:purple;stroke-width:5;fill-rule:evenodd;">
</svg>
 
</body>
</html>
```

### SVG 与 Canvas两者间的区别
>SVG 是一种使用 XML 描述 2D 图形的语言。

>Canvas 通过 JavaScript 来绘制 2D 图形。

SVG 基于 XML，这意味着 SVG DOM 中的每个元素都是可用的。您可以为某个元素附加 JavaScript 事件处理器。

在 SVG 中，每个被绘制的图形均被视为对象。如果 SVG 对象的属性发生变化，那么浏览器能够自动重现图形。

Canvas 是逐像素进行渲染的。在 canvas 中，一旦图形被绘制完成，它就不会继续得到浏览器的关注。如果其位置发生变化，那么整个场景也需要重新绘制，包括任何或许已被图形覆盖的对象。

### Canvas 与 SVG 的比较
>下表列出了 canvas 与 SVG 之间的一些不同之处。

| Canvas                                             | SVG                                                     |
| -------------------------------------------------- | ------------------------------------------------------- |
| 依赖分辨率                                         | 不依赖分辨率                                            |
| 不支持事件处理器                                   | 支持事件处理器                                          |
| 弱的文本渲染能力                                   | 最适合带有大型渲染区域的应用程序（比如谷歌地图）        |
| 能够以 .png 或 .jpg 格式保存结果图像               | 复杂度高会减慢渲染速度（任何过度使用 DOM 的应用都不快） |
| 最适合图像密集型的游戏，其中的许多对象会被频繁重绘 | 不适合游戏应用                                          |

## HTML5 MathML
>HTML5 可以在文档中使用 MathML 元素，对应的标签是 <math>...</math> 。

>MathML 是数学标记语言，是一种基于XML（标准通用标记语言的子集）的标准，用来在互联网上书写数学符号和公式的置标语言。

## 拖放（Drag 和 Drop）
与js交流密切,暂时等候

## 地理定位
与js结合

## HTML5 Video(视频)
### 视频格式
+ MP4 = 带有 H.264 视频编码和 AAC 音频编码的 MPEG 4 文件
+ WebM = 带有 VP8 视频编码和 Vorbis 音频编码的 WebM 文件
+ Ogg = 带有 Theora 视频编码和 Vorbis 音频编码的 Ogg 文件

实例：
```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  您的浏览器不支持 HTML5 video 标签。
</video>
```

### HTML5 `<video> `- 使用 DOM 进行控制
>`<video>` 和 `<audio>` 元素同样拥有方法、属性和事件。

>`<video>` 和 `<audio>`元素的方法、属性和事件可以使用JavaScript进行控制.

其中的方法用于播放、暂停以及加载等。其中的属性（比如时长、音量等）可以被读取或设置。其中的 DOM 事件能够通知您，比方说，`<video>` 元素开始播放、已暂停，已停止，等等。
DOM按钮需结合js

### HTML5 Video 标签
| 标签       | 描述                                        |
| ---------- | ------------------------------------------- |
| `<video>`  | 定义一个视频                                |
| `<source>` | 定义多种媒体资源,比如 `<video>` 和`<audio>` |
| `<track>`  | 定义在媒体播放器文本轨迹                    |

## HTML5 Audio(音频)
实例：
```html
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
您的浏览器不支持 audio 元素。
</audio>
```
### 音频格式的MIME类型
| Format | MIME-type  |
| ------ | ---------- |
| MP3    | audio/mpeg |
| Ogg    | audio/ogg  |
| Wav    | audio/wav  |

### HTML5 Audio 标签
| 标签           | 描述                                                         |
| -------------- | ------------------------------------------------------------ |
| `<audio>	`  | 定义了声音内容                                               |
| `<source>	` | 规定了多媒体资源, 可以是多个，在` <video>` 与 `<audio>`标签中使用 |

## HTML5 新的 Input 类型
- color
- date
- datetime
- datetime-local
- email
- month
- number
- range
- search
- tel
- time
- url
- week

>需要学习PHP语言!

## HTML5 新的表单元素
>HTML5 有以下新的表单元素:
```
<datalist>
<keygen>
<output>
```

| 标签         | 描述                                                         |
| ------------ | ------------------------------------------------------------ |
| `<datalist>` | `<input>`标签定义选项列表。请与 input 元素配合使用该元素，来定义 input 可能的值。 |
| `<keygen>`   | `<keygen>` 标签规定用于表单的密钥对生成器字段。              |
| `<output>`   | `<output>` 标签定义不同类型的输出，比如脚本的输出。          |
## HTML5 新的表单属性
>HTML5 的 <form> 和 <input>标签添加了几个新属性.

><form>新属性：

- autocomplete
- novalidate

><input>新属性：

- autocomplete
- autofocus
- form
- formaction
- formenctype
- formmethod
- formnovalidate
- formtarget
- height 与 width
- list
- min 与 max
- multiple
- pattern (regexp)
- placeholder
- required
- step

## HTML语义元素
### 什么是语义元素?
>一个语义元素能够清楚的描述其意义给浏览器和开发者。

>无语义 元素实例:` <div> 和 <span> -` 无需考虑内容.

>语义元素实例: `<form>, <table>, and <img> -` 清楚的定义了它的内容.

### HTML5` <section>` 元素
>`<section>` 标签定义文档中的节（section、区段）。比如章节、页眉、页脚或文档中的其他部分。

>根据W3C HTML5文档: section 包含了一组内容及其标题。

实例:
```html
<section>
  <h1>WWF</h1>
  <p>The World Wide Fund for Nature (WWF) is....</p>
</section>
```

### HTML5 `<article>` 元素
>`<article>` 标签定义独立的内容。

>`<article> `元素使用实例:

- Forum post
- Blog post
- News story
- Comment

实例:
```html
<article>
  <h1>Internet Explorer 9</h1>
  <p>Windows Internet Explorer 9(缩写为 IE9 )在2011年3月14日21:00 发布。</p>
</article>
```

### HTML5` <nav>` 元素
>`<nav>` 标签定义导航链接的部分。

>`<nav>` 元素用于定义页面的导航链接部分区域，但是，不是所有的链接都需要包含在` <nav>` 元素中!

实例:
```html
<nav>
    <a href="/html/">HTML</a> |
    <a href="/css/">CSS</a> |
    <a href="/js/">JavaScript</a> |
    <a href="/jquery/">jQuery</a>
</nav>
```

### HTML5` <aside>` 元素
>`<aside>` 标签定义页面主区域内容之外的内容（比如侧边栏）。

aside 标签的内容应与主区域的内容相关.

实例:
```html
<p>My family and I visited The Epcot center this summer.</p>
 
<aside>
  <h4>Epcot Center</h4>
  <p>The Epcot Center is a theme park in Disney World, Florida.</p>
</aside>
```

### HTML5` <header>` 元素
>`<header>`元素描述了文档的头部区域

>`<header>`元素主要用于定义内容的介绍展示区域.

在页面中你可以使用多个`<header>` 元素.

实例:
```html
<article>
  <header>
    <h1>Internet Explorer 9</h1>
    <p><time pubdate datetime="2011-03-15"></time></p>
  </header>
  <p>Windows Internet Explorer 9(缩写为 IE9 )是在2011年3月14日21:00发布的</p>
</article>
```

### HTML5` <footer>` 元素
>`<footer>` 元素描述了文档的底部区域.

>`<footer>` 元素应该包含它的包含元素

>一个页脚通常包含文档的作者，著作权信息，链接的使用条款，联系信息等

文档中你可以使用多个 `<footer>`元素.

实例:
```html
<footer>
  <p>Posted by: Hege Refsnes</p>
  <p><time pubdate datetime="2012-03-01"></time></p>
</footer>
```

### HTML5 `<figure>` 和 `<figcaption>` 元素
>`<figure>`标签规定独立的流内容（图像、图表、照片、代码等等）。

>`<figure>` 元素的内容应该与主内容相关，但如果被删除，则不应对文档流产生影响。

>`<figcaption>` 标签定义 `<figure>` 元素的标题.

>`<figcaption>`元素应该被置于 "figure" 元素的第一个或最后一个子元素的位置。

实例:
```html
<figure>
  <img src="img_pulpit.jpg" alt="The Pulpit Rock" width="304" height="228">
  <figcaption>Fig1. - The Pulpit Pock, Norway.</figcaption>
</figure>
```
## HTML5 Web 存储
**学完交互js回看**
>HTML5 web 存储,一个比cookie更好的本地存储方式。

- 什么是 HTML5 Web 存储?
>使用HTML5可以在本地存储用户的浏览数据。

>早些时候,本地存储使用的是 cookie。但是Web 存储需要更加的安全与快速. 这些数据不会被保存在服务器上，但是这些数据只用于用户请求网站数据上.它也可以存储大量的数据，而不影响网站的性能.

>数据以 键/值 对存在, web网页的数据只允许该网页访问使用。
- localStorage 对象
- sessionStorage 对象

## HTML5 Web SQL 数据库
js 回看

> Web SQL 数据库 API 并不是 HTML5 规范的一部分，但是它是一个独立的规范，引入了一组使用 SQL 操作客户端数据库的 APIs。

## HTML5 应用程序缓存
js 回看
- 什么是应用程序缓存（Application Cache）？
>HTML5 引入了应用程序缓存，这意味着 web 应用可进行缓存，并可在没有因特网连接时进行访问。

- 应用程序缓存为应用带来三个优势：

1. 离线浏览 - 用户可在应用离线时使用它们
2. 速度 - 已缓存资源加载得更快
3. 减少服务器负载 - 浏览器将只从服务器下载更新过或更改过的资源。
## HTML5 Web Workers
js 回看
- 什么是 Web Worker？
>当在 HTML 页面中执行脚本时，页面的状态是不可响应的，直到脚本已完成。

>web worker 是运行在后台的 JavaScript，独立于其他脚本，不会影响页面的性能。您可以继续做任何愿意做的事情：点击、选取内容等等，而此时 web worker 在后台运行。

## HTML5 服务器发送事件(Server-Sent Events)
js回看
>HTML5 服务器发送事件（server-sent event）允许网页获得来自服务器的更新。

## HTML5 WebSocket
>WebSocket 是 HTML5 开始提供的一种在单个 TCP 连接上进行全双工通讯的协议。

>WebSocket 使得客户端和服务器之间的数据交换变得更加简单，允许服务端主动向客户端推送数据。在 WebSocket API 中，浏览器和服务器只需要完成一次握手，两者之间就直接可以创建持久性的连接，并进行双向数据传输。

>在 WebSocket API 中，浏览器和服务器只需要做一个握手的动作，然后，浏览器和服务器之间就形成了一条快速通道。两者之间就直接可以数据互相传送。

## HTML(5) 代码规范
>HTML 代码约定
>很多 Web 开发人员对 HTML 的代码规范知之甚少。

>在2000年至2010年，许多Web开发人员从 HTML 转换到 XHTML。

>使用 XHTML 开发人员逐渐养成了比较好的 HTML 编写规范。

>而针对于 HTML5 ，我们应该形成比较好的代码规范，以下提供了几种规范的建议。

### 使用正确的文档类型
- 文档类型声明位于HTML文档的第一行：
```
<!DOCTYPE html>
```
如果你想跟其他标签一样使用小写，可以使用以下代码：
```
<!doctype html>
使用小写元素名
```

- HTML5 元素名可以使用大写和小写字母。

- 推荐使用小写字母：

1. 混合了大小写的风格是非常糟糕的。
2. 开发人员通常使用小写 (类似 XHTML)。
3. 小写风格看起来更加清爽。
4. 小写字母容易编写。
- 不推荐:
```
<SECTION>
  <p>这是一个段落。</p>
</SECTION>
```
- 非常糟糕:
```
<Section>
  <p>这是一个段落。</p>
</SECTION>
```
- 推荐:
```
<section>
  <p>这是一个段落。</p>
</section>
```
### 关闭所有 HTML 元素
>在 HTML5 中, 你不一定要关闭所有元素 (例如 `<p>` 元素)，但我们建议每个元素都要添加关闭标签。

- 不推荐:
```
<section>
  <p>这是一个段落。
  <p>这是一个段落。
</section>
```
- 推荐:
```
<section>
  <p>这是一个段落。</p>
  <p>这是一个段落。</p>
</section>
```
### 关闭空的 HTML 元素
>在 HTML5 中, 空的 HTML 元素也不一定要关闭：
```
我们可以这么写：

<meta charset="utf-8">
也可以这么写：

<meta charset="utf-8" />
在 XHTML 和 XML 中斜线 (/) 是必须的。
```
>如果你期望 XML 软件使用你的页面，使用这种风格是非常好的。

### 使用小写属性名
>HTML5 属性名允许使用大写和小写字母。

- 我们推荐使用小写字母属性名:

1. 同时使用大小写是非常不好的习惯。
2. 开发人员通常使用小写 (类似 XHTML)。
3. 小写风格看起来更加清爽。
4. 小写字母容易编写。
- 不推荐：
```
<div CLASS="menu">
```
- 推荐：
```
<div class="menu">
```
### 属性值
>HTML5 属性值可以不用引号。

- 属性值我们推荐使用引号:
```
如果属性值含有空格需要使用引号。
混合风格不推荐的，建议统一风格。
属性值使用引号易于阅读。
```
```
以下实例属性值包含空格，没有使用引号，所以不能起作用:

<table class=table striped>
以下使用了双引号，是正确的：

<table class="table striped">
```
### 图片属性
- 图片通常使用 alt 属性。 在图片不能显示时，它能替代图片显示。
```
<img src="html5.gif" alt="HTML5">
```
- 定义好图片的尺寸，在加载时可以预留指定空间，减少闪烁。
```
<img src="html5.gif" alt="HTML5" style="width:128px;height:128px">
```
### 空格和等号
- 等号前后可以使用空格。
```
<link rel = "stylesheet" href = "styles.css">
但我们推荐少用空格:

<link rel="stylesheet" href="styles.css">
避免一行代码过长
```
>使用 HTML 编辑器，左右滚动代码是不方便的。

- 每行代码尽量少于 80 个字符。

### 空行和缩进
- 不要无缘无故添加空行。

- 为每个逻辑功能块添加空行，这样更易于阅读。

- 缩进使用两个空格，不建议使用 TAB。

- 比较短的代码间不要使用不必要的空行和缩进。

- 不必要的空行和缩进:
```
<body>

  <h1>菜鸟教程</h1>

  <h2>HTML</h2>

  <p>
    菜鸟教程，学的不仅是技术，更是梦想。
    菜鸟教程，学的不仅是技术，更是梦想。
   菜鸟教程，学的不仅是技术，更是梦想,
    菜鸟教程，学的不仅是技术，更是梦想。
  </p>

</body>
```
- 推荐:
```
<body>

<h1>菜鸟教程</h1>

<h2></h2>
<p>菜鸟教程，学的不仅是技术，更是梦想。
菜鸟教程，学的不仅是技术，更是梦想。
菜鸟教程，学的不仅是技术，更是梦想。
菜鸟教程，学的不仅是技术，更是梦想。</p>

</body>
```
### 表格实例:
```
<table>
  <tr>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>A</td>
    <td>Description of A</td>
  </tr>
  <tr>
    <td>B</td>
    <td>Description of B</td>
  </tr>
</table>
```
### 列表实例:
```
<ol>
  <li>London</li>
  <li>Paris</li>
  <li>Tokyo</li>
</ol>
```
### 省略 <html> 和 <body>?
>在标准 HTML5 中，` <html>` 和 `<body>` 标签是可以省略的。

>以下 HTML5 文档是正确的:

实例:
```
<!DOCTYPE html>
<head>
  <title>页面标题</title>
</head>

<h1>这是一个标题</h1>
<p>这是一个段落。</p>

```
+ 不推荐省略 `<html>` 和 `<body>` 标签。

`<html>` 元素是文档的根元素，用于描述页面的语言：
```
<!DOCTYPE html>
<html lang="zh">
声明语言是为了方便屏幕阅读器及搜索引擎。
```
- 省略 `<html>` 或 `<body>` 在 DOM 和 XML 软件中会崩溃。

- 省略` <body>` 在旧版浏览器 (IE9)会发生错误。

### 省略 `<head>`?
>在标准 HTML5 中， <head>标签是可以省略的。

>默认情况下，浏览器会将 <body> 之前的内容添加到一个默认的 <head> 元素上。

实例
```
<!DOCTYPE html>
<html>
<title>页面标题</title>

<body>
  <h1>这是一个标题</h1>
  <p>这是一个段落。</p>
</body>

</html>
```
- 现在省略 head 标签还不推荐使用。
### 元数据
- HTML5 中 `<title>` 元素是必须的，标题名描述了页面的主题:
```
<title>菜鸟教程</title>
标题和语言可以让搜索引擎很快了解你页面的主题:
```
```
<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <title>菜鸟教程</title>
</head>
```
### HTML 注释
>注释可以写在` <!-- 和 -->` 中:
```
<!-- 这是注释 -->
比较长的评论可以在 <!-- 和 --> 中分行写：

<!--
  这是一个较长评论。 这是 一个较长评论。这是一个较长评论。
  这是 一个较长评论 这是一个较长评论。 这是 一个较长评论。
-->
长评论第一个字符缩进两个空格，更易于阅读。
```
### 样式表
>样式表使用简洁的语法格式 ( type 属性不是必须的):
```
<link rel="stylesheet" href="styles.css">
短的规则可以写成一行:

p.into {font-family: Verdana; font-size: 16em;}
长的规则可以写成多行:

body {
  background-color: lightgrey;
  font-family: "Arial Black", Helvetica, sans-serif;
  font-size: 16em;
  color: black;
}
```
- 将左花括号与选择器放在同一行。
- 左花括号与选择器间添加一个空格。
- 使用两个空格来缩进。
- 冒号与属性值之间添加一个空格。
- 逗号和符号之后使用一个空格。
- 每个属性与值结尾都要使用分号。
- 只有属性值包含空格时才使用引号。
- 右花括号放在新的一行。
- 每行最多 80 个字符。
- 在逗号和冒号后添加空格是常用的一个规则。
### 在 HTML 中载入 JavaScript
>使用简洁的语法来载入外部的脚本文件 ( type 属性不是必须的 ):
```
<script src="myscript.js">
使用 JavaScript 访问 HTML 元素
一个糟糕的 HTML 格式可能会导致 JavaScript 执行错误。

以下两个 JavaScript 语句会输出不同结果:

实例
var obj = getElementById("Demo")

var obj = getElementById("demo")

```
- HTML 中 JavaScript 尽量使用相同的命名规则。

### 访问 JavaScript 代码规范。

- 使用小写文件名
- 大多 Web 服务器 (Apache, Unix) 对大小写敏感： london.jpg 不能通过 London.jpg 访问。

- 其他 Web 服务器 (Microsoft, IIS) 对大小写不敏感： london.jpg 可以通过 London.jpg 或 london.jpg 访问。

- 必须保持统一的风格，我们建议统一使用小写的文件名。

### 文件扩展名
- HTML 文件后缀可以是 .html (或 .htm)。

- CSS 文件后缀是 .css 。

- JavaScript 文件后缀是 .js 。

>.htm 和 .html 的区别
>.htm 和 .html 的扩展名文件本质上是没有区别的。浏览器和 Web 服务器都会把它们当作 HTML 文件来处理。

区别在于：

1. .htm 应用在早期 DOS 系统，系统现在或者只能有三个字符。

2. 在 Unix 系统中后缀没有特别限制，一般用 .html。

技术上区别
1. 如果一个 URL 没有指定文件名 (如 http://www.runoob.com/css/), 服务器会返回默认的文件名。通常默认文件名为 index.html, index.htm, default.html, 和 default.htm。

2. 如果服务器只配置了 "index.html" 作为默认文件，你必须将文件命名为 "index.html", 而不是 "index.htm"。

>但是，通常服务器可以设置多个默认文件，你可以根据需要设置默认文件名。

>不管怎样，HTML 完整的后缀是 ".html"。



## 暂定这些