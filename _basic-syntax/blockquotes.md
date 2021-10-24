---
title: الاقتباسات
syntax-id: blockquotes
syntax-summary: "> الاقتباسات"
description: "To create a blockquote, add a `>` in front of a paragraph."
examples:
  - markdown: "> Dorothy followed her through many of the beautiful rooms in  her castle."
    html: "<blockquote><p>Dorothy followed her through many of the beautiful rooms in her castle.</p></blockquote>"
additional-examples:
  - name: "Blockquotes with Multiple Paragraphs"
    description: "Blockquotes can contain multiple paragraphs. Add a `>` on the blank lines between the paragraphs."
    markdown: |
      > Dorothy followed her through many of the beautiful rooms in her castle.
      >
      > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
    html: "<blockquote><p>Dorothy followed her through many of the beautiful rooms in her castle.</p><p>The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.</p></blockquote>"
  - name: "Nested Blockquotes"
    description: "Blockquotes can be nested. Add a `>>` in front of the paragraph you want to nest."
    markdown: |
      > Dorothy followed her through many of the beautiful rooms in her castle.
      >
      >> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
    html: "<blockquote><p>Dorothy followed her through many of the beautiful rooms in her castle.</p><blockquote><p>The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.</p></blockquote></blockquote>"
  - name: "Blockquotes with Other Elements"
    description: "Blockquotes can contain other Markdown formatted elements. Not all elements can be used — you'll need to experiment to see which ones work."
    markdown: |
      > ### The quarterly results look great!
      >
      > - Revenue was off the chart.
      > - Profits were higher than ever.
      >
      >  *Everything* is going according to **plan**.
    html: "<blockquote><h3>The quarterly results look great!</h3><ul><li>Revenue was off the chart.</li><li>Profits were higher than ever.</li></ul><p><em>Everything</em> is going according to <strong>plan</strong>.</p></blockquote>"
---

لإنشاء اقتباس، أضف `>` أمام الفقرة.

```
> الأطباء رائعون، ما دمت لا تحتاجهم.
```

ستكون النتيجة النهائية كهذه:

> الأطباء رائعون، ما دمت لا تحتاجهم

### الاقتباسات مع الفقرات المتعددة

يمكن أن تحتوي الاقتباسات على فقرات متعددة. أضف `>` على الأسطر الفارغة بين الفقرات لكي تحسب كتلة اقتباس واحدة.

```
> أمهلني الطبيب ستة أشهر لكي أعيش..
>
> ولكن عندما لم أستطع دفع فاتورة العلاج، أمهلني الطبيب ستة أشهر أخرى.
```

ستكون النتيجة النهائية كالتالي:

> أمهلني الطبيب ستة أشهر لكي أعيش..
>
> ولكن عندما لم أستطع دفع فاتورة العلاج، أمهلني الطبيب ستة أشهر أخرى.

### الاقتباسات المتداخلة

يمكن للاقتباسات أن تكون متداخلة. أضف `>>` أمام الفقرة التي تريد أن تكون متداخلة داخل الفقرة الكبيرة.

قال ناقد الأفلام سعيد الحاج:

> في فيلم Inception تكمن الحبكة في وجود حلم
>
> > داخله حلم آخر.

ستكون النتيجة النهائية كالتالي:

قال ناقد الأفلام سعيد الحاج:

> في فيلم Inception تكمن الحبكة في وجود حلم
>
> > داخله حلم آخر

### الاقتباسات مع العناصر الأخرى

يمكن أن تحتوي الاقتباسات على عناصر ماركداون أخرى منسّقة. لا يمكن استخدام جميع العناصر داخل هذه الاقتباسات، وستحتاج إلى التجربة لمعرفة العناصر التي تعمل.

> #### تبدو النتائج ربع السنوية رائعة!
>
> - الإيرادات كانت مرتفعة.
> - الأرباح غير مسبوقة.
>
>   _كل شيء_ يمضي **على ما يرام**.

ستكون النتيجة النهائية كالتالي:
كل شيء يمضي على ما يرام.

> <h4 class="no-anchor">تبدو النتائج ربع السنوية رائعة!</h4>
>
> - الإيرادات كانت مرتفعة.
> - الأرباح غير مسبوقة.
>
> _كل شيء_ يمضي **على ما يرام**.

### أفضل ممارسات الاقتباسات

للتوافقية، ضع أسطرًا فارغة قبل وبعد الاقتباس.

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
حاول أن تترك سطرًا فارغًا قبل الاقتباس..<br><br>
 
> هنا يقع الاقتباس<br><br>
 
وسطرًا فارغًا بعد الاقتباس...
</code>
 
</td>
<td>
<code class="highlighter-rouge">
دون أي سطر فارغ، قد لا يبدو التنسيق صحيحًا.<br>
> هنا يقع الاقتباس<br>
لا تفعل هذا!
</code>
</td>
</tr>
</tbody>
</table>
