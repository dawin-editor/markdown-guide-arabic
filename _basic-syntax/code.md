---
title: الأكواد البرمجية
syntax-id: code
syntax-summary: "`code`"
description: "To denote a word or phrase as code, enclose it in backticks (`` ` ``)."
examples:
  - markdown: "At the command prompt, type `nano`."
    html: "At the command prompt, type <code>nano</code>."
additional-examples:
  - name: "Escaping Backticks"
    description: "If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks (<code>``</code>)."
    markdown: "``Use `code` in your Markdown file.``"
    html: <code>Use `code` in your Markdown file.</code>
  - name: "Code Blocks"
    description: "To create code blocks, indent every line of the block by at least four spaces or one tab."
    markdown: |
      <html>
        <head>
        </head>
      </html>
    html: <pre><code><html><head></head></html></code></pre>
---

لتحديد كلمة أو عبارة أنها كود برمجي، ضعها بين الفاصلة العليا المائلة (`).

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
      <td><code class="highlighter-rouge">في سطر الأوامر، اكتب `nano`.</code></td>
      <td><code class="highlighter-rouge">في سطر الأوامر، اكتب  &lt;code&gt;nano&lt;/code&gt;. </code></td>
      <td>في سطر الأوامر، اكتب <code class="highlighter-rouge">nano</code>.</td>
    </tr>
  </tbody>
</table>

### تخطي الفاصلة العليا المائلة (Backticks)

إذا تضمّنت الكلمة أو العبارة التي تريد تحديدها أنها كود برمجي واحد أو أكثر من الفواصل العليا المائلة (backticks)، فيمكنك تجاوزها باحتواء الكلمة أو العبارة في بفاصلتين مزدوجتين (<code>``</code>).

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
      <td><code>``استخدام `code` في ملف ماركداون الخاص بك.``</code></td>
      <td><code class="highlighter-rouge">&lt;code&gt;استخدام `code` في ملف ماركداون الخاص بك.&lt;/code&gt;</code></td>
      <td><code>استخدام `code` في ملف ماركداون الخاص بك.</code></td>
    </tr>
  </tbody>
</table>

### الكتل البرمجية

لإنشاء كتل أكواد برمجية، ضع مسافة بادئة لكل سطر من الكتلة برمجية، بأربع مسافات (Spaces) على الأقل أو بزر Tab واحد.

```text
   <html>
     <head>
     </head>
   </html>
```

[لاحظ الإزاحة قبل كتلة الأكواد البرمجية]

ستكون النتيجة النهائية كالتالي:

```text
<html>
 <head>
 </head>
</html>
```

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>ملاحظة:</strong> لإنشاء كتل الأكواد البرمجية دون مسافة بادئة للأسطر، استخدم <a href="https://guide.dawin.io/extended-syntax/#fenced-code-blocks">fenced code blocks</a>. التي تحاط بعلامات الفاصلة العليا المائلة (<code>```</code>) أو هذه العلامات (<code>~~~</code>) لتمييزها عن بقية النص.
</div>
