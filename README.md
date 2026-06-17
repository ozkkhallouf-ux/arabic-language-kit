# arabic-language-kit
مكتبة شاملة لدعم اللغة العربية في تطبيقات الويب 

## 📖 نظرة عامة

**arabic-language-kit** مكتبة قوية وسهلة الاستخدام توفر حلولاً متكاملة لدعم اللغة العربية في تطبيقات الويب، بما في ذلك:

- ✅ معالجة النصوص العربية
- ✅ التحقق من صحة الأحرف العربية
- ✅ تحويل الأرقام والتواريخ
- ✅ معالجة الكلمات المفتاحية والعلامات
- ✅ دعم الاتجاه (RTL/LTR)

## 🚀 المميزات

- دعم كامل للنصوص العربية
- أداء عالي وسهل الاستخدام
- توافق مع جميع المتصفحات الحديثة
- موثق بشكل كامل مع أمثلة عملية
- مرخص تحت MIT

## 📦 التثبيت

### باستخدام npm

```bash
npm install arabic-language-kit
```

### باستخدام yarn

```bash
yarn add arabic-language-kit
```

## 🔧 الاستخدام الأساسي

### التحقق من النص العربي

```javascript
import { isArabic } from 'arabic-language-kit';

const text = "السلام عليكم";
console.log(isArabic(text)); // true
```

### تنظيف النص العربي

```javascript
import { cleanArabicText } from 'arabic-language-kit';

const text = "السلام   عليكم";
const cleaned = cleanArabicText(text);
console.log(cleaned); // "السلام عليكم"
```

### تحويل الأرقام

```javascript
import { arabicToEnglish, englishToArabic } from 'arabic-language-kit';

console.log(arabicToEnglish("١٢٣")); // "123"
console.log(englishToArabic("123")); // "١٢٣"
```

## 📚 التوثيق الكاملة

### الدوال المتاحة

#### `isArabic(text)`
التحقق مما إذا كان النص يحتوي على أحرف عربية.

```javascript
isArabic("مرحبا") // true
isArabic("Hello") // false
```

#### `cleanArabicText(text)`
تنظيف النص من المسافات الإضافية والعلامات غير المرغوبة.

```javascript
cleanArabicText("السلام   عليكم") // "السلام عليكم"
```

#### `arabicToEnglish(number)`
تحويل الأرقام العربية إلى إنجليزية.

```javascript
arabicToEnglish("١٢٣") // "123"
```

#### `englishToArabic(number)`
تحويل الأرقام الإنجليزية إلى عربية.

```javascript
englishToArabic("123") // "١٢٣"
```

## 🤝 المساهمة

نرحب بمساهماتكم! يرجى اتباع الخطوات التالية:

1. Fork المستودع
2. إنشاء فرع جديد (`git checkout -b feature/amazing-feature`)
3. Commit التغييرات (`git commit -m 'Add amazing feature'`)
4. Push إلى الفرع (`git push origin feature/amazing-feature`)
5. فتح Pull Request

## 📝 الترخيص

هذا المشروع مرخص تحت رخصة MIT - انظر ملف [LICENSE](LICENSE) للتفاصيل.

## 👨‍💻 المؤلف

**ozkkhallouf-ux**
- GitHub: [@ozkkhallouf-ux](https://github.com/ozkkhallouf-ux)

## 📧 التواصل

إذا كان لديك أسئلة أو اقتراحات، لا تتردد في فتح issue أو إرسال رسالة.

---

صنع بـ ❤️ من قبل ozkkhallouf-ux
