---
title: سُمْك النص
syntax-id: bold
syntax-summary: "**bold text**"
description: "To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters."
examples:
  - markdown: "I just love **bold text**."
    html: "I just love <strong>bold text</strong>."
  - markdown: "I just love __bold text__."
    html: "I just love <strong>bold text</strong>."
  - markdown: "Love**is**bold"
    html: "Love<strong>is</strong>bold"
---

لزيادة سمك النص، أضف نجمتين (`**`) أو شرطة سفلية (`_`) قبل وبعد الكلمة أو العبارة. ولزيادة سُمْكِ منتصف الكلمة لتأكيدها، أضف نجمتين دون مسافاتٍ حول الأحرف.

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
      <td><code class="highlighter-rouge">أحب **النص السميك**.</code></td>
      <td><code class="highlighter-rouge">أحب &lt;strong&gt;النص السميك&lt;/strong&gt;.</code></td>
      <td>أحب <strong>النص السميك</strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">أحب __النص السميك__.</code></td>
      <td><code class="highlighter-rouge">أحب &lt;strong&gt;النص السميك&lt;/strong&gt;.</code></td>
      <td>أحب <strong>النص السميك</strong>.</td>
    </tr>
    <tr>
      <td>
      <code class="highlighter-rouge">ضبط اسم ابن **خَلْ**دون صاحب المقدمة بفتح الخاء فتسكين اللام.
    </code>
</td> <td><code class="highlighter-rouge">ضبط اسم ابن &lt;strong&gt;خَلْ&lt;/strong&gt;دون صاحب المقدمة بفتح الخاء فتسكين اللام.
</code></td>
      <td>ضبط اسم ابن <strong>خَلْ</strong>دون صاحب المقدمة بفتح الخاء فتسكين اللام.
</td>
    </tr>
  </tbody>
</table>

#### أفضل ممارسات لِسُمْكِ النص

لا تتفق تطبيقات ماركداون على كيفية التعامل مع الشرطة السفلية (`_`) في وسط الكلمة. للتوافقية، استخدم النجمة (`*`) لزيادة سُمْكِ وسط الكلمة لتأكيدها.

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
         لاحظ الرَّوم والإشمام في قوله تعالى:"مَا لَكَ لَا تَأْمَ**نَّ**ا عَلَى يُوسُفَ"
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          لاحظ الرَّوم والإشمام في قوله تعالى:"مَا لَكَ لَا تَأْمَ__نَّ__ا عَلَى يُوسُفَ"
        </code>
      </td>
    </tr>
  </tbody>
</table>
