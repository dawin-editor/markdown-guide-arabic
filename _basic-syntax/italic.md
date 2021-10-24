---
title: إمالة النص
syntax-id: italic
syntax-summary: "*italicized text*"
description: "To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters."
examples:
  - markdown: "Italicized text is the *cat's meow*."
    html: "Italicized text is the <em>cat's meow</em>."
  - markdown: "Italicized text is the _cat's meow_."
    html: "Italicized text is the <em>cat's meow</em>."
  - markdown: "A*cat*meow"
    html: "A<em>cat</em>meow"
---

لإمالة النص، أضف نجمة واحدة (`*`) أو شرطة سفلية واحدة (`_`) قبل وبعد الكلمة أو العبارة المراد إمالتها. لإمالة وسط الكلمة لتأكيدها، أضف نجمة واحدة (`*`) بدون مسافات حول الأحرف، بنفس طريقة سُمْكِ النص بالأعلى.

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
      <td><code class="highlighter-rouge">هذا النص فيه *جزء مائل*.</code></td>
      <td><code class="highlighter-rouge">هذا النص فيه &lt;em&gt;جزء مائل&lt;/em&gt;.</code></td>
      <td>هذا النص فيه <em>جزء مائل</em>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">هذا النص فيه _جزء مائل_.</code></td>
      <td><code class="highlighter-rouge">هذا النص فيه &lt;em&gt;جزء مائل&lt;/em&gt;.</code></td>
      <td>هذا النص فيه <em>جزء مائل</em>.</td>
    </tr>
    <tr>
      <td>
      <code class="highlighter-rouge">ضبط اسم *سِيْ*بويه النحوي المعروف بكسر السين فتسكين الياء.
      </code>
      </td>
      <td><code class="highlighter-rouge">ضبط اسم &lt;em&gt;سِيْ&lt;/em&gt;ويه النحوي المعروف بكسر السين فتسكين الياء.</code></td>
      <td>ضبط اسم <em>سِيْ</em>ويه النحوي المعروف بكسر السين فتسكين الياء.</td>
    </tr>
  </tbody>
</table>

#### أفضل ممارسات إمالة النص

لا تتفق تطبيقات ماركداون على كيفية التعامل مع الشرطة السفلية (`_`) في وسط الكلمة. للتوافقية، استخدم النجمة (`*`) وسط الكلمة لإمالة الكلمة لتأكيدها.

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
         لاحظ الإمالة في قوله تعالى: "بسم الله مجر*ا*ها ومرساها".
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          لاحظ الإمالة في قوله تعالى: "بسم الله مجر_ا_ها ومرساها".
        </code>
      </td>
    </tr>
  </tbody>
</table>
