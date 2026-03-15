# TODO: إصلاح مشاكل الباركود والتقارير - خطة التنفيذ

## الخطوات المكتملة
- [x] إنشاء ملف TODO.md لتتبع التقدم
- [x] قراءة الملفات الرئيسية (index.html, script.js, style.css)

## الخطوات المتبقية

1. **تعديل index.html**: ✅
   - [x] إضافة قسم صفحة الباركود المنفصلة (full-screen).
   - [x] تحديث زرار المسح للانتقال للصفحة الجديدة (`onclick="showBarcodePage()"`).
   - [x] إضافة sidebar link لصفحة الباركود.

2. **إصلاح script.js**: ✅
   - [x] إضافة `showBarcodePage()`, `registerBarcodeAttendance()` مع التحقق من `selectedPart`.
   - [x] إصلاح scanner مع try-catch، permissions، proper event binding.
   - تظبيط downloads (add click handlers، fallback alerts).

3. **تعديل style.css**: ✅
   - [x] Full-screen styles لـ `#barcode-page-section` مع animations.

4. **اختبار وإكمال**.

**ملاحظات**:
- المنطق الحالي لا يضيف طلاب جدد من باركود (يبحث فقط في `students` ✅).


