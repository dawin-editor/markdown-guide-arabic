---
title: فواصل الأسطر
syntax-id: line-breaks
description: "To create a line break (`<br>`), end a line with two or more spaces, and then type return."
examples:
  - markdown: |
      This is the first line.  
      And this is the second line.
    html: "<p>This is the first line.  <br>And this is the second line.</p>"
---

لإنشاء فاصل أسطر (`<br>`)، انقر على زر المسافة مرتين أو أكثر في نهاية السطر، ثم انتقل للسطر الجديد بالنقر على زر الرجوع للسطر Enter/Return.

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
هذا هو السطر الأول.&nbsp;<br />
وهذا السطر الثاني.
</code>
</td>
<td>
<code class="highlighter-rouge">&lt;p&gt;هذا هو السطر الأول.&lt;br&gt;<br />

وهذا السطر الثاني.&lt;/p&gt;</code>

</td>
<td>
<p>هذا هو السطر الأول.
<br />
وهذا السطر الثاني.</p>
</td>
</tr>
</tbody>
</table>

### أفضل ممارسات فواصل الأسطر

يمكنك استخدام مسافتين أو أكثر (يشار إليها عادةً باسم "المسافة البيضاء الزائدة") لفواصل الأسطر في كل تطبيق ماركداون تقريبًا، ولكنها مسألة خلافية. من الصعب رؤية مسافة بيضاء زائدة في المحرر، وقد يضع العديد من الأشخاص مسافتين عن طريق الخطأ أو عن قصد بعد كل جملة. لهذا السبب، قد ترغب في استخدام شيء آخر غير المسافة البيضاء الزائدة لفواصل الأسطر. إذا كان تطبيق ماركداون الذي تستخدمه [يدعم HTML](https://guide.dawin.io/basic-syntax/#html)، فيمكنك استخدام علامة `<br>` لفواصل الأسطر المستخدمة في HTML.

للتوافقية، استخدم مسافة بيضاء زائدة أو علامة `<br>` الخاصة بـ HTML في نهاية السطر.

هناك خياران آخران لا أوصي باستخدامهما. تتيح لك CommonMark وبعض لغات الترميز الخفيفة الأخرى كتابة شرطة مائلة للخلف (`\`) في نهاية السطر، ولكن لا تدعم جميع تطبيقات ماركداون هذا الخيار، لذا فهو ليس خيارًا جيدًا من ناحية التوافقية. وهناك تنويعتا ماركداون على الأقل لا تتطلبان أي شيء في نهاية السطر؛ فبمجرد نقر Enter/Return سيُنشأ فاصل سطر.

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
السطر الأول مع مسافتين في آخر السطر. &nbsp;<br>
ثم السطر الثاني.<br><br>

السطر الأول مع عنصر HTML الخاص بفاصل الأسطر&lt;br&gt;<br>
ثم السطر الثاني.<br><br>
</code>

</td>
<td>
<code class="highlighter-rouge">
السطر الأول مع شرطة مائلة للخلف.\<br>
ثم السطر الثاني.<br><br>

السطر الأول ولا شيء بعده.<br>
ثم السطر الثاني.<br><br>
</code>

</td>
</tr>
</tbody>
</table>
