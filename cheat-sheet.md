---
layout: default
title: ملخّصات مرجعية
description: مرجع سريع لقواعد ماركداون.
last_modified_at: 2020-07-31
---

## لمحة

توفر الملخّصات المرجعية (Cheat Sheet) نظرة عامة سريعة على جميع عناصر ماركداون. لا يمكن أن تغطّي هذه المختصرات كل حالة فرعية، لذلك إذا كنت بحاجة إلى مزيد من المعلومات حول أي من هذه العناصر، فارجع إلى الأدلة المرجعية [للقواعد الأساسية](https://guide.dawin.io/basic-syntax) و[القواعد الموسّعة](https://guide.dawin.io/extended-syntax).

## القواعد الأساسية

هذه هي العناصر الموضّحة في مستند التصميم الأصلي لجون جروبر مخترع ماركداون. تدعم جميع تطبيقات ماركداون هذه العناصر.

<table class="table table-bordered">
	<thead class="thead-light">
		<tr>
			<th>العنصر</th>
			<th>قاعدة ماركداون</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>
				<a href="https://guide.dawin.io/basic-syntax/#العناوين"
					>العناوين</a
				>
			</td>
			<td>
				<code
					># عنوان أول<br />
					## عنوان ثاني<br />
					### عنوان ثالث
				</code>
			</td>
		</tr>
		<tr>
			<td>
				<a href="https://guide.dawin.io/basic-syntax#سُمْك-النص"
					>تسميك النص</a
				>
			</td>
			<td><code>**النص المراد زيادة سمكه**</code></td>
		</tr>
		<tr>
			<td>
				<a href="https://guide.dawin.io/basic-syntax#إمالة-النص"
					>إمالة النص</a
				>
			</td>
			<td><code> *النص المراد إمالته* </code></td>
		</tr>
		<tr>
			<td>
				<a href="https://guide.dawin.io/basic-syntax#الاقتباسات-1"
					>الاقتباس</a
				>
			</td>
			<td><code>> نص الاقتباس</code></td>
		</tr>
		<tr>
			<td>
				<a href="https://guide.dawin.io/basic-syntax#القوائم-المرقّمة-المرتّبة"
					>قائمة مرقّمة</a
				>
			</td>
			<td>
				<code>
					1. العنصر الأول<br />
					2. العنصر الثاني<br />
					3. العنصر الثالث<br />
				</code>
			</td>
		</tr>
		<tr>
			<td>
				<a href="https://guide.dawin.io/basic-syntax#القوائم-المنقّطة-غير-المرتّبة"
					>قائمة منقّطة</a
				>
			</td>
			<td>
				<code>
					- العنصر الأول<br />
					- العنصر الثاني<br />
					- العنصر الثالث<br />
				</code>
			</td>
		</tr>
		<tr>
			<td>
				<a href="https://guide.dawin.io/basic-syntax#الأكواد-البرمجية">الكود البرمجي</a>
			</td>
			<td><code>`هنا يُكتب الكود البرمجي`</code></td>
		</tr>
		<tr>
			<td>
				<a href="https://guide.dawin.io/basic-syntax/#فواصل-الأسطر"
					>خط أفقي</a
				>
			</td>
			<td><code>---</code></td>
		</tr>
		<tr>
			<td>
				<a href="https://guide.dawin.io/basic-syntax/#الروابط">رابط</a>
			</td>
			<td><code>[عنوان الرابط](https://www.example.com)</code></td>
		</tr>
		<tr>
			<td>
				<a href="https://guide.dawin.io/basic-syntax/#الصور-1">صورة</a>
			</td>
			<td><code>![صورة الرابط](link-to_img.jpg)</code></td>
		</tr>
	</tbody>
</table>

## القواعد الموسّعة

هذه القواعد الموسعة تُضيف ميزات إضافية. لا تدعم جميع تطبيقات ماركداون هذه العناصر.

<table class="table table-bordered">
	<thead class="thead-light">
		<tr>
			<th>العنصر</th>
			<th>تنسيق ماركداون</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>
				<a href="https://guide.dawin.io/extended-syntax/#الجداول">جدول</a>
			</td>
			<td>
				<code>
					| | العمود 1 | العمود 2 | العمود 3 |<br />
					| -------- | -------- | -------- |<br />
					| النص | النص | النص |<br />
				</code>
			</td>
		</tr>
		<tr>
			<td>
				<a
					href="https://guide.dawin.io/extended-syntax/#الكتل-البرمجية-المسوّرة"
					>فقرة برمجية كاملة</a
				>
			</td>
			<td>
				<code
					>```<br />
					{<br />
					&nbsp;&nbsp;"firstName": "محمد",<br />
					&nbsp;&nbsp;"lastName": "صالح",<br />
					&nbsp;&nbsp;"age": 25<br />
					}<br />
					```
				</code>
			</td>
		</tr>
		<tr>
			<td>
				<a href="https://guide.dawin.io/extended-syntax/#الحواشي-السفلية"
					>حاشية سفلية</a
				>
			</td>
			<td>
				<code>
					هذه الجملة تتضمن حاشية سفلية. [^1]<br />
					[^1]: هذه هي الحاشية السفلية.<br />
				</code>
			</td>
		</tr>
		<tr>
			<td>
				<a href="https://guide.dawin.io/extended-syntax/#معرفّات-العنوان"
					>معرّف فريد للعنوان</a
				>
			</td>
			<td>
				<code>### هذا العنوان المميز {#معرف-فريد}</code>
			</td>
		</tr>
		<tr>
			<td>
				<a
					href="https://guide.dawin.io/extended-syntax/#قوائم-التعريف"
					>قائمة تعريف</a
				>
			</td>
			<td>
				<code>
					المصطلح<br />
					: التعريف
				</code>
			</td>
		</tr>
		<tr>
			<td>
				<a href="https://guide.dawin.io/extended-syntax/#النص-المشطوب"
					>نص مشطوب</a
				>
			</td>
			<td>
				<code>~~هذا نص مشطوب إما لأنه خطأ أو طرأ عليه تحديث جديد.~~</code>
			</td>
		</tr>
		<tr>
			<td>
				<a href="https://guide.dawin.io/extended-syntax/#قوائم-المهام"
					>قائمة مهام</a
				>
			</td>
			<td>
				<code>
					- [x] مهمة انتهت بنجاح<br />
					- [ ] مهمة ما زالت قيد التنفيذ<br />
					- [ ] مهمة أخرى لم تنفذ بعد<br />
				</code>
			</td>
		</tr>
	</tbody>
</table>
<!-- ## التنزيلات -->

<!-- يمكنك [تنزيل هذا المخلص المرجعي كملف ماركداون](https://guide.dawin.io/assets/markdown-cheat-sheet.md) لتستخدمه في تطبيق ماركداون الذي تستخدمه. -->
