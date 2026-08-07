# FREE PHONE NUMBER

موقع دليل خدمات الأرقام المجانية لتفعيل الرسائل النصية — متعدد اللغات مع لوحة تحكم.

## الملفات

- `index.html` — الصفحة الرئيسية (متعددة اللغات، عداد زيارات، آراء الزوار، إعلانات أدسنس).
- `dashboard.html` — لوحة التحكم (أدسنس، سيو، إدارة الخدمات والآراء). كلمة المرور الافتراضية: `admin123`.
- `robots.txt` + `sitemap.xml` — ملفات محركات البحث (حدّث النطاق من لوحة التحكم ثم أعد رفعها).

## الرفع على GitHub Pages (خطوتان)

1. أنشئ مستودعًا فارغًا على GitHub باسم: `USERNAME.github.io` (بدون إنشاء README).
2. في هذا المجلد نفّذ:

```
git remote add origin https://github.com/USERNAME/USERNAME.github.io.git
git push -u origin main
```

ثم من إعدادات المستودع: Settings → Pages → Source: Deploy from a branch → `main` / root → Save.
الموقع يظهر خلال دقيقة على: `https://USERNAME.github.io/`

## بعد النشر

- لوحة التحكم: `https://USERNAME.github.io/dashboard.html`
- من تبويب «السيو» ضع النطاق الحقيقي، ولّد `sitemap.xml` و `robots.txt` الجديدين، ثم ادفع التعديلات.
- فعّل أدسنس من اللوحة بعد الموافقة.
