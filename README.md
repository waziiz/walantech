# وعلان للتقنية — Walan Technology Website

موقع وعلان للتقنية الرسمي — مبني بـ HTML/CSS/JS خالص بدون أي framework.

## 📁 هيكل الملفات

النسخة العربية بالجذر، والنسخة الإنجليزية داخل مجلد `en/`.

| الملف (عربي) | الملف (English) | الوصف |
|---|---|---|
| `index.html` | `en/index.html` | الصفحة الرئيسية |
| `about.html` | `en/about.html` | من نحن |
| `easy-erp.html` | `en/easy-erp.html` | Easy ERP |
| `mobile-pos.html` | `en/mobile-pos.html` | نقاط البيع المتنقل |
| `pos.html` | `en/pos.html` | أجهزة نقاط البيع |
| `apps.html` | `en/apps.html` | تطبيقات الهاتف |
| `walan-retail.html` | `en/walan-retail.html` | Walan Retail |
| `walan-gold.html` | `en/walan-gold.html` | Walan Gold |
| `pricing.html` | `en/pricing.html` | الأسعار |
| `terms.html` | `en/terms.html` | الشروط والأحكام |
| `privacy.html` | `en/privacy.html` | سياسة الخصوصية |

## 🚀 الرفع على GitHub ثم النشر عبر Vercel

### الخطوة 1 — امسح محتوى الـ repo القديم وارفع الجديد
```bash
# داخل مجلد الملفات المستخرجة من ZIP
git clone https://github.com/USERNAME/REPO.git
cd REPO
git rm -rf .
cp -r /path/to/extracted/walantech/* .
git add .
git commit -m "Update site: Arabic + English, full content refresh"
git push origin main
```

### الخطوة 2 — Vercel
إذا الـ repo مربوط مسبقًا بـ Vercel، بيسحب التحديث وينشره تلقائيًا بعد الـ push مباشرة.
إذا ما هو مربوط بعد: من لوحة Vercel اختر **Add New Project** → اختر نفس الـ repo → **Deploy**.

### الخطوة 3 — ربط الدومين
من إعدادات المشروع في Vercel → **Domains** → أضف الدومين الخاص بك واتبع تعليمات DNS اللي يعرضها Vercel.

## 📞 معلومات التواصل
- الهاتف: +966 53 071 1999
- الدعم: 9200-09925
- الإيميل: support@walantech.com
