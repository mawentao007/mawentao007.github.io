#Marvin的blog
[Pelican](http://docs.getpelican.com/en/3.6.0/quickstart.html)
Install
---

        $ pip install pelican markdown


Create a project
---

        $ mkdir blog & cd


Generate site
---

        $ pelican-quickstart
Write something in file.md in content folder

        $ pelican content
Preview site
---
        
        $ cd output
        $ python -m pelican.server
Publish        
---

        $ make publish
将当前目录下的submit.sh拷贝到上一级目录，同时将.git文件拷贝到上一级目录：

        $ ./submit.sh  blogname


Config
---
配置文件有pelicanconf.py和publishconf.py两个，其中第二个引用了第一个。有些字段，比如
SITURL可以在publishconf.py中配置，这样对于本地预览比较方便。

theme
---

        $ pelican-theme -i themePath 
Attention
---
        
        $ 用submit脚本可以完成生成和提交工作！
Todo list
---
+ google 统计
+ google search
+ tag 统计
+ discus 评论
+ 写博客！
