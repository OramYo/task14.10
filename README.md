# האתר האישי של אורם יוסף

מעבדת פריסה אוטומטית של אתר סטטי באמצעות GitHub Actions ו־GitHub Pages.

- האתר: https://oramyo.github.io/task14.10/
- הקוד: https://github.com/OramYo/task14.10
- הרצות: https://github.com/OramYo/task14.10/actions

## מבנה

- `index.html` — שם, תיאור אישי וקישורים.
- `style.css` — עיצוב הדף, כולל התאמה לעברית ולטלפון.
- `.github/workflows/deploy.yml` — פריסה אוטומטית בכל Push ל־main; ניתן להפעיל גם ידנית.
- `.nojekyll` — האתר מוגש כקבצים סטטיים.

## תהליך הפריסה

Checkout → Setup Pages → Upload Artifacts → Deploy to GitHub Pages.

ב־Settings → Pages יש לבחור GitHub Actions כמקור הפריסה. הצלחת הפריסה מאומתת בלשונית Actions ובכתובת האתר החי.

מבוסס על [תבנית boxbot6](https://github.com/boxbot6/website-template-simple-single-page-v1), ברישיון MIT המצורף.
