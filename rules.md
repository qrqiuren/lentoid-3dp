# 文档规范（alpha版）

这是Lentoid 3D打印机的文档。本文档参与编辑人员力求做到本规范所规定内容。

## 内容

*   每一部分开始之前，应当向读者指明工具和材料的清单，并用有序列表表示，最好标注预计价格（以淘宝为准）；
*   在描述操作步骤时，应尽量使用祈使句，少用第二人称；
*   每一部分制作结束时，有必要时必须指导读者做调试；
*   正文中间可以穿插一些额外的讲解和启发思考的问题，这一部分使用引用格式；
*   每一部分作者不能在影响阅读的情况下刷存在感，因为GitHub会自动整理commit清单，所以秋纫桑发布本文档时自然会列出贡献人员名单的。

## 知识

本文档对读者的知识面做如下假设：

*   读者已经掌握基本的工程图学知识与电路分析能力（包括对半导体器件的初步了解）；
*   读者是书呆子，没有工程实践经验；
*   读者看得懂英文参考资料。

## Markdown语法

*   使用[标准Markdown](http://daringfireball.net/projects/markdown/syntax)，最终以在[Maruku](http://maruku.rubyforge.org/index.html)导出成HTML的效果为准；
*   标题使用行首井号表示，不要使用行末井号或下划线；
*   无序列表用星号表示；
*   分割线用连续的三个星号表示，并且不许卖萌；
*   一层缩进是四个空格。

## 资源

所有文件名只能使用ASCII编码。除了Markdown文字以外，所有文件使用下划线命名法。

*   **Markdown文字**：放到根目录下，已编号的文档的文件名以表示序号的两位数字和空格开头，未编号的文档文件名不含编号，文档编号方式参见下边“文档结构”；
*   **普通格式图片**：放到img文件夹下；
*   **机械图纸**：放到cad文件夹下，同时包含CAD软件格式与PDF格式；
*   **框图**：使用[Dia](https://wiki.gnome.org/Apps/Dia)制作框图，将框图以及导出的png图片保存到dia文件夹下，框图所用字体为黑体（SimHei），大小28 pt；
*   **其他资源**：放到misc文件夹下。

## 全文结构

下面以无序列表列出所有章节的提纲，每一项前面的数字，第一位表示章号，第二位表示节号，合在一起是文档编号。文档的标题由作者自拟。

章号为0的文档都是总述或非技术的内容。节号为0的文档是每一章开头的引子。

*   【10】机械
    *   【11】除挤出机外的部分制作与组装，以及标准件紧固件
    *   【12】挤出机部分
*   【20】电路
    *   【21】主板
    *   【22】截止器
*   【30】软件
    *   【31】主板单片机的引导程序以及固件
    *   【32】电脑上位机
    *   【33】三维模型设计软件