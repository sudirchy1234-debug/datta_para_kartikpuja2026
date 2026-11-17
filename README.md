# সময় — কার্তিক পূজা ২০২৬

পশ্চিম বেতাগী দত্তপাড়া সার্বজনীন কার্তিক পূজা উদযাপন পরিষদ

## ফাইলের গঠন
- `index.html` — মূল পেজ (এটিই GitHub Pages খোলে)
- `css/style.css` — সব ডিজাইন
- `js/main.js` — সব কাজ ও লেখা। শুরুতে `CONTENT` অংশে লেখা, নাম, সময়সূচী, ভিডিও, অডিও ও ছবির তালিকা আছে
- `assets/` — ছবি, গান (`bgm.mp3`), কিউআর
- `.nojekyll` — GitHub Pages-এর জন্য

## GitHub Pages-এ চালু করা
1. নতুন Public repository খুলুন (যেমন `somoy`)।
2. জিপের ভেতরের সব ফাইল ও ফোল্ডার (`index.html`, `css`, `js`, `assets`, `.nojekyll`) repository-তে আপলোড করুন। জিপ ফাইলটি নিজে আপলোড করবেন না।
3. Settings → Pages → Deploy from a branch → `main` / `(root)` → Save।
4. ১–২ মিনিট পরে `https://আপনার-ইউজারনেম.github.io/somoy/` এ খুলবে।

## পরে কী যোগ করবেন
- ভিডিও: ফাইল `assets/` এ রেখে `js/main.js`-এর `CONTENT.videos`-এ লাইন যোগ করুন।
- অডিও: `CONTENT.audios`-এ লাইন যোগ করুন।
- মণ্ডপের ছবি/ভিডিও: `CONTENT.stage` (এ বছর) ও `CONTENT.memories` (আগের বছর)।
- সময়সূচী: `CONTENT.schedule`।
- কিউআর: লিংক চূড়ান্ত হলে নতুন কিউআর ছবি `assets/qr.png` এ বসিয়ে `index.html`-এ `qrbox`-এর `hidden` সরান।
