---
layout: tools
title: أدوات
description: تطبيقات ومكوّنات تدعم ماركداون.
last_modified_at: 2021-08-03
---

<div class="row">
  <div class="col-sm-3" style="padding-top:20px">
    <div class="card" style="width: 16rem; height: 15rem;">
      <div class="card-body">
        <h4 class="card-title no-anchor" style="margin-top: -20px;"><span class="emoji" style="font-size:30px">👋</span>&nbsp;&nbsp;&nbsp;مرحبا!</h4>
        <p class="card-text">هذه هي بداية الدليل الشامل لأدوات ماركداون. تجميع كل هذه الأدوات سيستغرق بعض الوقت! <a href="https://github.com/mattcone/markdown-guide/wiki/Markdown-tool-directory">تعلم كيف تساهم.</a></p>
      </div>
    </div>
  </div>

<div class="col-sm-3" style="padding-top:20px">
    <div class="card" style="width: 16rem; height: 15rem;">
      <div class="card-body">
        <h4 class="card-title no-anchor" style="margin-top: -20px; font-size: 20px;"><a href="https://dawin.io/"><img src="/assets/images/tool-icons/dawin.png" alt="محرر دوّن" style="width:40px; margin-top:-5px"></a>&nbsp;&nbsp;محرّر دوّن</h4>
        <p class="card-text">محرّر نصوص ماركداون عربي بمعاينة مباشرة على متصفّحك وهاتفك، يمكنك تثبيته أينما أردت، ويعمل دون الحاجة إلى إنترنت.</p>
        <a href="https://www.dawin.io/" class="btn btn-outline-secondary btn-sm">ابدأ الكتابة الآن</a>
      </div>
    </div>
  </div>
{% for tool in site.tools %}

  <div class="col-sm-3" style="padding-top:20px">
    <div class="card" style="width: 16rem; height: 15rem;">
      <div class="card-body">
        <h4 class="card-title no-anchor" style="margin-top: -20px; font-size: 20px;"><a href="{{ tool.url }}"><img src="/assets/images/tool-icons/{{ tool.icon }}" alt="{{ tool.title }} logo" style="width:50px; margin-top:-5px"></a>&nbsp;&nbsp;{{ tool.title }}</h4>
        <p class="card-text">{{ tool.description }}</p>
        <a href="{{ tool.url }}" class="btn btn-outline-secondary btn-sm">المزيد</a>
      </div>
    </div>
  </div>
  {% endfor %}
</div>
