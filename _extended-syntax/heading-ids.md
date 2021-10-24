---
title: معرفّات العنوان
syntax-id: heading-ids
syntax-summary: "### My Great Heading {#custom-id}"
---

تدعم العديد من معالجات ماركداون المعّرفات المخصّصة [للعناوين](https://guide.dawin.io/basic-syntax/#headings)، تضيف بعض معالجات ماركداون هذه المعرّفات تلقائيًا. تتيح لك إضافة معرفات مخصّصة الارتباط مباشرة بالعناوين وتعديلها باستخدام CSS. لإضافة معرّف عنوان مخصّص، أحِط المعّرف المخصّص بأقواس هلالية على نفس سطر العنوان.

```text
### عنواني الرائع (#معرف-خاص)
```

سيظهر تنسيق HTML كما يلي:

```html
<h3 id="معرف-خاص">‎عنواني الخاص</h3>
```

### الربط بمعرّفات العناوين

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
      <td><code class="highlighter-rouge">[العنوان](#معرف-العنوان)</code></td>
      <td><code class="highlighter-rouge"> &lt;a href="#معرف-العنوان"&gt;العنوان‎&lt;/a&gt;</code></td>
      <td><a href="#heading-ids">العنوان</a></td>
    </tr>
  </tbody>
</table>

تستطيع بعض المواقع ربط العنوان بإضافة معرف العنوان إلى الرابط الكامل للصفحة. مثلا، [العنوان](https://guide.dawin.io/extended-syntax#معرف-العنوان).
