---
title: السطور الأفقية (الفواصل السطرية)
syntax-id: horizontal-rules
syntax-summary: "---"
description: "To create a horizontal rule, use three or more asterisks (`***`), dashes (`---`), or underscores (`___`) on a line by themselves."
examples:
  - markdown: "***"
    html: "<hr>"
  - markdown: "---"
    html: "<hr>"
  - markdown: "_________________"
    html: "<hr>"
---

لإنشاء سطر أفقي، أضف ثلاث أو أكثر من النجمات (`***`)، أو الشرطات (`---`)، أو الشرطات السفلية (`___`)، وتكون أيًا من هذه العلامات على سطر بمفردها.

ستكون النتيجة النهائية متطابقة كالتالي:

---

---

---

### أفضل ممارسات السطر الأفقي

للتوافقية اترك سطرًا فارغًا قبل وبعد السطر الأفقي.

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
  حاول ترك سطر فارغ قبل..<br><br>

---<br><br>

...وسطر آخر بعد السطر الأفقي.
</code>

</td>
<td>
  <code class="highlighter-rouge">
   دون السطر الفارغ، سيُنسّق هذا عنوانًا.<br>
  ---<br>
  لا تفعل هذا!
  </code>
</td>
</tr>
</tbody>
</table>
