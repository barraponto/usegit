---
theme: default
title: استخدام الطرفية
info: |
  استخدام Git - الدرس 1: استخدام الطرفية
  انظر https://github.com/barraponto/usegit
transition: slide-left
drawings:
  persist: false
exportFilename: 01-الطرفية.pdf
---

# استخدام الطرفية

## مع كابي إيثريل

[@barraponto](https://github.com/barraponto)

---
layout: statement
---

# ما هي الطرفية؟

<div class="max-w-prose mx-auto">
<v-clicks>

الطرفية هي برنامج يعرض واجهة سطر الأوامر للمستخدم النهائي.

</v-clicks>
</div>

---
layout: statement
---

# ما هو الشل؟

<div class="max-w-prose mx-auto">
<v-clicks>

بشكل عام، الشل هو واجهة للجهاز الكمبيوتر.

الشل الرسومي يسمح بالنقر على الرموز ورؤية مخرجات رسومية مثل النوافذ.

الشل سطر الأوامر يسمح بإدخال النص (الأوامر) واستقبال سطور نصية كإخراج (في معظم الأوقات).

</v-clicks>
</div>

---
layout: statement
---

# ما هي الأمر؟

<div class="max-w-prose mx-auto">
<v-clicks>

الأمر هو تمثيل نصي لما يُطلب من الكمبيوتر. إذا كنت تريد إرسال بريد إلكتروني إلى مديرك لطلب زيادة في الراتب، وكان محتوى البريد موجودًا بالفعل في ملف معين، يمكنك فعل ذلك على النحو التالي:

mail --subject="أحتاج زيادة في الراتب" boss@company.com < ./contents.txt

</v-clicks>
</div>

---
layout: intro
---

# فتح الطرفية

---
layout: intro
---

# تكوين الطرفية

---
layout: intro
---

# هل هناك برنامج قيد التشغيل الآن؟

---
layout: statement
---

# ما هو المترجم؟

<div class="max-w-prose mx-auto">
<v-clicks>

المترجم هو برنامج يأخذ إدخالك وينفذ البرامج الضرورية لمعالجته، مُجمعًا البرامج إذا كان ذلك ضروريًا.

كما يسمح أيضًا ببعض المنطق مثل الشروط والحلقات.

بالمناسبة، المترجم هو أيضًا REPL (بيئة تنفيذ قراءة-تقييم-طباعة) للغة برمجة نصية تُدعى **سكريبت الشل**.

</v-clicks>
</div>

---
layout: intro
---

# كيف يجد الشل البرامج؟

---
layout: statement
---

# ما هو الطريق (PATH)؟

<div class="max-w-prose mx-auto">
<v-clicks>

المتغير `PATH` هو متغير البيئة القياسي الذي يُدرج الأدلة التي يجب على المترجم البحث فيها عن البرامج. سيتم استخدام أول دليل يحتوي على برنامج بهذا الاسم.

</v-clicks>
</div>

---
layout: statement
---

# ما هو متغير البيئة؟

<div class="max-w-prose mx-auto">
<v-clicks>

متغير البيئة هو قيمة لها اسم.

هي متاحة لأوامرك.

بعضها تقليدي، مثل `PWD`، `PATH`، `PS1`.

يمكنك أيضًا إنشاء متغيرات خاصة بك.

</v-clicks>
</div>

---
layout: intro
---

# كيف يمكنني عرض متغيرات البيئة؟

الإجابة: `env`

---
layout: intro
---

# كيف يمكنني تكوين هذه المتغيرات؟

الإجابة: `.bashrc` أو `.zshrc` أو اعتمادًا على جهازك.

---
layout: intro
---

# أي نوع من الشل أستخدمه؟

الإجابة: `echo $0`

---
---

# لنضع الأمور في التطبيق
<br>

الهدف: تثبيت tealdeer 

1. إنشاء دليل "التنزيلات"
2. الوصول إلى هذا الدليل (الانتقال إليه باستخدام cd)
3. تنزيل tealdeer من https://github.com/dbrgn/tealdeer/releases
4. تشغيل tealdeer باستخدام `./tealdeer`
   4.1. تغيير الأذونات إذا كان ذلك ضروريًا
5. وضع tealdeer في مسار البحث (PATH)
6. إعادة تسمية teal
