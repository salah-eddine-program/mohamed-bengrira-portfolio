# Mohamed Bengrira — Personal Portfolio

موقع شخصي ثابت ومتجاوب للتعريف بالمسار المهني والأكاديمي لمحمد بن قريرة، بثلاث لغات: العربية والفرنسية والإنجليزية.

## محتويات المشروع

```text
mohamed-bengrira-site/
├── index.html
├── README.md
├── .nojekyll
└── assets/
    ├── css/style.css
    ├── js/main.js
    ├── images/
    │   ├── favicon.svg
    │   ├── mohamed-portrait.webp
    │   └── mohamed-original.webp
    └── cv/CV-Mohamed-Bengrira.pdf
```

## المميزات

- ثلاث لغات مع تغيير فوري للواجهة: العربية (RTL)، الفرنسية، والإنجليزية.
- تصميم متجاوب للهاتف واللوحي والحاسوب.
- تصميم داكن ثابت بهوية كحلية ولمسات ذهبية وزرقاء؛ لا يوجد وضع نهاري أو زر لتغيير السمة.
- أقسام النبذة الشخصية، المهارات، الخبرة المهنية، التكوين، مشروع التخرج، اللغات، وبيانات الاتصال.
- زر تنزيل السيرة الذاتية PDF.
- روابط مباشرة للهاتف والبريد الإلكتروني وواتساب.
- لا يحتاج إلى قاعدة بيانات أو خادم أو خطوات بناء؛ HTML وCSS وJavaScript فقط.

## النشر المجاني عبر GitHub Pages

1. فك ضغط ملف ZIP على جهازك.
2. أنشئ مستودعًا جديدًا على GitHub، مثل `mohamed-bengrira-portfolio`.
3. ارفع **محتويات** مجلد `mohamed-bengrira-site` إلى جذر المستودع، بحيث يكون `index.html` في المستوى الأول وليس داخل مجلد إضافي.
4. افتح **Settings → Pages**.
5. ضمن **Build and deployment** اختر **Deploy from a branch**.
6. اختر الفرع `main` والمجلد `/ (root)` ثم اضغط **Save**.
7. بعد اكتمال النشر سيظهر رابط الموقع في قسم GitHub Pages، عادةً بالشكل:
   `https://YOUR-USERNAME.github.io/mohamed-bengrira-portfolio/`

إذا كان اسم المستودع `YOUR-USERNAME.github.io` فسيكون الموقع على النطاق الرئيسي لحساب GitHub Pages.

## تعديل البيانات

- النصوص والترجمات الثلاث موجودة في `assets/js/main.js` داخل الكائن `translations`.
- الألوان والأحجام والتنسيق موجودة في `assets/css/style.css` داخل متغيرات `:root` في بداية الملف.
- الصورة الرئيسية: `assets/images/mohamed-portrait.webp`.
- الصورة الإضافية: `assets/images/mohamed-original.webp`.
- ملف السيرة الذاتية: `assets/cv/CV-Mohamed-Bengrira.pdf`.

لإضافة رابط LinkedIn أو GitHub، عدّل قسم التواصل في `index.html` وأضف الرابط الحقيقي؛ لم تتم إضافة روابط حسابات غير متوفرة في السيرة الذاتية.

## معلومات يجب مراجعتها قبل النشر

- تأكد من صحة رقم الهاتف والبريد الإلكتروني ومعلومات السيرة الذاتية.
- الصورة الرئيسية معالجة/مولّدة اعتمادًا على الصور المرجعية المقدمة؛ يمكن استبدالها بصورة شخصية رسمية عبر استبدال الملف `mohamed-portrait.webp` مع الاحتفاظ بالاسم نفسه.
- شهادة CCNA مذكورة بصيغة **قيد التحضير** وليست شهادة مكتسبة.
- الموقع يعرض المهارات والخبرات كما وردت في السيرة الذاتية ولا يدّعي امتلاك شهادات أو وظائف إضافية.

## Technical notes

This is a static website. It can also be hosted on Netlify, Cloudflare Pages, or any static web host. No API keys, build tools, or environment variables are required.


### قائمة اللغات
تستخدم قائمة اللغات أعلامًا مرسومة بصيغة SVG داخل الموقع (الجزائر 🇩🇿، فرنسا 🇫🇷، المملكة المتحدة 🇬🇧)، لذلك تظهر بجانب أسماء اللغات دون الاعتماد على دعم رموز الأعلام في خطوط الجهاز.
