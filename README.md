# حرفي - Harfi 🔧
## Service Finder App — Flutter

تطبيق موبايل للعثور على الحرفيين القريبين منك بسهولة.

---

## 📱 الشاشات
- **الرئيسية** — بحث + كاتيجوريز + كروت الحرفيين
- **تفاصيل الحرفي** — معلومات كاملة + تقييم + حجز
- **تأكيد الحجز** — وصف المشكلة + تأكيد
- **حجوزاتي** — قائمة الحجوزات ومتابعة الحالة
- **الملف الشخصي** — إعدادات + وضع داكن + تغيير اللغة

---

## 🎨 المميزات
- ✅ Dark Mode / Light Mode
- ✅ عربي / English (RTL + LTR)
- ✅ فلتر الحرفيين (الأقرب / الأعلى تقييماً / المتاح)
- ✅ بحث نصي
- ✅ حجز مع تأكيد مرئي
- ✅ اتصال مباشر بالحرفي
- ✅ حفظ الإعدادات (SharedPreferences)

---

## 🚀 تشغيل المشروع

### المتطلبات
- Flutter SDK >= 3.0.0
- Dart >= 3.0.0
- Android Studio أو VS Code

### خطوات التشغيل
```bash
# 1. فك ضغط المشروع
cd harfi

# 2. تحميل المكتبات
flutter pub get

# 3. تشغيل على المحاكي أو موبايل حقيقي
flutter run

# 4. بناء APK
flutter build apk --release
```

---

## 📦 المكتبات المستخدمة
| المكتبة | الاستخدام |
|---------|-----------|
| `provider` | State Management |
| `shared_preferences` | حفظ الإعدادات |
| `google_fonts` | خط Cairo الجميل |
| `flutter_rating_bar` | نجوم التقييم |
| `url_launcher` | الاتصال بالهاتف |
| `geolocator` | الموقع الجغرافي |

---

## 🗂️ هيكل المشروع
```
lib/
├── main.dart               ← نقطة البداية
├── models/
│   └── models.dart         ← Worker, Booking, ServiceCategory
├── providers/
│   └── app_provider.dart   ← State Management
├── theme/
│   ├── app_theme.dart      ← Dark/Light Theme
│   └── app_localizations.dart ← ترجمة عربي/إنجليزي
├── screens/
│   ├── main_app.dart       ← Bottom Navigation
│   ├── home_screen.dart    ← الشاشة الرئيسية
│   ├── worker_detail_screen.dart ← تفاصيل الحرفي
│   ├── booking_confirm_screen.dart ← تأكيد الحجز
│   ├── bookings_screen.dart ← حجوزاتي
│   └── profile_screen.dart ← الملف الشخصي
└── widgets/
    └── widgets.dart        ← WorkerCard, ServiceChip, TabBar
```

---

## 🔮 الخطوات القادمة (للنسخة الكاملة)
- [ ] Firebase Auth — تسجيل دخول
- [ ] Firestore — قاعدة بيانات حقيقية
- [ ] Google Maps — خريطة تفاعلية
- [ ] Push Notifications — إشعارات
- [ ] Payment Gateway — دفع إلكتروني
- [ ] Chat — محادثة مع الحرفي
