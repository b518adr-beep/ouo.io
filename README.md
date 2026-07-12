# التقنية والأناقة — Portfolio

تتضمن الحزمة نسختين:

- `index.html`: نسخة مستقلة تعمل مباشرة دون تثبيت.
- `react/`: نسخة React + TypeScript متقدمة.
- `ANTIGRAVITY_PROMPT.txt`: برومبت مختصر ومحسن لمنصة Antigravity.

## تشغيل نسخة HTML

افتح `index.html` في المتصفح، أو ارفعه مباشرة إلى Netlify أو GitHub Pages أو استضافة cPanel.

## تشغيل نسخة React على Replit

1. أنشئ Repl جديدًا من نوع Node.js.
2. ارفع محتويات مجلد `react` إلى المشروع.
3. نفّذ `npm install`.
4. نفّذ `npm run dev`.
5. أمر البناء للإنتاج: `npm run build`.

## التعديل

- بيانات خدمات ومشاريع نسخة HTML موجودة في الكائن `DATA` قرب نهاية `index.html`.
- بيانات نسخة React موجودة أعلى `react/src/main.tsx`.
- استبدل حرف B داخل الإطار بصورة شخصية باستخدام عنصر `img` مع `object-fit: cover`.

## النشر

- Replit: استخدم أمر البناء `npm run build` ومجلد الإخراج `dist`.
- Vercel/Netlify: حدّد `react` كمجلد المشروع، وأمر البناء `npm run build`، ومجلد النشر `dist`.
