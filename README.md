# حرفي | Harfi App 🔨

منصة الحرفيين الموثوقة — Trusted Craftsmen Platform

## المميزات | Features

- ✅ **23 حرفي** مدمجين في الكود (سباكة، كهرباء، ميكانيكي، تكييف، دهانات، نجارة، بناء)
- 🌙☀️ **دارك / لايت مود** — Dark / Light Mode
- 🌍 **عربي / إنجليزي** — Arabic / English
- 📋 **حجز فوري** مع حفظ محلي (localStorage)
- 💬 **دردشة** مع رد تلقائي من الحرفي
- 📍 **تتبع الحجز** بشريط التقدم
- 👤 **ملف شخصي** قابل للتعديل
- 📱 **Responsive** — موبايل وديسكتوب

## تجربة الحساب التجريبي
```
Email: demo@harfi.app
Password: demo1234
```

---

## 🚀 نشر على Vercel (3 طرق)

### الطريقة 1 — Drag & Drop (الأسهل)
1. افتح [vercel.com](https://vercel.com) وسجل دخول
2. اضغط **"Add New Project"**
3. اضغط **"Import Git Repository"** أو **"Upload"**
4. ارفع مجلد `harfi-vercel` كاملاً
5. اضغط **Deploy** — خلاص! ✅

### الطريقة 2 — GitHub + Vercel (الأفضل للتحديث)
```bash
# 1. ارفع على GitHub
git init
git add .
git commit -m "🔨 Harfi App"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/harfi-app.git
git push -u origin main

# 2. على vercel.com → Import from GitHub → اختر الـ repo
# 3. اضغط Deploy
```

### الطريقة 3 — Vercel CLI
```bash
# ثبّت Vercel CLI
npm i -g vercel

# داخل مجلد harfi-vercel
cd harfi-vercel
vercel

# اتبع التعليمات، ثم:
vercel --prod
```

---

## 🏃 تشغيل محلي
```bash
# بدون تثبيت — افتح مباشرة
open public/index.html

# أو مع serve
npx serve public
# ثم افتح: http://localhost:3000
```

---

## 📁 هيكل الملفات
```
harfi-vercel/
├── public/
│   └── index.html      ← التطبيق كاملاً (React + Data)
├── vercel.json         ← إعدادات Vercel
├── package.json
└── README.md
```

---

> تطبيق مبني بـ React (CDN) — لا يحتاج build أو تثبيت أي شيء
