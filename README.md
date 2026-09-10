# LOODY’S SPOT AI v9.1.2

منصة تحليل ومراقبة Binance Spot فقط، مع وضع محاكاة/مراقبة فقط. لا توجد أوامر حقيقية أو رافعة أو Futures أو Margin أو سحب، ولا يتم تخزين مفاتيح API.

## الحالة
- الإصدار المرجعي: v9.1.2
- الفرع الرئيسي: `main`
- مصدر البيانات: Binance Spot public API
- مهلة طلبات الخادم: 9 ثوانٍ مع مرايا متعددة لـ Binance
- Opportunity Engine يعمل ضمن حدود المخاطر ولا يفترض زيادة عدد الصفقات لمجرد زيادة الفرص.

## البنية
- `src/index.js` — Cloudflare Worker API
- `public/` — واجهة التطبيق والـ engines
- `wrangler.jsonc` — إعداد Cloudflare Workers
- `capacitor.config.json` — إعداد تطبيق Android/Capacitor

> ملاحظة: هذا المستودع هو المرجع الأساسي للإصدارات القادمة. يجب اختبار كل تغيير قبل نشره إلى Cloudflare.
