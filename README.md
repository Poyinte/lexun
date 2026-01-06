面向中国英语学习者的超纲词标注工具

# 快速使用

## 导入单词表

* 点击左侧栏 <img src="./icons/sidebar-import-list.svg" height="15"> <kbd>导入单词表</kbd>，选择 `.txt` 单词表文件。

>[!NOTE]
> 单词表文件格式为 `一行一词`。

以下是两个在国内具有代表性的单词表。

>[!WARNING]
> 以下单词表均提取自相关正式文件。可能有所疏漏，仅供参考。

<div align="center">

| 单　　　词　　　表 |`.txt` 文件|
| ---------- | -----------|
| 全国大学英语四、六级考试大纲 `（2016 年修订版）`  | [![CET6](https://img.shields.io/badge/-CET6.txt-084c91?style=flat-square&logo=googledocs&logoColor=white)](https://github.com/Poyinte/lexun/raw/main/wordlist/CET6.txt) |
| 普通高中英语课程标准 `（2017 年版 2020 年修订）`  | [![CET6](https://img.shields.io/badge/-SeniorHigh.txt-084c91?style=flat-square&logo=googledocs&logoColor=white)](https://github.com/Poyinte/lexun/raw/main/wordlist/SeniorHigh.txt) |

</div>

## 载入文本

* 复制需要标注的文本后，点击左侧栏 <img src="./icons/sidebar-new-page.svg" height="15"> <kbd>新建空白页</kbd>，在空白页的 `阅读视图` 中粘贴文本。

>[!TIP]
> 可使用快捷键 <kbd>Ctrl</kbd> + <kbd>V</kbd> 新建空白页并粘贴文本。


* 点击左侧栏 <img src="./icons/sidebar-import-text.svg" height="15"> <kbd>导入文本</kbd>，选择 `.txt` 文本文件 `可多选`。

>[!TIP]
> 标签页数量过多，标签栏无法一次显示时，可将 `鼠标` 移至标签栏左右两端来左右移动标签栏。

* 点击右侧栏 <img src="./icons/sidebar-clear.svg" height="15"> <kbd>清空阅读视图</kbd> 会关闭所有标签页。

## 超纲词标注

* 点击左侧栏 <kbd>开始标注</kbd>。

## 查看超纲词

* 在 `阅读视图` 中点击标注词或在右侧 `超纲词列表` 中点击超纲词均可选中并跳转至该词。
* 在右侧 `超纲词列表` 中，超纲词的 `出现次数` 显示在右侧。`出现次数` 大于 `1` 的词可多次点击，`阅读视图` 会依照该词在文中的出现顺序依次跳转。
  
>[!NOTE]
> 选中后的超纲词其列表右侧的数字显示格式为：`选中词的序号/总次数”`。

* 可随时点击 `超纲词列表栏` 中的 <img src="./icons/toolbar-sort.svg" height="15"> 来切换列表排序。设有以下三种排序方式：

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
|`相关词`|在 `单词表` 中与该超纲词意思相关的词语|
|`词　典`|该超纲词在 `线上词典` 中的查询结果|

</div>

>[!NOTE]
>线上词典API：https://v2.xxapi.cn/api/englishwords

## 手动编辑
* 点击 `阅读视图栏` 右侧的 <img src="./icons/toolbar-edit.svg" height="15"> 可启用 `编辑模式`，编辑 `阅读视图` 中的文本。
* 点击 `超纲词列表栏` 右侧的 <img src="./icons/toolbar-add.svg" height="15"> <kbd>添加</kbd> 可手动添加超纲词。

>[!TIP]
> 可使用快捷键 <kbd>Enter</kbd> 添加超纲词。

* 在 `阅读视图` 中或在右侧 `超纲词列表` 中 <kbd>鼠标右键</kbd> 点击超纲词可手动 `移除` 或 `恢复` 超纲词。

## 导出结果

* 点击左侧栏 <img src="./icons/sidebar-copy.svg" height="15"> <kbd>复制标注结果</kbd>，可复制带有标注的文本 `标注词被加粗`。
* 点击左侧栏 <img src="./icons/sidebar-export.svg" height="15"> <kbd>导出超纲词列表</kbd>，可生成 `一行一词` 格式的 `.txt` 超纲词列表文件。
