---
title: التأكيد
syntax-id: emphasis
api: "no"
---

يمكنك إضافة تأكيد النص بجعله سميك أو مائل.
{% include syntax.html type="basic-sub" syntax-id="bold" %}

{% include syntax.html type="basic-sub" syntax-id="italic" %}

### زيادة سُمكِ النص وإمالته معًا

لتأكيد النص بتسميكه وإمالته في نفس الوقت، أضف ثلاث نجمات (`***`) أو ثلاث شرطات سفلية (`___`) قبل وبعد الكلمة أو العبارة. وكذلك لإمالة وزيادة سُمْكِ جزء من النص أو العبارة، أضف ثلاث نجمات دون مسافات حول الأحرف.

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
      <td><code class="highlighter-rouge">هذا النص ***مهم جدًا***.</code></td>
      <td><code class="highlighter-rouge">هذا النص &lt;strong&gt;&lt;em&gt;مهم جدًا&lt;/em&gt;&lt;/strong&gt;.</code></td>
      <td>هذا النص <strong><em>مهم جدًا</em></strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">هذا النص ___مهم جدًا___.</code></td>
      <td><code class="highlighter-rouge">هذا النص &lt;strong&gt;&lt;em&gt;مهم جدًا&lt;/em&gt;&lt;/strong&gt;.</code></td>
      <td>هذا النص <strong><em>مهم جدًا</em></strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">هذا النص __*مهم جدًا*__.</code></td>
      <td><code class="highlighter-rouge">هذا النص &lt;strong&gt;&lt;em&gt;مهم جدًا&lt;/em&gt;&lt;/strong&gt;.</code></td>
      <td>هذا النص <strong><em>مهم جدًا</em></strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">هذا النص **_مهم جدًا_**.</code></td>
      <td><code class="highlighter-rouge">هذا النص &lt;strong&gt;&lt;em&gt;مهم جدًا&lt;/em&gt;&lt;/strong&gt;.</code></td>
      <td>هذا النص <strong><em>مهم جدًا</em></strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">في قوله تعالى: "فأسقينا***ك****موه" تعرب الكاف أنها ضمير متصل في محل نصب مفعول به.</code></td>
      <td><code class="highlighter-rouge">في قوله تعالى: "فأسقينا&lt;strong&gt;&lt;em&gt;ك&lt;/em&gt;&lt;/strong&gt;موه" تعرب الكاف أنها ضمير متصل في محل نصب مفعول به.
</code></td>
      <td>في قوله تعالى: "فأسقينا<strong><em>ك</em></strong>موه" تعرب الكاف أنها ضمير متصل في محل نصب مفعول به.
</td>
    </tr>
  </tbody>
</table>

#### أفضل الممارسات لزيادة سمك النص وإمالته

لا تتفق تطبيقات ماركداون على كيفية التعامل مع الشرطة السفلية (`_`) في وسط الكلمة. للتوافقية، استخدم النجمة (`*`) وسط الكلمة للإمالة وزيادة السُمك لتأكيدها.

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
         في المثال: "أعطي***ت***ك القلم"، نجد أن إعراب التاء في أعطيتك هو ضمير متصل في محل رفع فاعل.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
         في المثال: "أعطي___ت___ك القلم"، نجد أن إعراب التاء في أعطيتك هو ضمير متصل في محل رفع فاعل.
        </code>
      </td>
    </tr>
  </tbody>
</table>
