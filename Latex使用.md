# Latex学习
编译器为Texstudio

施工中...
# 一、Latex文件的基本结构

```latex
% 导言区
\documentclass{article}  %book/report/letter

% 正文区
\begin{document}
    文本内容
    Let $f(x)$ be difined by the foluma $f(x)=3x^2+x-1$
\end{document}
```

>导言区中主要进行**全局设置**
```latex
% 设置文章名称
\title{My First Latex article}
% 设置文章作者
\author{Jedi Master}
% 设置编辑时间
\date{2024.3.2} % {\today}表示今天

%在正文区 \maketitle(此命令在letter类中无效) 显示上面的信息 

```

# 段落 中文处理
# 公式    
```latex
行内公式使用  $$
另起一行公式使用 $$$$
```
# 图片
# 表格
# 文献引用
# 使用模板