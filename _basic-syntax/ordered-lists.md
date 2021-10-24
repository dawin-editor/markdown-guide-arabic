---
title: القوائم المرقّمة (المرتّبة)
syntax-id: ordered-lists
syntax-summary: |
  1. First item
  2. Second item
  3. Third item
description: "To create an ordered list, add line items with numbers followed by periods. The numbers don't have to be in numerical order, but the list should start with the number one."
examples:
  - markdown: |
      1. First item
      2. Second item
      3. Third item
      4. Fourth item
    html: <ol><li>First item</li><li>Second item</li><li>Third item</li><li>Fourth item</li></ol>
  - markdown: |
      1. First item
      1. Second item
      1. Third item
      1. Fourth item
    html: <ol><li>First item</li><li>Second item</li><li>Third item</li><li>Fourth item</li></ol>
  - markdown: |
      1. First item
      8. Second item
      3. Third item
      5. Fourth item
    html: <ol><li>First item</li><li>Second item</li><li>Third item</li><li>Fourth item</li></ol>
  - markdown: |
      1. First item
      2. Second item
      3. Third item
        1. Indented item
        2. Indented item
      4. Fourth item
    html: <ol><li>First item</li><li>Second item</li><li>Third item<ol><li>Indented item</li><li>Indented item</li></ol></li><li>Fourth item</li></ol>
---

لإنشاء قائمة مرقّمة، أضف أرقام العناصر متبوعة بنقاط. لا يجب أن تكون الأرقام بالترتيب العددي، ولكن يجب أن تبدأ القائمة بالرقم "واحد".

بمعنى آخر، يمكن أن تبدأ بأي عدد فتكون الأعداد مستمرة من النقطة التي بدأت فيها؛ ويعني هذا أنك إذا بدأت من العدد "ثلاثة"، ثم أكملت القائمة، فستكون النتيحة النهائية تبدأ من العدد ثلاثة: 3. 4. 5. وهكذا.

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
        1. العنصر الأول<br/>
        2. العنصر الثاني<br/>
        3. العنصر الثالث<br/>
        4. العنصر الرابع
      </code>
    </td>
    <td style="direction:ltr; text-align: left">
      <code class="highlighter-rouge">
        &lt;ol&gt;<br>
          &lt;li&gt;العنصر الأول&lt;/li&gt;<br/>
          &lt;li&gt;العنصر الثاني&lt;/li&gt;<br/>
          &lt;li&gt;العنصر الثالث&lt;/li&gt;<br/>
          &lt;li&gt;العنصر الرابع&lt;/li&gt;<br/>
        &lt;/ol&gt;
      </code>
    </td>
    <td>
      <ol>
        <li>العنصر الأول</li>
        <li>العنصر الثاني</li>
        <li>العنصر الثالث</li>
        <li>العنصر الرابع</li>
      </ol>
    </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          1. العنصر الأول<br/>
          1. العنصر الثاني<br/>
          1. العنصر الثالث<br/>
          1. العنصر الرابع
        </code>
      </td>
      <td style="direction:ltr; text-align: left">
        <code class="highlighter-rouge">
          &lt;ol&gt;<br>
            &lt;li&gt;العنصر الأول&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثاني&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثالث&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الرابع&lt;/li&gt;<br/>
          &lt;/ol&gt;
        </code>
      </td>
      <td>
        <ol>
          <li>العنصر الأول</li>
          <li>العنصر الثاني</li>
          <li>العنصر الثالث</li>
          <li>العنصر الرابع</li>
        </ol>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          1. العنصر الأول<br/>
          8. العنصر الثاني<br/>
          3. العنصر الثالث<br/>
          5. العنصر الرابع
        </code>
      </td>
      <td style="direction:ltr; text-align: left">
        <code class="highlighter-rouge">
          &lt;ol&gt;<br>
            &lt;li&gt;العنصر الأول&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثاني&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثالث&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الرابع&lt;/li&gt;<br/>
          &lt;/ol&gt;
        </code>
      </td>
      <td>
        <ol>
          <li>العنصر الأول</li>
          <li>العنصر الثاني</li>
          <li>العنصر الثالث</li>
          <li>العنصر الرابع</li>
        </ol>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          1. العنصر الأول<br/>
          2. العنصر الثاني<br/>
          3. العنصر الثالث<br/>
          &nbsp;&nbsp;&nbsp;&nbsp;1. عنصر فرعي<br/>
          &nbsp;&nbsp;&nbsp;&nbsp;2. عنصر فرعي آخر<br/>
          4. العنصر الرابع
        </code>
      </td>
      <td style="direction:ltr; text-align: left">
        <code class="highlighter-rouge">
          &lt;ol&gt;<br>
            &lt;li&gt;العنصر الأول&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثاني&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثالث<br/>
              &lt;ol&gt;<br>
                &lt;li&gt;عنصر فرعي&lt;/li&gt;<br/>
                &lt;li&gt;عنصر فرعي آخر&lt;/li&gt;<br/>
              &lt;/ol&gt;<br/>
            &lt;/li&gt;<br/>
            &lt;li&gt;العنصر الرابع&lt;/li&gt;<br/>
          &lt;/ol&gt;
        </code>
      </td>
      <td>
        <ol>
          <li>العنصر الأول</li>
          <li>العنصر الثاني</li>
          <li>العنصر الثالث
            <ol>
              <li>عنصر فرعي</li>
              <li>عنصر فرعي آخر</li>
            </ol>
          </li>
          <li>العنصر الرابع</li>
        </ol>
      </td>
    </tr>
  </tbody>
</table>

#### أفضل ممارسات القوائم المرتّبة (المرقّمة)

تتيح لك CommonMark وبعض لغات الترميز الخفيفة الأخرى استخدام القوس "`)`" محددًا بعد العدد بدلًا عن النقطة مثلًا "`1) العنصر الأول`"، ولكن لا تدعم جميع تطبيقات ماركداون هذا الخيار، لذا فهو ليس خيارًا جيدًا من منظور التوافقية. لذلك، استخدم النقاط فقط.

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
          1. العنصر الأول<br>
          2. العنصر الثاني
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          1) العنصر الأول<br>
          2) العنصر الثاني
        </code>
      </td>
    </tr>
  </tbody>
</table>
