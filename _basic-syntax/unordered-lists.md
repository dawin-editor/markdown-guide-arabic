---
title: القوائم المنقّطة (غير المرتّبة)
syntax-id: unordered-lists
syntax-summary: |
  - First item
  - Second item
  - Third item
description: "To create an unordered list, add dashes (`-`), asterisks (`*`), or plus signs (`+`) in front of line items. Indent one or more items to create a nested list."
examples:
  - markdown: |
      - First item
      - Second item
      - Third item
      - Fourth item
    html: <ul><li>First item</li><li>Second item</li><li>Third item</li><li>Fourth item</li></ul>
  - markdown: |
      * First item
      * Second item
      * Third item
      * Fourth item
    html: <ul><li>First item</li><li>Second item</li><li>Third item</li><li>Fourth item</li></ul>
  - markdown: |
      + First item
      * Second item
      - Third item
      + Fourth item
    html: <ul><li>First item</li><li>Second item</li><li>Third item</li><li>Fourth item</li></ul>
  - markdown: |
      - First item
      - Second item
      - Third item
          - Indented item
          - Indented item
      - Fourth item
    html: <ul><li>First item</li><li>Second item</li><li>Third item<ul><li>Indented item</li><li>Indented item</li></ul></li><li>Fourth item</li></ul>
---

لإنشاء قائمة منقّطة، أضف الشرطات (`-`) أو النجمات (`*`) أو علامات الجمع (`+`) أمام عناصر السطر. أضف مسافة بادئة أمام العنصر أو العناصر الفرعية لإنشاء قائمة متداخلة.

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
          - العنصر الأول<br/>
          - العنصر الثاني<br/>
          - العنصر الثالث<br/>
          - العنصر الرابع
        </code>
      </td>
      <td style="direction:ltr; text-align: left">
        <code class="highlighter-rouge">
          &lt;ul&gt;<br>
            &lt;li&gt;العنصر الأول&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثاني&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثالث&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الرابع&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>العنصر الأول</li>
          <li>العنصر الثاني</li>
          <li>العنصر الثالث</li>
          <li>العنصر الرابع</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          * العنصر الأول<br/>
          * العنصر الثاني<br>
          * العنصر الثالث<br/>
          * العنصر الرابع
        </code>
      </td>
      <td style="direction:ltr; text-align: left">
        <code class="highlighter-rouge">
          &lt;ul&gt;<br>
            &lt;li&gt;العنصر الأول&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثاني&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثالث&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الرابع&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>العنصر الأول</li>
          <li>العنصر الثاني</li>
          <li>العنصر الثالث</li>
          <li>العنصر الرابع</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          + العنصر الأول<br/>
          + العنصر الثاني<br/>
          + العنصر الثالث<br/>
          + العنصر الرابع
        </code>
      </td>
      <td style="direction:ltr; text-align: left">
        <code class="highlighter-rouge">
          &lt;ul&gt;<br>
            &lt;li&gt;العنصر الأول&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثاني&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثالث&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الرابع&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>العنصر الأول</li>
          <li>العنصر الثاني</li>
          <li>العنصر الثالث</li>
          <li>العنصر الرابع</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <code class="highlighter-rouge">
          - العنصر الأول<br/>
          - العنصر الثاني<br/>
          - العنصر الثالث<br/>
          &nbsp;&nbsp;&nbsp;&nbsp;- عنصر فرعي<br/>
          &nbsp;&nbsp;&nbsp;&nbsp;- عنصر فرعي آخر<br/>
          - العنصر الرابع
        </code>
      </td>
      <td style="direction:ltr; text-align: left">
        <code class="highlighter-rouge">
          &lt;ul&gt;<br/>
            &lt;li&gt;العنصر الأول&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثاني&lt;/li&gt;<br/>
            &lt;li&gt;العنصر الثالث<br/>
              &lt;ul&gt;<br/>
                &lt;li&gt;عنصر فرعي&lt;/li&gt;<br/>
                &lt;li&gt;عنصر فرعي آخر&lt;/li&gt;<br/>
              &lt;/ul&gt;<br/>
            &lt;/li&gt;<br/>
            &lt;li&gt;العنصر الرابع&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>العنصر الأول</li>
          <li>العنصر الثاني</li>
          <li>العنصر الثالث
            <ul>
              <li>عنصر فرعي</li>
              <li>عنصر فرعي آخر</li>
            </ul>
          </li>
          <li>العنصر الرابع</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

#### بدء عناصر القائمة المنقّطة بالأرقام

إذا كنت بحاجة إلى بدء عنصر قائمة منقّطة برقم متبوعًا بنقطة (دون أن تُعالَج كأنّها قائمة مرقّمة)، فيمكنك استخدام شرطة مائلة للخلف (`\`) [لتخطي](https://guide.dawin.io/basic-syntax/#escaping-characters) النقطة.

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
          - 1962\. ما أجمله من عام!<br/>
          - أزعم أن عام 1963 كان ثاني الأعوام روعة.
        </code>
      </td>
      <td style="direction:ltr; text-align: left">
        <code class="highlighter-rouge">
          &lt;ul&gt;<br>
            &lt;li&gt;1962. ما أجمله من عام!&lt;/li&gt;<br/>
            &lt;li&gt;أزعم أن عام 1963 كان ثاني الأعوام روعة.&lt;/li&gt;<br/>
          &lt;/ul&gt;
        </code>
      </td>
      <td>
        <ul>
          <li>1962. ما أجمله من عام!</li>
          <li>أزعم أن عام 1963 كان ثاني الأعوام روعة.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

#### أفضل ممارسات القوائم المنقطة

لا تتفق تطبيقات ماركداون على كيفية التعامل مع المحدّدات المختلفة (كالنجمة والشرطة ونحوهما) في نفس القائمة. للتوافقية، لا تخلط المحددات في نفس القائمة، بل اختر واحدة والتزم بها. <table class="table table-bordered">

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
          - العنصر الأول<br>
          - العنصر الثاني<br>
          - العنصر الثالث<br>
          - العنصر الرابع
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          + العنصر الأول<br>
          * العنصر الثاني<br>
          - العنصر الثالث<br>
          + العنصر الرابع
        </code>
      </td>
    </tr>
  </tbody>
</table>
