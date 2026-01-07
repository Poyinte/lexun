<div align="left">
 
  [![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

</div>
<br>
<div align="center">
<p>
<img src="./icons/title.svg" height="150" align="center">
</p>

面向中国英语学习者的超纲词标注工具
<br>
<sub>Powered by <code><img src="./icons/gemini.svg" height="12" align="center"> Gemini</code></sub>

[![下载](https://img.shields.io/badge/下载-离线网页-0e7ff1?style=flat-square&logo=googlechrome&logoColor=white)](https://github.com/Poyinte/Lexun/releases/download/v1.0.0/Lexun.html) [![访问](https://img.shields.io/badge/访问-线上网页-084c91?style=flat-square&logo=github)](https://poyinte.github.io/Lexun/)
</div>
<br><br>
<div align="right">
<sub>* 标注结果可能存在错漏。投入使用前请进行人工核对。</sub><br>
<sub>** 线上网页为部署在 <code>GitHub Pages</code> 上的静态网页。<br>
  除 <code>学习窗口</code> 外，其余功能均在本地离线运行，数据不会上传至任何服务器。</sub>
</div>

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png

---

# <img src="./icons/rocket.svg" height="30"> 快速使用

## 导入单词表

* 点击左侧栏 <kbd><img src="./icons/sidebar-import-list.svg" height="15" align="center"> 导入单词表</kbd>，选择 `.txt` 单词表文件。
  
>[!NOTE]
> 单词表文件格式为 `一行一词`。

以下是两个在国内具有代表性的单词表。

>[!WARNING]
> 以下单词表均提取自相关正式文件。可能有所疏漏，仅供参考。

<div align="center">

| 单　　　词　　　表 |`.txt` 文件|
| ---------- | -----------|
| [全国大学英语四、六级考试大纲<sub>（2016 年修订版）</sub>](https://cet.neea.edu.cn/res/Home/1704/55b02330ac17274664f06d9d3db8249d.pdf) | [![CET6](https://img.shields.io/badge/-CET6.txt-084c91?style=flat-square&logo=googledocs&logoColor=white)](https://github.com/Poyinte/Lexun/releases/download/v1.0.0/CET6.txt) |
| [普通高中英语课程标准<sub>（2017 年版 2020 年修订）</sub>](https://www.pep.com.cn/xw/zt/rjwy/gzkb2020/202205/P020220517522153664167.pdf) | [![CET6](https://img.shields.io/badge/-SeniorHigh.txt-084c91?style=flat-square&logo=googledocs&logoColor=white)](https://github.com/Poyinte/Lexun/releases/download/v1.0.0/SeniorHigh.txt) |

</div>

## 载入文本

* 复制需要标注的文本后，点击左侧栏 <kbd><img src="./icons/sidebar-new-page.svg" height="15" align="center"> 新建空白页</kbd>，在空白页的 `阅读视图` 中粘贴文本。

>[!TIP]
> 可使用快捷键 <kbd>Ctrl</kbd> + <kbd>V</kbd> 新建空白页并粘贴文本。


* 点击左侧栏 <kbd><img src="./icons/sidebar-import-text.svg" height="15" align="center"> 导入文本</kbd>，选择 `.txt` 文本文件<sup> `可多选`</sup>。

>[!TIP]
> 标签页数量过多，标签栏无法完整显示时，可将 `鼠标` 移至标签栏左右两端来左右移动标签栏。

* 点击左侧栏 <kbd><img src="./icons/sidebar-clear.svg" height="15" align="center"> 清空阅读视图</kbd> 会关闭所有标签页。

## 超纲词标注

* 点击左侧栏 <kbd>开始标注</kbd>。

## 查看超纲词

* 在 `阅读视图` 中点击标注词或在右侧 `超纲词列表` 中点击超纲词均可选中并跳转至该词。
* 在右侧 `超纲词列表` 中，超纲词的 `出现次数` 显示在右侧。`出现次数` 大于 `1` 的词可多次点击，`阅读视图` 会依照该词在文中的出现顺序依次跳转。
  
>[!NOTE]
> 选中后的超纲词其列表右侧的数字显示格式为：`选中词的序号/总次数`。

* 可随时点击 `超纲词列表栏` 右侧的 <kbd><img src="./icons/toolbar-sort.svg" height="15" align="center"></kbd> 来切换列表排序。设有以下三种排序方式：

<div align="center">

| 排序方式 |说　　　明|
| :----------: | -----------|
|`正　序`|`默认` 按出现先后排序|
|`次　数`|按出现次数从多到少排序|
|`音　序`|按单词首字母先后排序|

</div>


## 学习超纲词

* 在 `阅读视图` 中选中超纲词，再次点击可呼出 `学习窗口`。多次点击选中的超纲词可在两个学习窗口间来回切换。设有以下两种窗口：

<div align="center">

| 学习窗口 |说　　　　　明|
| :----------: | -----------|
|`相关词`|显示在 `单词表` 中与该超纲词意思相关的词语|
|`词　典`|显示该超纲词在 `线上词典` 中的查询结果|

</div>

## 手动编辑
* 点击 `阅读视图栏` 右侧的 <kbd><img src="./icons/toolbar-edit.svg" height="15" align="center"></kbd> 可启用 `编辑模式`，编辑 `阅读视图` 中的文本。
* 点击 `超纲词列表栏` 右侧的 <kbd><img src="./icons/toolbar-add.svg" height="15" align="center"> 添加</kbd> 可手动添加超纲词。

>[!TIP]
> 可使用快捷键 <kbd>Enter</kbd> 添加超纲词。

* 在 `阅读视图` 中或在右侧 `超纲词列表` 中 <kbd>鼠标右键</kbd> 点击超纲词可手动 `移除` 或 `恢复` 超纲词。

## 导出结果

* 点击左侧栏 <kbd><img src="./icons/sidebar-copy.svg" height="15" align="center"> 复制标注结果</kbd>，可复制带有标注的文本<sup> `标注词会被加粗`</sup>。
* 点击左侧栏 <kbd><img src="./icons/sidebar-export.svg" height="15" align="center"> 导出超纲词列表</kbd>，可生成 `一行一词` 格式的 `.txt` 超纲词列表文件。

# <img src="./icons/shield-check.svg" height="30"> 隐私与安全

>[!IMPORTANT]
> 除 `学习窗口` 需联网调用 `API` 外，其余功能均在本地离线运行，数据不会上传至任何服务器。

# <img src="./icons/layers.svg" height="30"> 使用资源

## 自然语言资源
| 用　　途 |使　　　用　　　资　　　源|
| :----------: | -----------|
|`自然语言处理`|[compromise: modest natural-language processing](https://github.com/spencermountain/compromise)|
|`相关词处理`|[Datamuse API](https://www.datamuse.com/api/) |
|`在线词典查询`|[英语单词详解 - 免费API](https://v2.xxapi.cn/api/englishwords)|
|`不规则动词映射表`|[English irregular verbs - Wikipedia](https://en.wikipedia.org/wiki/English_irregular_verbs#List)|

## 图形资源
| 用　　途 |使　　　　用　　　　资　　　　源|
| :----------: | -----------|
|`标识字体`|[glow-sans: SHSans-derived CJK font family with a more concise & modern look.](https://github.com/welai/glow-sans?tab=readme-ov-file)|
|`用户界面图标`|[lucide: Beautiful & consistent icon toolkit made by the community.](https://github.com/lucide-icons/lucide?tab=readme-ov-file) |
