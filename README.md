# Magic Motion Camera

Telefon va kompyuter brauzerlarida ishlaydigan qo‘l ishorasi demo-loyihasi.

## Ishga tushirish
1. `index.html` faylini GitHub repository'ga yuklang.
2. Repository → **Settings** → **Pages** bo‘limiga kiring.
3. **Deploy from a branch** ni tanlang.
4. Branch: `main`, folder: `/ (root)` → **Save**.
5. Bir oz kutib, GitHub Pages bergan HTTPS manzilini oching.
6. **Kamerani yoqish** tugmasini bosing va kamera ruxsatini bering.

## Muhim
- MediaPipe kutubxonasi va modeli CDN orqali yuklanadi, shuning uchun internet kerak.
- Kamera odatda HTTPS manzilida yoki `localhost`da ishlaydi.
- Brauzerda kamera ruxsatini bering; yorug‘ joyda sinab ko‘ring.
- Bu prototipda neon zarralar va halqa Canvas orqali chiziladi. Keyin Three.js bilan haqiqiy 3D modellar qo‘shish mumkin.
