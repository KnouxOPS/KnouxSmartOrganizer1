# 🚀 بدء تشغيل سريع - Knoux SmartOrganizer PRO

## ⚡ تشغيل فوري (5 دقائق)

### 📋 المتطلبات

- Node.js 18+
- npm أو yarn أو pnpm
- متصفح حديث (Chrome, Firefox, Safari, Edge)

### 🏃‍♂️ البدء السريع

```bash
# 1. تثبيت التبعيات
npm install

# 2. تشغيل الخادم المحلي
npm run dev

# 3. فتح المتصفح على:
# http://localhost:5173
```

**🎉 مبروك! التطبيق يعمل الآن**

---

## 🧪 اختبار الميزات

### 📸 تجربة تحليل الصور

1. **انقر على زر "رفع الصور"** في الص��حة الرئيسية
2. **اختر صورة أو عدة صور** من جهازك
3. **شاهد التحليل الفوري** بالذكاء الاصطناعي:
   - 🎯 تصنيف الصورة
   - 👥 كشف الوجوه
   - 📝 استخراج النصوص
   - 🎨 تحليل الألوان
   - ⭐ تقييم الجودة
   - 🛡️ فحص المحتوى

### 📱 تجربة PWA (التطبيق المحمول)

1. **افتح التطبيق في Chrome/Edge**
2. **ابحث عن أيقونة التثبيت** في شريط العنوان
3. **انقر "تثبيت التطبيق"**
4. **استخدم التطبيق كتطبيق أصلي**

### 🖥️ تجربة نسخة سطح المكتب

```bash
cd knoux-smartorganizer-desktop
npm install
npm start
```

---

## 🎨 تخصيص سريع

### 🌈 تغيير الألوان

```css
/* في src/index.css */
:root {
  --primary: 250 84% 60%; /* اللون الأساسي */
  --secondary: 210 40% 98%; /* اللون الثانوي */
  --accent: 220 14.3% 95.9%; /* اللون المميز */
}
```

### ⚙️ إعدادات AI

```typescript
// في src/lib/ai-engine.ts
const defaultAiSettings = {
  runClassifier: true, // تفعيل التصنيف
  runFaceDetection: true, // تفعيل كشف الوجوه
  runOcr: true, // تفعيل استخراج النصوص
  runNsfw: true, // تفعيل فحص المحتوى
  nsfwThreshold: 0.5, // عتبة المحتوى الحساس
};
```

---

## 🔧 حل المشاكل السريع

### ❌ التطبيق لا يبدأ

```bash
# حذف node_modules وإعادة التثبيت
rm -rf node_modules package-lock.json
npm install
npm run dev
```

### 🐌 التطبيق بطيء

```bash
# تحسين الأداء
npm run build      # بناء للإنتاج
npm run preview    # معاينة الإنتاج
```

### 📱 PWA لا يعمل

1. تأكد من أن التطبيق يعمل على **HTTPS** أو **localhost**
2. تحقق من وجود **manifest.json** في مجلد public
3. افتح DevTools > Application > Service Workers

### 🧠 AI لا يعمل

1. تحقق من **اتصال الإنترنت** لتحميل النماذج
2. امنح **إذن الكاميرا** إذا كنت تستخدم التصوير
3. تأكد من أن المتصفح **يدعم WebGL**

---

## 📚 روابط مفيدة

- 📖 **الدليل الشامل:** [ULTIMATE_PROJECT_GUIDE.md](ULTIMATE_PROJECT_GUIDE.md)
- 📱 **إعداد التطبيق المحمول:** [mobile-app-setup.md](mobile-app-setup.md)
- 🏗️ **هيكل المشروع:** [CLAUDE.md](CLAUDE.md)
- 🐛 **الإبلاغ عن مشاكل:** GitHub Issues

---

## 🎯 الخطوات التالية

### 1. 🎨 تخصيص التصميم

- غيّر الألوان في `tailwind.config.ts`
- عدّل الخطوط في `index.css`
- أضف شعارك في `public/`

### 2. 🧠 تحسين AI

- اضبط إعدادات النماذج في `src/lib/ai-engine.ts`
- أضف نماذج جديدة في `src/core/`
- حسّن دقة التحليل

### 3. 📱 نشر التطبيق

- **Vercel:** `npm run build && vercel deploy`
- **Netlify:** `npm run build && netlify deploy`
- **GitHub Pages:** `npm run build && gh-pages -d dist`

### 4. 📲 بناء تطبيق محمول

```bash
npx cap add android
npm run build
npx cap sync
npx cap open android
```

---

<div align="center">

## 🎉 **تهانينا! أصبح لديك تطبيق متطور جاهز للاستخدام** 🎉

### استمتع بتجربة تنظيم الصور بالذكاء الاصطناعي!

[![بدء الاستخدام](https://img.shields.io/badge/بدء_الاستخدام-الآن-success?style=for-the-badge)](http://localhost:5173)

</div>
