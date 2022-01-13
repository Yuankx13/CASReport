# 中科院开题中期报告LaTeX模板

#### 介绍
这是主要面向中国科学院地质与地球物理研究所制作的开题和中期报告模板，中科院其它单位大体上也是通用的，因为题头只是中科院大学而已。详细描述自己编译了之后可以看到。

#### 软件架构
采用LaTeX2e编辑，主要使用xeCJK实现中文支持。


#### 使用说明

主文件是Report.tex
编译时先执行XeLaTex，形成各个编译准备文件。
然后运行BibTeX，形成参考文献库
最后连续运行两次XeLaTeX，将超链接、交叉引用等安排进入文档。

参考文献的Bib库为20190110.bib，也可以按需自己编辑，记得修改主文件中指向的bib文件。
具体说明请自行参见文中说明

#### 参与贡献

