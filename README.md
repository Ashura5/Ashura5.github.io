# 2023/04/01 #
> 记录自己第一次搭建博客

使用Jekyll + Github Pages搭建。最终选择了jekyll-rtd-theme模板。这个模板比较简洁。大部分的页面只需要对markdown文件进行修改就可以做到。可以满足我对于博客记录的需要。同时也方便我对博客内容进行迁移。

## jekyll-rtd-theme模板优势 ##
1. 根据文件目录自动生成侧边栏，README.md作为索引
1. 一个文件或者一行代码就可以部署完成，比docsify更加简单

    `remote_theme: rundocs/jekyll-rtd-theme`

1. 使用markdown书写，全部使用pages格式

    ```
	# 传统的命名  
    _posts/日期+名称.md  
    # 新的命名  
    目录（分类）/子目录/子目录...../文章.md  
    文章.md
	```
2. 代码高亮（多种主题可供选择）
1. GitHub pages原生支持（提交文档就可以啦）