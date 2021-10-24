---
title: الصور
syntax-id: images
syntax-summary: "![alt text](image.jpg)"
description: "To add an image, add an exclamation mark (`!`), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title after the URL in the parentheses."
examples:
  - markdown: |
      ![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")
    html: <img src=\"/assets/images/san-juan-mountains.jpg\" class=\"img-responsive\" alt=\"The San Juan Mountains are beautiful!\" title=\"San Juan Mountains\">
additional-examples:
  - name: "Linking Images"
    description: "To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses."
    markdown: |
      [![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
    html: <a href=\"https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv\"><img src=\"/assets/images/shiprock.jpg\" alt=\"An old rock in the desert\" title=\"Shiprock, New Mexico by Beau Rogers\"></a>
---

لإضافة صورة، أضف علامة تعجب (`!`)، متبوعة بنص بديل بين قوسين (يظهر في حالة تعذر ظهور الصورة)، ثم مسار الصورة بين قوسين مربعين. يمكنك اختياريًا إضافة عنوان للصورة بعد الأقواس؛ الذي يظهر عندما يحوم مؤشر الماوس (Hover) على الصورة.

```
![صورة يوغرطة بن علي رحمه الله](https://i.suar.me/9AdO8/ "صورة المبرمج والناشط التقني الراحل يوغرطة بن علي")
```

ستكون النتيجة النهائية كالتالي:

![صورة يوغرطة بن علي](https://i.suar.me/9AdO8/ "صورة المبرمج والناشط التقني الراحل يوغرطة بن علي")

### إضافة الروابط للصور

لإضافة الروابط للصور، أحط تنسيق ماركداون للصور بالأقواس المربعة `[]`، ثم أضف الرابط بالأقواس الهلالية `()`.

```
[![شعار شركة صخر](https://upload.wikimedia.org/wikipedia/commons/5/53/Sakhr.jpg "من أكبر الشركات البرمجية العربية")](https://ar.wikipedia.org/wiki/%D8%B5%D8%AE%D8%B1_(%D8%B4%D8%B1%D9%83%D8%A9))
```

ستكون النتيجة النهائية كالتالي:

[![شعار شركة صخر](https://upload.wikimedia.org/wikipedia/commons/5/53/Sakhr.jpg "من أكبر الشركات البرمجية العربية")](<https://ar.wikipedia.org/wiki/%D8%B5%D8%AE%D8%B1_(%D8%B4%D8%B1%D9%83%D8%A9)>)
