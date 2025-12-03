# [HTML5 Boilerplate](https://html5boilerplate.com/)

[![Build status](https://github.com/h5bp/html5-boilerplate/workflows/Build%20status/badge.svg)](https://github.com/h5bp/html5-boilerplate/actions?query=workflow%3A%22Build+status%22+branch%3Amain)
[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://github.com/h5bp/html5-boilerplate/blob/main/LICENSE.txt)
[![NPM Downloads](https://img.shields.io/npm/dt/html5-boilerplate.svg)](https://www.npmjs.com/package/html5-boilerplate)
[![github-stars-image](https://img.shields.io/github/stars/h5bp/html5-boilerplate.svg?label=github%20stars)](https://github.com/h5bp/html5-boilerplate)

HTML5 Boilerplate هو قالب احترافي للواجهة الأمامية لبناء
تطبيقات أو مواقع ويب سريعة وقوية وقابلة للتكيف.

هذا المشروع هو نتاج أكثر من 10 سنوات من التطوير التكراري والمعرفة
المجتمعية. لا يفرض فلسفة أو إطار عمل تطوير محدد، لذا فأنت حر في
تصميم الكود الخاص بك بالطريقة التي تريدها.

- [الصفحة الرئيسية](https://html5boilerplate.com/)
- [الكود المصدري](https://github.com/h5bp/html5-boilerplate)

## حول هذا المستودع

هذا المستودع هو المكان الذي تم فيه تأليف HTML5-Boilerplate. بعض الأدوات
والملفات والعمليات التي تراها هنا مخصصة فقط لـ _إنتاج_
HTML5 Boilerplate وليست _جزءًا_ من HTML5 Boilerplate. على سبيل المثال،
سكريبت [gulpfile.mjs](https://github.com/h5bp/html5-boilerplate/blob/main/gulpfile.mjs)
يُستخدم لـ _بناء_ المشروع. إنه ليس جزءًا من المشروع نفسه.

المشروع الذي ننشره ممثل بمحتويات مجلد `/dist/`.
كل شيء آخر في هذا المستودع يُستخدم لتأليف المشروع.

فكر في الأمر بهذه الطريقة، بنفس الطريقة التي لا تستنسخ بها [vuejs/core](https://github.com/vuejs/core)
لإنشاء تطبيق Vue.js، لا تحتاج إلى استنساخ هذا المستودع لبدء
موقع أو تطبيق جديد يعتمد على HTML5 Boilerplate.

لذا، إذا كنت تبحث عن قالب بداية سريعة لبناء موقع ويب أو
تطبيق، انظر إلى الخيارات في
قسم [البداية السريعة](https://github.com/h5bp/html5-boilerplate#quick-start) من هذا المستند.

إذا كنت تريد مساعدتنا في _تحسين_ HTML5 Boilerplate، فيمكنك البدء بالوثائق [هنا](.github/CONTRIBUTING.md)، والتي تتضمن خطوات لاستنساخ هذا المستودع من أجل إعداده للتطوير.

## البداية السريعة

اختر أحد الخيارات التالية:

- استخدام سكريبت [create-html5-boilerplate](https://github.com/h5bp/create-html5-boilerplate)
  للحصول فورًا على أحدث حزمة npm منشورة (أو أي إصدار
  متاح على npm) باستخدام `npx` أو `npm init` أو `yarn create` دون الحاجة إلى
  تثبيت أي تبعيات. تشغيل أمر `npx` التالي يثبت
  أحدث إصدار في مجلد يسمى `new-site`

  ```bash
  npx create-html5-boilerplate new-site
  cd new-site
  npm install
  npm run start
  ```

- استخدام [مستودع القالب](https://github.com/h5bp/html5-boilerplate-template) الجديد
  لإنشاء مستودع GitHub جديد بناءً على أحدث كود من الفرع الرئيسي لـ HTML5
  Boilerplate.

- التثبيت باستخدام [npm](https://www.npmjs.com/): `npm install html5-boilerplate`
  أو [yarn](https://yarnpkg.com/): `yarn add html5-boilerplate`. المجلد الناتج
  `node_modules/html5-boilerplate/dist` يمثل أحدث إصدار من
  المشروع للمستخدمين النهائيين. اعتمادًا على ما تريد استخدامه وكيف تريد
  استخدامه، قد تضطر إلى نسخ ولصق محتويات هذا المجلد في
  دليل مشروعك.

- تنزيل أحدث إصدار مستقر من
  [هنا](https://github.com/h5bp/html5-boilerplate/releases/download/v9.0.0/html5-boilerplate_v9.0.0.zip). ملف zip هذا هو
  لقطة لمجلد `dist`. على Windows أو Mac ومن مدير الملفات على
  Linux، سيؤدي فك ضغط هذا المجلد إلى إخراج مجلد يسمى شيئًا مثل
  `html5-boilerplate_v9.0.0`. من سطر الأوامر، ستحتاج إلى إنشاء
  مجلد وفك ضغط المحتويات في هذا المجلد.

  ```bash
  mkdir html5-boilerplate
  unzip html5-boilerplate*.zip -d html5-boilerplate
  ```

## الميزات

- قالب بداية مضبوط بدقة: اجنِ فوائد 10 سنوات من التحليل
  والبحث والتجريب من قبل أكثر من 200 مساهم.
- مصمم مع وضع التحسين التدريجي في الاعتبار.
- يتضمن:
  - عناصر وسمات Open Graph النائبة.
  - ملف package.json نموذجي مع أوامر [WebPack](https://webpack.js.org/)
    مدمجة لبدء تطوير التطبيق.
  - استعلامات CSS Media النائبة.
  - فئات مساعدة CSS مفيدة.
  - أنماط طباعة افتراضية، محسنة للأداء.
  - "سهل الحذف." من السهل إزالة الأجزاء التي لا تحتاجها.
  - وثائق شاملة.

## دعم المتصفحات

يدعم HTML5-Boilerplate أحدث الإصدارات المستقرة من جميع المتصفحات الرئيسية.

تحقق من تكوين `default` من [Browserslist](https://browsersl.ist/#q=defaults)
لمزيد من التفاصيل حول المتصفحات والإصدارات المغطاة.

## الوثائق

ألقِ نظرة على [جدول محتويات الوثائق](docs/TOC.md). هذه
الوثائق مجمعة مع المشروع مما يجعلها متاحة للقراءة
دون اتصال بالإنترنت وتوفر نقطة انطلاق مفيدة لأي وثائق تريد
كتابتها حول مشروعك.

## المساهمة

ساعد المئات من المطورين في إنشاء HTML5 Boilerplate. أي شخص
مرحب به [للمساهمة](.github/CONTRIBUTING.md). ومع ذلك، إذا قررت
المشاركة، يرجى قضاء لحظة لمراجعة [الإرشادات](.github/CONTRIBUTING.md):

- [تقارير الأخطاء](.github/CONTRIBUTING.md#bugs)
- [طلبات الميزات](.github/CONTRIBUTING.md#features)
- [طلبات السحب](.github/CONTRIBUTING.md#pull-requests)

## الترخيص

الكود متاح بموجب [ترخيص MIT](LICENSE.txt).
