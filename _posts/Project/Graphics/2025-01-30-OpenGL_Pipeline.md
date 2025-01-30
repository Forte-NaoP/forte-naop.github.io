---
title: "OpenGL 파이프라인 정리"
date: "2024-12-28 17:49:24 +0900"
categories: [Project, Graphics]
tags: [OpenGL]
use_math: true
---

{% assign remote_url = "https://raw.githubusercontent.com/Forte-NaoP/Univ-Project/main/Computer-Graphics/OpenGL-Pipeline.md" %}
{% assign img_url = remote_url | remove: "OpenGL-Pipeline.md" %}

{% capture remote_content %}
    {% remote_include https://raw.githubusercontent.com/Forte-NaoP/Univ-Project/main/Computer-Graphics/OpenGL-Pipeline.md %}
{% endcapture %}

{{ remote_content 
  | replace: './', img_url
}}

<p>🔗 <a href="https://github.com/Forte-NaoP/Univ-Project/blob/main/Computer-Graphics/OpenGL-Pipeline.md" target="_blank">원본 파일 보기</a></p>