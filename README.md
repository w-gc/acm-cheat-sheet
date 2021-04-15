# 手写代码必备手册（注释版）

原版来自[手写代码必备手册](https://github.com/soulmachine/acm-cheat-sheet/blob/master/C++)

<!-- # C++版 ----------------- **下载**：<a href="https://github.com/soulmachine/acm-cheat-sheet/blob/master/C++/%E6%89%8B%E5%86%99%E4%BB%A3%E7%A0%81%E5%BF%85%E5%A4%87%E6%89%8B%E5%86%8C(C++%E7%89%88).pdf?raw=true">手写代码必备手册(C++版).pdf</a> 书的内容与Java版一摸一样，不过代码是用C++写的。 -->

显示注释：
```LaTex
\usepackage{color}
\newcommand{\Note}[1]{\textcolor{blue}{【注：#1】}} %% 笔记
\newcommand{\Hl}[1]{\textcolor{red}{#1}} %% Highlight
\newcommand{\Dl}{---------------------------------------------------------------------分割线-------------------------------------------------------------------} %% Dividingline
\usepackage{listings}
\lstnewenvironment{NoteCode}{
\lstset{ %
backgroundcolor=\color{white},   % choose the background color
basicstyle=\small,        % size of fonts used for the code
columns=fullflexible,
breaklines=true,                 % automatic line breaking only at whitespace
captionpos=b,                    % sets the caption-position to bottom
tabsize=4,
commentstyle=\color{magenta},    % comment style
escapeinside={\%*}{*)},          % if you want to add LaTeX within your code
keywordstyle=\color{blue},       % keyword style
stringstyle=\color{green}\ttfamily,     % string literal style
frame=single, % none
% rulesepcolor=\color{red!20!green!20!blue!20},
% identifierstyle=\color{red},
language=C++
}}{}
```

关闭注释：
```LaTex
\newcommand{\Note}[1]{} %% 笔记 (注释掉)
\newcommand{\Hl}[1]{#1} %% Highlight (注释掉)
\newcommand{\Dl}[1]{} %% Dividingline (注释掉)
\usepackage{comment}
\newenvironment{NoteCode}{}{}
\excludecomment{NoteCode}
```