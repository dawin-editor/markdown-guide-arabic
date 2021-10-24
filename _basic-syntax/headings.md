---
title: العناوين
syntax-id: headings
syntax-summary: |
  # H1
  ## H2
  ### H3
description: "To create a heading, add number signs (`#`) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level three (`<h3>`), use three number signs (e.g., `### My Header`)."
examples:
  - markdown: "# Heading level 1"
    html: "<h1>Heading level 1</h1>"
  - markdown: "## Heading level 2"
    html: "<h2>Heading level 2</h2>"
  - markdown: "### Heading level 3"
    html: "<h3>Heading level 3</h3>"
  - markdown: "#### Heading level 4"
    html: "<h4>Heading level 4</h4>"
  - markdown: "##### Heading level 5"
    html: "<h5>Heading level 5</h5>"
  - markdown: "###### Heading level 6"
    html: "<h6>Heading level 6</h6>"
additional-examples:
  - name: "Alternative H1 Syntax"
    description: "Alternatively, on the line below the text, add any number of == characters for heading level 1."
    markdown: |
      Heading level 1
      ===============
    html: "<h1>Heading level 1</h1>"
  - name: "Alternative H2 Syntax"
    description: "Alternatively, on the line below the text, add any number of -- characters for heading level 2."
    markdown: |
      Heading level 2
      ---------------
    html: "<h2>Heading level 2</h2>"
---

لإنشاء عنوان، أضف علامة المربع (#) أمام الكلمة أو العبارة التي تريد تنسيقها عنوانًا. يجب أن يتوافق عدد علامات المربع التي تستخدمها مع مستوى العنوان. مثلًا، لإنشاء عنوان من المستوى الثالث (<h3>)، استخدم ثلاث علامات مربع (مثلًا، ### هذا العنوان من المستوى الثالث).

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
          <code class="highlighter-rouge">## عنوان من المستوى الأول</code>
        </td>
        <td><code class="highlighter-rouge">&lt;h1&gt;عنوان من المستوى الأول&lt;/h1&gt;</code></td>
        <td>
          <h1 class="no-anchor" data-toc-skip>عنوان من المستوى الأول</h1>
        </td>
      </tr>
      <tr>
        <td><code class="highlighter-rouge">## عنوان من المستوى الثاني</code></td>
        <td><code class="highlighter-rouge">&lt;h2&gt;عنوان من المستوى الثاني&lt;/h2&gt;</code></td>
        <td><h2 class="no-anchor" data-toc-skip>عنوان من المستوى الثاني</h2></td>
      </tr>
      <tr>
        <td><code class="highlighter-rouge">### عنوان من المستوى الثالث</code></td>
        <td><code class="highlighter-rouge">&lt;h3&gt;عنوان من المستوى الثالث&lt;/h3&gt;</code></td>
        <td><h3 class="no-anchor" data-toc-skip>عنوان من المستوى الثالث</h3></td>
      </tr>
      <tr>
        <td><code class="highlighter-rouge">#### عنوان من المستوى الرابع</code></td>
        <td><code class="highlighter-rouge">&lt;h4&gt;عنوان من المستوى الرابع&lt;/h4&gt;</code></td>
        <td><h4 class="no-anchor">عنوان من المستوى الرابع</h4></td>
      </tr>
      <tr>
        <td><code class="highlighter-rouge">##### عنوان من المستوى الخامس</code></td>
        <td><code class="highlighter-rouge">&lt;h5&gt;عنوان من المستوى الخامس&lt;/h5&gt;</code></td>
        <td><h5 class="no-anchor">عنوان من المستوى الخامس</h5></td>
      </tr>
      <tr>
        <td><code class="highlighter-rouge">###### عنوان من المستوى السادس</code></td>
        <td><code class="highlighter-rouge">&lt;h6&gt;عنوان من المستوى السادس&lt;/h6&gt;</code></td>
        <td><h6 class="no-anchor">عنوان من المستوى السادس</h6></td>
      </tr>
    </tbody>
  </table>

### قاعدة بديلة

بدلاً من ذلك، في السطر الموجود أسفل النص (المراد تنسيقه عنوانًا)، أضف أي عدد من الأحرف "===" لعنوان من المستوى الأول، أو أحرف الشرطة "---" لعنوان من المستوى الثاني.

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
      <td><code class="highlighter-rouge">عنوان من المستوى الأول<br/>===============</code></td>
      <td><code class="highlighter-rouge">&lt;h1&gt;عنوان من المستوى الأول&lt;/h1&gt;</code></td>
      <td><h1 class="no-anchor" data-toc-skip>عنوان من المستوى الأول</h1></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">عنوان من المستوى الثاني<br/>---------------</code></td>
      <td><code class="highlighter-rouge">&lt;h2&gt;عنوان من المستوى الثاني&lt;/h2&gt;</code></td>
      <td><h2 class="no-anchor" data-toc-skip>عنوان من المستوى الثاني</h2></td>
    </tr>
  </tbody>
</table>

### أفضل الممارسات لكتابة العناوين

لا تتفق تطبيقات ماركداون على كيفية التعامل مع المسافة الموضوعة بين علامات المربع (#) ونص العنوان. للتوافق مع كل هذه التطبيقات، ضع دائمًا مسافة بين علامات المربع (#) ونص العنوان.

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
          # هذا عنوان<br><br>
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          #هذا عنوان
        </code>
      </td>
    </tr>
  </tbody>
</table>

يجب أيضًا ترك أسطر فارغة قبل العنوان وبعده للتوافقية (لضمان صحة التنسيق في كل البرامج).

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
  <pre>
حاول ترك أسطر فارغة قبل العنوان.. <br />

العنوان #

...وكذلك بعد العنوان.

</pre>
</td>

<td>
<pre>
دون الأسطر الفارغة قبل العنوان وبعده، قد لا يبدو التنسيق صحيحًا.

العنوان #
إياك أن تفعل هذا!

</pre>
</td>
</tr>
  </tbody>
</table>
