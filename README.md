# Royal AI — كهف الكريستال

خادم بايثون (Flask) يحسب توقعات الأسواق بـ RandomForest ويجلب الأخبار، ويقدّم كهف الكريستال ثلاثي الأبعاد (`index.html`) بأسعار حية من Binance.

## التشغيل
```
pip install -r requirements.txt
python royal_ai.py
```
ثم افتح `http://localhost:8000` في المتصفح.

> ملاحظة: فتح `index.html` وحده (أو عبر GitHub Pages) يعمل أيضاً، لكن التوقعات والأخبار تأتي حينها من محرك المتصفح بدل بايثون.
