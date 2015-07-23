---
layout: page
title: 只言片语
tagline: Supporting tagline
---
{% include JB/setup %}

阅读 [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html){:target="_blank"}

完整的使用方法地址: [Jekyll Bootstrap](http://jekyllbootstrap.com){:target="_blank"}

## 修改作者等属性

在 `_config.yml` 输入你自己的信息:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

任何时候主题都需要这些变量。
    
## 小样本

这个博客包含了帮助网页和博客数据的示例文章。如果你不再需要这些，就请删除掉 `_posts/core-samples` 这个文件夹

    $ rm -rf _posts/core-samples

这里有个简单 "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 需要你

这个主题现在还没有完成。如果你想成为一名贡献者, [Fork](http://github.com/plusjade/jekyll-bootstrap){:target="_blank"}!






