# citespace-auto


以中国知网（CNKI）为数据来源，在学科目录中选“中医学”“中药学”“中西医结合”。采取高级检索，检索式为:（“早泄”or“PE”or“鸡精”or“臻疾”or“溢精”）。检索年限为不限—2021 年 8 月 15 日,检索条件为中文文献，共得到 1356 条结果。然后进行人工筛选，剔除报纸、会议通知、稿约等与 PE 无关的文献 289 篇，最后共纳入 1067 篇文献。规范化处理：以《中医外科学》中的描述为参考基础，对疾病名称、证型、治法等进行规范化处理，以《中药学》中的描述为参考，对中药术语进行规范，合并同义词（如“肾阴虚”与“肾阴不足”等）


Citespace 是应用 Java 语言所开发的文献可视化软件，通过软件
对现有数据库中文献的处理，可形象、准确、便捷地对某学科领域的
研究历程进行客观分析，预测该领域未来的研究趋势，为接下来的研
究方向提供新思路，因此，该软件的应用受到众多学者与研究人员的
重视[9-12]。本文应用的软件为 Citespace5.0.R1（Drexel University，
Philadelphia，PA，USA），具有将关键词进行聚类与共现分析的功
能。


将符合要求的 1067 篇知网文献转化为 Refworks 格式，并导出到新建的 input 文件夹中，利用 Citespace5.0.R1 将 input 中的文献转化
为软件可识别的 download .txt 格式。在 Citespace 的操作区域新建 Title（标题）“PE，”Project Home（项目主页）路径选择新建的 project 文
件夹，Data Directory（数据目录）路径选择新建的 output 文件夹，因纳入的文献首篇发表于 1954 年，故将软件右上角区域 Time Slicing（时
间分区）调整为 1954 年 1 月－2021 年 8 月，Years Per Slice（时间切片）设置为每一年。（因研究 PE 的作者及研究机构较少，在进行作
者以及研究机构的分析时，将时间切片调整为每 10 年。）Node Types（节点类型）分别勾选 Author（作者）、Institution（机构）时，Pruning
（剪切方式）将 Pathfinder 法和 Pruning sliced networks 法都勾选上。而节点类型勾选 Keyword（关键词）时剪切方式只选择 Pruning sliced networks 法。
