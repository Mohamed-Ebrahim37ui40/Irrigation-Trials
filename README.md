# Irrigation Pivot Manager — مدير البيفوتات

تطبيق ويب احترافي (PWA) لإدارة بيانات أنظمة الري المحوري، يعمل بدون إنترنت ويمكن تثبيته على الشاشة الرئيسية في أندرويد وiOS وWindows وmacOS وLinux.

**تصميم مهندس محمد إبراهيم (Firmo)**

## المميزات

- عدد غير محدود من البيفوتات مع حفظ محلي آمن.
- استدعاء البيفوت بالضغط على اسمه، مع تعديل وحذف.
- بحث فوري وإحصائيات تلقائية.
- زر **تثبيت التطبيق** في أعلى الصفحة لجميع الأنظمة المدعومة.
- على iOS يعرض الزر تعليمات **Add to Home Screen** في Safari.
- تبديل عربي/إنجليزي وثيم نهاري/ليلي.
- عمل كامل بدون إنترنت بعد أول فتح.
- أيقونة مخصصة للتطبيق على أندرويد وiOS.
- قسم تواصل تفاعلي، ومنه رابط LinkedIn المباشر.

## التشغيل والتثبيت

للتثبيت الكامل يجب فتح التطبيق عبر **HTTPS** أو `localhost`; فتح ملف `index.html` مباشرة بصيغة `file:///` لا يفعّل Service Worker أو التثبيت.

```bash
cd irrigation-pivot-manager
python -m http.server 8080
```

افتح `http://localhost:8080`.

- **أندرويد / Windows / macOS / Linux:** اضغط زر **تثبيت التطبيق**، أو أيقونة التثبيت في المتصفح.
- **iPhone / iPad:** في Safari اضغط **Share ⬆️** ثم **Add to Home Screen** ثم **Add**.

## الملفات

```text
irrigation-pivot-manager/
├── index.html
├── styles.css
├── app.js
├── manifest.webmanifest
├── sw.js
├── README.md
├── assets/logo.svg
└── icons/icon-192.png, icon-512.png
```

## التواصل

- Email: mohamed.ibrahim11617@gmail.com
- LinkedIn: https://www.linkedin.com/in/mohamed-ebrahim-771b0540a
- Facebook: https://www.facebook.com/share/1JHu4fGCXa/
- X: https://x.com/Firmo13MH
- WhatsApp: https://wa.me/qr/QIZ446FGUAGGD1
- Telegram: https://t.me/FR6060ME
