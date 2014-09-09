typecho to jekyll
===============

Fork from [lauyoume/typecho_to_hexo](https://github.com/lauyoume/typecho_to_hexo)  
Convert typecho blog to jekyll by nodejs

导出 typecho 博客 为 jekyll 支持的 Markdown 文档

说明
===============

导出每篇博文, md文件名格式为: {date}-{slug}.md 若需更改请改源码。  
只修改了转换文章的部分，会自动对代码段作处理，转换成 jekyll 标准格式的高亮代码段。在这里需要注意一个问题: 
务必标明代码段高亮类型，比如 js、python ，以确保它可以被正确地检测。 
另外，标题不能以 ` [ ` 符号开始，会导致检测错误。有时间再作修改。
