# 💬 DirectMsg (direct~chat) | محادثة مباشرة

<div align="center">

[![React](https://img.shields.io/badge/React-19-61dafb.svg?style=flat-square&logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178c6.svg?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-6-646cff.svg?style=flat-square&logo=vite)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-4-38b2ac.svg?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![PWA Ready](https://img.shields.io/badge/PWA-Installable-5A0FC8.svg?style=flat-square&logo=pwa)](https://web.dev/progressive-web-apps/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)

**تطبيق حديث وسريع لفتح محادثات فورية ومباشرة عبر واتساب، واتساب للأعمال، تيليجرام، سيجنال، والرسائل القصيرة (SMS) دون الحاجة لتسجيل الرقم في جهات الاتصال.**

*A modern, privacy-focused web application to start direct chats on WhatsApp, WhatsApp Business, Telegram, Signal, and SMS without saving numbers to your address book.*

[🌟 الميزات](#-المميزات-الرئيسية--key-features) •
[🚀 التشغيل السريع](#-التشغيل-والتطوير--getting-started) •
[📁 هيكلية المشروع](#-هيكلية-المشروع--project-structure) •
[📦 نسخة الملف المستقل](#-نسخة-html-المستقلة--single-file-html) •
[🔒 الخصوصية والأمان](#-الخصوصية-والأمان--privacy--security)

---

</div>

## 📖 نبذة عن المشروع | About The Project

كثيراً ما نحتاج لمراسلة مندوب توصيل، متجر، أو عميل لمرة واحدة فقط عبر واتساب أو تيليجرام، وتجبرنا التطبيقات التقليدية على حفظ الرقم في قائمة جهات الاتصال.
حل **DirectMsg (direct~chat)** هذه المشكلة نهائياً من خلال واجهة مستخدم سريعة، أنيقة، تدعم كافة المنصات وتعمل على جميع الهواتف والمتصفحات، بالإضافة إلى توفير نسخة مستند مستقلة (`direct-chat.html`) تعمل بدون إنترنت وبدون خادم.

---

## ✨ المميزات الرئيسية | Key Features

### 1. 🚀 دعم متعدد المنصات (Multi-Platform Support)
- **واتساب (WhatsApp)**: فتح المحادثة مباشرة عبر الرابط الرسمي `wa.me`.
- **واتساب بزنس (WhatsApp Business)**: خيار مخصص لفتح الرقم مباشرة في تطبيق واتساب الأعمال التجاري.
- **تيليجرام (Telegram)**: فتح حساب أو بدء محادثة فورية عبر معرف الرقم الدولي.
- **سيجنال (Signal)**: دعم تطبيق المراسلة الآمن سيجنال.
- **الرسائل القصيرة (SMS)**: فتح تطبيق الرسائل النصية الافتراضي على الهاتف مع تجهيز النص مسبقاً.

### 2. 🌍 اختيار ذكي وتلقائي للدول (Smart Country Picker)
- دعم لأكثر من 200 دولة مع الأعلام الرسمية والرموز الدولية.
- بحث فوري بالاسم العربي، الإنجليزي، أو مفتاح الدولة (مثل +964، +966، +20).
- معالجة تلقائية للأرقام: تنظيف الرقم من الفواصل والمسافات والرموز والأصفار الزائدة عند اختيار المفتاح الدولي.

### 3. 💬 قوالب رسائل جاهزة وتخصيص فوري (Quick Templates)
- إرسال مباشر بدون نص أو كتابة رسالة مسبقة.
- قوالب سريعة ومفيدة: (تحيات رسمية، طلب الموقع الجغرافي، استفسار عن الأسعار، تأكيد طلب).
- خيار إنشاء قوالب خاصة وحفظها في التفضيلات.

### 4. 🔗 مولد روابط مباشرة ورمز الاستجابة السريعة (QR Code & Direct Links)
- نسخ رابط المراسلة السريع بضغطة واحدة لمشاركته في الإعلانات، السير الذاتية، أو وسائل التواصل.
- توليد رمز QR قابل للمسح الضوئي الفوري بكاميرا أي هاتف.

### 5. 📜 سجل محلي يحفظ الخصوصية (Privacy-First Local History)
- الاحتفاظ بآخر الأرقام والعمليات محلياً على جهازك فقط (`localStorage`).
- إمكانية إعادة المراسلة بلمسة واحدة دون إعادة إدخال الرقم.
- خيار مسح السجل كلياً أو جزئياً في أي وقت.

### 6. 📱 تطبيق ويب تقدمي قابل للتثبيت (PWA & Offline Ready)
- دعم التثبيت المباشر على الشاشة الرئيسية للهواتف (Android & iOS) ليعمل كتطبيق أصلي (APK-like Native Experience).
- تشغيل بدون اتصال بالإنترنت وحفظ التفضيلات محلياً.

### 7. 📦 ملف HTML مستقل بالكامل (Standalone Single-File HTML)
- إمكانية تشغيل التطبيق بالكامل من ملف واحد (`direct-chat.html`) مدمج به كود الـ React، التنسيقات (Tailwind CSS)، والأيقونات، ليعمل بمجرد النقر المزدوج عليه بدون تثبيت `Node.js` أو الحاجة لأي خادم.

---

## 🛠️ التقنيات المستخدمة | Tech Stack

- **الواجهة الأمامية (Frontend):** [React 19](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- **التجميع والأداء (Build Tool):** [Vite 6](https://vitejs.dev/)
- **التصميم والتنسيق (Styling):** [Tailwind CSS v4](https://tailwindcss.com/) بتصميم Dark Modern Glassmorphism
- **الأيقونات (Icons):** [Lucide React](https://lucide.dev/) + SVG Brands
- **التخزين (Storage):** المتصفح المحلي LocalStorage بدون أي خوادم خارجية
- **تطبيق الويب التقدمي (PWA):** `vite-plugin-pwa` مع Service Worker وتخزين مؤقت
- **الحزم المستقلة (Single-File Inliner):** `vite-plugin-singlefile`

---

## 🚀 التشغيل والتطوير | Getting Started

### المتطلبات المسبقة (Prerequisites)
- [Node.js](https://nodejs.org/) (الإصدار 18 أو أحدث)
- مدير الحزم `npm` أو `pnpm` أو `yarn`

### 1. استنساخ المستودع (Clone Repository)
```bash
git clone <REPO_URL>
cd direct-chat
```

### 2. تثبيت الحزم (Install Dependencies)
```bash
npm install
```

### 3. تشغيل وضع التطوير (Run Development Server)
```bash
npm run dev
```
افتح المتصفح على العنوان: `http://localhost:3000`

### 4. فحص جودة الكود والأنماط (Linting & Testing)
```bash
npm run lint
npm test
```

### 5. بناء المشروع للإنتاج (Production Build)
```bash
npm run build
```
يقوم هذا الأمر ببناء:
1. نسخة الويب الموزعة القياسية داخل مجلد `dist/`.
2. نسخة ملف الـ HTML الموحد والمستقل `direct-chat.html` و `public/direct-chat.html`.

---

## 📦 نسخة HTML المستقلة | Single-File HTML

إذا كنت ترغب في إنشاء أو تحديث ملف الـ HTML الموحد فقط:
```bash
npm run build:single
```
- **المسار الناتج:** `direct-chat.html`
- **المميزات:**
  - واجهة مطابقة تماماً لواجهة التطبيق بنسبة 100%.
  - يحتوي على كل كود JavaScript، CSS، والخطوط مدمجة بداخله.
  - يعمل مباشرة عن طريق المتصفح حتى من ذاكرة فلاش (USB) أو في بيئة معزولة تماماً بدون إنترنت.

---

## 📁 هيكلية المشروع | Project Structure

```text
├── direct-chat.html            # ملف HTML مستقل وشامل لكافة مميزات التطبيق
├── public/
│   ├── favicon.svg             # أيقونة الموقع
│   ├── icon.svg                # شعار التطبيق المتجهي
│   ├── manifest.json           # إعدادات تطبيق الويب التقدمي (PWA)
│   └── direct-chat.html        # نسخة الـ HTML المستقلة المتاحة عبر الويب
├── scripts/
│   └── build-single-file.mjs   # أداة البناء البرمجية لتوليد ملف الـ HTML المستقل
├── src/
│   ├── components/
│   │   ├── BrandIcons.tsx      # أيقونات واتساب، تيليجرام، سيجنال بدقة عالية
│   │   ├── DirectSender.tsx    # البطاقة التفاعلية الرئيسية لإرسال الرسائل واختيار المنصة
│   │   ├── HelpModal.tsx       # نافذة الإرشادات والأسئلة الشائعة
│   │   ├── HistoryDrawer.tsx   # درج سجل المحادثات السابقة وخيارات إدارتها
│   │   ├── Navbar.tsx          # شريط التنقل العلوي، الشعار، الأزرار السريعة
│   │   ├── PWAInstallModal.tsx # نافذة تثبيت التطبيق على الهواتف والأجهزة
│   │   ├── QRCodeModal.tsx     # نافذة مسح وتوليد رمز الـ QR ومشاركة الرابط
│   │   ├── SettingsModal.tsx   # نافذة التفضيلات (الدولة الافتراضية، الإشعارات)
│   │   └── usePWAInstall.ts    # Hook مخصص للتعامل مع تثبيت PWA
│   ├── utils/
│   │   ├── phone.ts            # قائمة الدول، التحقق من صحة الرقم، وتنظيف المدخلات
│   │   ├── phone.test.ts       # اختبارات الوحدة لمعالجة أرقام الهواتف
│   │   └── translations.ts     # نصوص اللغتين العربية والإنجليزية
│   ├── App.tsx                 # المكون الجذري للتطبيق
│   ├── index.css               # استيراد وتخصيص Tailwind CSS v4
│   └── main.tsx                # نقطة الدخول لتطبيق React
├── package.json                # التبعيات والأوامر
├── tsconfig.json               # إعدادات لغة TypeScript
├── vite.config.ts              # إعدادات بناء Vite وتطبيق الويب
└── vite.singlefile.config.ts   # إعدادات تجميع التطبيق إلى ملف HTML منفرد
```

---

## 🔒 الخصوصية والأمان | Privacy & Security

- **صفر خوادم خارجية (Zero Backend Storage):** أرقام الهواتف ونصوص الرسائل لا تُرسل ولا تُخزن على أي خادم سحابي إطلاقاً.
- **معالجة محلية فقط (Client-Side Only):** جميع الروابط تُنشأ مباشرة داخل متصفح المستخدم وتتوجه إلى روابط التوجيه الرسمية المعتمدة من الشركات المطورة (`wa.me`، `t.me`، `sms:`).
- **أمان البيانات:** سجل المحادثات يُحفظ في الـ `localStorage` لجهازك الخاص فقط، وتستطيع مسحه في أي ثانية بضغطة زر واحدة.

---

## 🤝 المساهمة | Contributing

نرحب بمساهمات الجميع! لتطوير ميزة جديدة أو إصلاح أي مشكلة:
1. قم بعمل Fork للمستودع.
2. أنشئ فرعاً لميزتك (`git checkout -b feature/AmazingFeature`).
3. احفظ التغييرات (`git commit -m 'Add some AmazingFeature'`).
4. ادفع التغييرات إلى فرعك (`git push origin feature/AmazingFeature`).
5. افتح طلب دمج (Pull Request).

---

## 📄 الترخيص | License

هذا المشروع مرخص تحت رخصة **MIT**. لمزيد من التفاصيل، راجع ملف التراخيص.
