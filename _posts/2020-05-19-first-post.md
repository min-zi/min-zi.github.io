---
layout: post
comments: true
date: 2020-05-19 01:23
title: "Swift 데이터 타입, 상수, 변수"
subject: blog
categories: [ jekyll ]
tags: [ jekyll, plugin ]
---

스위프트 데이터 타입
> _config.yml
 
```yml
plugins:
  - jekyll-paginate
```

> list.html

```html
<div class="pagination">
    {% if paginator.previous_page %}
        <a href="{{ paginator.previous_page_path | prepend: site.baseurl }}" class="fas fa-chevron-left"></a>
    {% endif %}
    {% if paginator.next_page %}
        <a href="{{ paginator.next_page_path | prepend: site.baseurl }}" class="fas fa-chevron-right"></a>
    {% endif %}
    
    <span class="page-left">{{ paginator.page }}</span><span class="page-slice"> / </span><span class="page-right">{{ paginator.total_pages }}</span>
</div>
```
