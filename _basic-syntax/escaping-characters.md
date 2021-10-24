---
title: تخطي الحروف
syntax-id: escaping-characters
api: "no"
---

لعرض حرف (من الحروف المفتاحية التي تُعَالج مباشرة في ماركداون) دون أن يكون له أثر على التنسيق وإنما يظهر كما هو، أضف شرطة مائلة للخلف (`\`) أمام الحرف.

```
\* لولا الشرطة المائلة للخلف، لكان هذا النص جزءًا من قائمة منقطة
```

ستكون النتيجة النهائية كالتالي: \* لولا الشرطة المائلة للخلف، لكان هذا النص جزءًا من قائمة منقطة.

### الحروف التي يمكنك تخطيها

يمكنك استخدام الشرطة المائلة للخلف لتخطي الأحرف التالية.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>الحرف</th>
      <th>الاسم</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>\</td>
      <td>شرطة مائلة للخلف</td>
    </tr>
    <tr>
      <td>`</td>
      <td>الفاصلة العليا المائلة (انظر أيضًا <a href="https://guide.dawin.io/basic-syntax/#escaping-backticks">تخطي الفاصلة العليا في الكود</a>)</td>
    </tr>
    <tr>
      <td>*</td>
      <td>نجمة</td>
    </tr>
    <tr>
      <td>_</td>
      <td>شرطة سفلية</td>
    </tr>
    <tr>
      <td>{ }</td>
      <td>أقواس معقوفة / مزخرفة</td>
    </tr>
    <tr>
      <td>[ ]</td>
      <td>أقواس مربعة</td>
    </tr>
    <tr>
      <td>< ></td>
      <td>أقواس الزاوية</td>
    </tr>
    <tr>
      <td>( )</td>
      <td>أقواس هلالية</td>
    </tr>
    <tr>
      <td>#</td>
      <td>علامة المربع (أو الشبّاك)</td>
    </tr>
    <tr>
      <td>+</td>
      <td>علامة الجمع</td>
    </tr>
    <tr>
      <td>-</td>
      <td>علامة الطرح (الشرطة)</td>
    </tr>
    <tr>
      <td>.</td>
      <td>نقطة</td>
    </tr>
    <tr>
      <td>!</td>
      <td>علامة التعجب</td>
    </tr>
    <tr>
      <td>|</td>
      <td>علامة الأنبوب (انظر أيضًا <a href="https://guide.dawin.io/extended-syntax/#escaping-pipe-characters-in-tables">تخطي علامة الأنبوب في الجداول</a>)</td>
    </tr>
  </tbody>
</table>
