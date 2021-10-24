---
title: الروابط
syntax-id: links
syntax-summary: "[link name](https://www.example.com)"
description: "To create a link, enclose the link text in brackets (e.g., `[Duck Duck Go]`) and then follow it immediately with the URL in parentheses (e.g., `(https://duckduckgo.com)`). You can optionally add a title after the URL in the parentheses."
examples:
  - markdown: 'My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").'
    html: My favorite search engine is <a href=\"https://duckduckgo.com\" title=\"The best search engine for privacy\">Duck Duck Go</a>.
additional-examples:
  - name: "URLs and Email Addresses"
    description: "To quickly turn a URL or email address into a link, enclose it in angle brackets."
    markdown: "<https://www.guide.dawin.io><fake@example.com>"
    html: <a href=\"https://www.guide.dawin.io\">https://www.guide.dawin.io</a><a href=\"&#x6d;&#97;&#105;&#x6c;&#116;&#x6f;&#58;&#x66;&#x61;&#x6b;&#101;&#64;&#x65;&#120;&#x61;&#x6d;&#x70;&#108;&#101;&#46;&#99;&#x6f;&#109;\">&#x66;&#x61;&#x6b;&#101;&#64;&#x65;&#120;&#x61;&#x6d;&#x70;&#108;&#101;&#46;&#99;&#x6f;&#109;</a>
  - name: "Formatting Links"
    description: "To emphasize links, add asterisks before and after the brackets and parentheses."
    markdown: "I love supporting **[EFF](https://eff.org)**. This is the *[Markdown Guide](https://www.guide.dawin.io)*."
    html: I love supporting <strong><a href=\"https://eff.org\">EFF</a></strong>. This is the <em><a href=\"https://www.guide.dawin.io\">Markdown Guide</a></em>.
---

لإنشاء رابط، ضع نص الرابط بين قوسين. مثلًا، `[Google]` ثم أتبعه فورًا بالرابط الفعلي بين قوسين `(https://google.com)`.

```
محرك البحث المفضل لديّ هو [Google]‏(https://google.com)
```

