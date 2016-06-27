# myblog
我的博客
===================
这就是一个标题
===================
 
----------------
这也是一个章节标题
----------------
基本形式
========
 
`下面这种是最简单的表格形式，当然你也可以去掉表头展示。`
 
=====  =====  =======
  A      B    A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======
 
表内嵌入
========
 
`下面这种简单表内有列表`
 
=====  =====
col 1  col 2
=====  =====
1      Second column of row 1.
2      Second column of row 2.
       Second line of paragraph.
3      - Second column of row 3.
 
       - Second item in bullet
         list (row 3, column 2).
\      Row 4; column 1 will be empty.
=====  =====
 
表头合并
========
 
`表头进行分类合并`
 
=====  =====  ======
   Inputs     Output
------------  ------
  A      B    A or B
=====  =====  ======
False  False  False A
True   False  True
False  True   True
True   True   True
=====  =====  ======
