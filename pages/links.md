---
layout: mypost
title: 友情链接
---

[Vexoben](https://vexoben.github.io/)

[Sheauhaw Jang](https://sheauhawjang.github.io/)

欢迎各位大佬和我互开友链啊ο(=•ω＜=)ρ⌒☆

```
名称：{{ site.title }}
描述：{{ site.description }}
地址：{{ site.domainUrl }}{{ site.baseurl }}
```

<ul>
  {%- for link in site.links %}
  <li>
    <p><a href="{{ link.url }}" title="{{ link.desc }}" target="_blank" >{{ link.title }}</a></p>
  </li>
  {%- endfor %}
</ul>