ستكون النتيجة النهائية كالتالي:
محرك البحث المفضل لديّ هو [Google](https://www.google.com).

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>ملاحظة:</strong>  لإنشاء رابط يصل بعنصر في نفس الصفحة، طالع <a href="https://guide.dawin.io/extended-syntax/#linking-to-heading-ids">الارتباط مع معرفات العناوين</a>.
</div>

### إضافة العناوين (للروابط)

يمكنك اختياريًا إضافة عنوان للرابط. سيظهر هذا تلميحًا (Tooltip) عندما يحوم مؤشر الماوس على الرابط (Hover). لإضافة عنوان، ضَمّنه بين قوسين بعد الرابط.

```
محرك البحث المفضل لديّ هو [Google](http://google.com "أشهر محركات البحث على الإطلاق").
```

ستكون النتيجة النهائية كالتالي:
محرك البحث المفضل لديّ هو [Google](http://google.com "أشهر محركات البحث على الإطلاق").

### الروابط وعناوين البريد الإلكتروني

لأجل التحويل السريع لمسار ويب أو عنوان بريد إلكتروني إلى رابط، ضمّنه بين قوسي زاوية (`<>`).
<https://guide.dawin.io>
<fake@example.com>
ستكون النتيجة النهائية كالتالي:
​​<https://guide.dawin.io><br/>
<fake@example.com>

### تنسيق الروابط

[للتأكيد](https://guide.dawin.io/basic-syntax/#emphasis) على الروابط (بإمالة الخط أو زيادة سُمْكِه)، أضف النجمات قبل الأقواس وبعدها. لتنسيق الروابط [كالأكواد](https://guide.dawin.io/basic-syntax/#code)، أضف الفاصلة العليا المائلة (Backticks) بين القوسين المربعين.

```
أحب هذا الموقع **[EFF](https://eff.org)**.<br/>
هذا هو *[دليل ماركداون](https://guide.dawin.io)*.<br/>
راجع قسم [`الكود البرمجي`](#code).
```

ستكون النتيجة النهائية كالتالي:
أحب هذا الموقع **[EFF](https://eff.org)**.<br/>
هذا هو _[دليل ماركداون](https://guide.dawin.io)_.<br/>
راجع قسم [`الكود البرمجي`](#code).

### الروابط ذات الأسلوب المرجعي

الروابط ذات الأسلوب المرجعي هي نوع خاص من الروابط التي تجعل الروابط أسهل في العرض والقراءة في ماركداون. تُنشأ هذه الروابط في جزأين: الجزء الذي تحافظ عليه متسقًا مع النص، والجزء الذي تخزّنه في مكان آخر في الملف للحفاظ على سهولة قراءة النص.

#### تنسيق الجزء الأول من الرابط

يُنسّق الجزء الأول من الروابط ذات الأسلوب المرجعي بمجموعتين من الأقواس المربعة. المجموعة الأولى من الأقواس تحيط بالنص الظاهر، وتعرض المجموعة الثانية من الأقواس مؤشرًا للرابط الذي المخزّن في مكان آخر في المستند.
وإن لم يكن مطلوبًا، يمكنك تضمين مسافة بين المجموعة الأولى والثانية من الأقواس المربعة.

التسمية الموجودة في المجموعة الثانية من الأقواس (التي تشير للرابط الأصلي الموجود في مكان ما على المستند) ليست حسّاسة لحالة الأحرف (الكبيرة والصغيرة في الأحرف اللاتينية) ويمكن أن تتضمن أحرفًا أو أرقامًا أو مسافات أو علامات ترقيم.
هذا يعني أن تنسيقات المثالَين التالِيَين متكافئة من ناحية الجزء الأول من الرابط:
• `[محرر دوّن][1]`
• `[محرر دوّن] [1]`

#### تنسيق الجزء الثاني من الرابط

يُنسّق الجزء الثاني من الروابط ذات الأسلوب المرجعي بالِسمَات الآتية:

1. التسمية، بين قوسين مربعين، متبوعة مباشرة بنقطتين ومسافة واحدة على الأقل. مثلًا، "`[مثال على التسمية]: `".
2. الرابط، والذي يمكنك (اختياريًا) وضعه بين قوسي زاوية.
3. العنوان الاختياري للرابط، والذي يمكن تضمينه بين علاماتي اقتباس مزدوجة "" أو مفردة '' أو قوسين ().

هذا يعني أن تنسيقات الأمثلة التالية جميعها مكافئة تقريبًا للجزء الثاني من الرابط:

- `[1]: https://www.dawin.io/`
- `[1]: https://www.dawin.io/ "اكتب وحرّر مستنداتك بحروف عربية"`
- `[1]: https://www.dawin.io/ 'اكتب وحرّر مستنداتك بحروف عربية'`
- `[1]: https://www.dawin.io/ (اكتب وحرّر مستنداتك بحروف عربية)`
- `[1]: <https://www.dawin.io/> "اكتب وحرّر مستنداتك بحروف عربية"`
- `[1]: <https://www.dawin.io/> 'اكتب وحرّر مستنداتك بحروف عربية'`
- `[1]: <https://www.dawin.io/> (اكتب وحرّر مستنداتك بحروف عربية)`

بإمكانك وضع هذا الجزء الثاني من الرابط في أي مكان في مستند ماركداون الخاص بك. يضعها بعض الناس مباشرةً بعد الفقرة التي تظهر فيها، ويضعها آخرون في نهاية المستند (كالحواشي السفلية).

#### مثال مكتمل يضع الأجزاء معًا

لنفترض أنك أضفت [رابطًا فعليًا](https://guide.dawin.io/basic-syntax/#links) لفقرة، فإنها ستبدو هكذا في ماركداون:

```
مُحرّر [دَوِّن](<https://www.dawin.io> "أوّل محرّر نصوص ماركداون عربي بمعاينة مباشرة") صُمّم بأيادٍ عربية ليكون مخصصًا للكتاب والمدونين، يساعدهم على الإلهام ويمَكّنهم من تحرير مقالات باللغة العربية ذات جودة عالية.
```

بالرغم من أن الرابط يضيف معلومات مثيرة للاهتمام، إلا أنه لا يضيف كثيرًا للنص العادي كما أنه يجعل النص أصعب في القراءة. لإصلاح ذلك، يمكنك تنسيق الرابط مثل هذا بدلاً من التنسيق السابق:

```
مُحرّر [دَوِّن][1] صُمّم بأيادٍ عربية ليكون مخصصًا للكتاب والمدونين، يساعدهم على الإلهام ويمَكّنهم من تحرير مقالات باللغة العربية ذات جودة عالية.

[1]: <https://www.dawin.io> "أوّل محرّر نصوص ماركداون عربي بمعاينة مباشرة"
```

في كلتا الحالتين أعلاه، سيكون الناتج المعروض متطابقًا:
مُحرّر <a href="https://www.dawin.io/" title="اكتب وحرّر مستنداتك بحروف عربية">دوّن</a> صُمّم بأيادٍ عربية ليكون مخصصًا للكتاب والمدونين، يساعدهم على الإلهام ويمَكّنهم من تحرير مقالات باللغة العربية ذات جودة عالية.

وسيكون ترميز HTML للرابط كالتالي:

```
<a href="https://www.dawin.io/" title="أوّل محرّر نصوص ماركداون عربي بمعاينة مباشرة">دَوِّن</a>
```

### أفضل ممارسات الروابط

لا تتفق تطبيقات ماركداون على كيفية التعامل مع المسافات في الرابط. للتوافقية، حاول استبدال أي مسافات برمز `%20`.

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
[عنوان الرابط](https://www.example.com/my%20great%20page)
</code>
      </td>
      <td>
<code class="highlighter-rouge">
[عنوان الرابط](https://www.example.com/my great page)
</code>
      </td>
    </tr>
  </tbody>
</table>
