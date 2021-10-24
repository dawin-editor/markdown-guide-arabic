---
title: الفقرات
syntax-id: paragraphs
description: "To create paragraphs, use a blank line to separate one or more lines of text. You should not indent paragraphs with spaces or tabs."
examples:
  - markdown: |
      I really like using Markdown.

      I think I'll use it to format all of my documents from now on.
    html: "<p>I really like using Markdown.</p><p>I think I'll use it to format all of my documents from now on.</p>"
---

لإنشاء فقرات، أترك سطرًا فارغًا بعد كل فقرة كي تفصل سطرًا واحدًا أو أكثر من النص.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
        <th>تنسيق ماركداون</th>
        <th>HTML</th>
        <th>النتيجة النهائية</th>
  </tr>
  </thead>
  <tbody>
<tr>
<td>
  <code class="highlighter-rouge">
    أنا حقا أحب استخدام ماركداون.<br /><br />

أعتقد أنني سأستخدمها لتنسيق جميع مستنداتي من الآن فصاعدًا.
</code>

</td>
<td>
  <code class="highlighter-rouge">&lt;p&gt;أنا حقا أحب استخدام ماركداون.&lt;/p&gt;<br /><br />

&lt;p&gt;أعتقد أنني سأستخدمها لتنسيق جميع مستنداتي من الآن فصاعدًا.&lt;/p&gt;</code>

</td>
<td>
  <p>أنا حقا أحب استخدام ماركداون.</p>

  <p>أعتقد أنني سأستخدمها لتنسيق جميع مستنداتي من الآن فصاعدًا.</p>
</td>
</tr>

</tbody>
</table>

### أفضل ممارسات كتابة الفقرات

لا تضع مسافة بادئة سواء بالمسافات (Spaces) أو بأزرار Tabs في لوحة المفاتيح، إلا في حالة أنّ [الفقرة في قائمة](https://guide.dawin.io/basic-syntax/#paragraphs).

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; افعل</th>
      <th>❌&nbsp; لا تفعل</th>
    </tr>
  </thead>
  <tbody>
<tr>
<td>
<code class="highlighter-rouge">
لا تضع مسافة بادئة  بزر المسافة ولا بأزرار tabs قبل فقراتك.
<br><br>

دع الأسطر محاذية لبداية الكتابة كهذا النص.
<br><br>
</code>

</td>
<td>
<code class="highlighter-rouge">
&nbsp;&nbsp;&nbsp;&nbsp;قد يؤدي هذا الفراغ إلى مشاكل غير متوقعة في التنسيق.<br><br>

&nbsp;&nbsp;لا تضف مسافات في بداية الفقرات سواء بزر المسافة أو أزرار الtabs.
</code>

</td>
</tr>
</tbody>
</table>
