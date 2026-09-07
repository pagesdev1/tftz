# TFTZ LiveHub — Cloudflare Workers

نسخة جاهزة للنشر على Cloudflare Workers باستخدام GitHub + Workers Builds.

## هيكل المشروع

- `worker.js` — Worker و API لأحدث فيديوهات YouTube.
- `wrangler.jsonc` — إعدادات Worker و Static Assets.
- `public/` — كل ملفات الموقع والصور.
- `public/assets/` — صور TFTZ.

## إعداد Cloudflare Workers Builds

- Repository: `pagesdev1/tftz`
- Production branch: `main`
- Root directory: `/`
- Build command: اتركه فارغًا
- Deploy command: `npx wrangler deploy`

اسم الـ Worker في `wrangler.jsonc` هو `tftz-livehub`.

## مهم

ارفع **محتويات هذا المجلد كما هي** إلى جذر مستودع GitHub، وليس مجلد `TFTZ-LiveHub-Corrected` نفسه داخل المستودع.

الصور يجب أن تكون داخل:

`public/assets/avatar.png`
`public/assets/banner.png`
`public/assets/hero.png`
