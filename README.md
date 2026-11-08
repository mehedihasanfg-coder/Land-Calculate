# জমির হিসাব ক্যালকুলেটর — iPhone PWA

এই ফোল্ডারটি একটি Progressive Web App (PWA)। GitHub Pages-এ প্রকাশ করার পর iPhone-এর Safari থেকে Home Screen-এ যোগ করে অ্যাপের মতো ব্যবহার করা যাবে।

## Windows 11 থেকে প্রকাশ করার ধাপ

1. GitHub-এ সাইন ইন করুন।
2. একটি নতুন **Public** repository তৈরি করুন, নাম দিন `land-calculator`।
3. এই ZIP ফাইলটি extract করুন।
4. repository-তে **Add file → Upload files** চাপুন।
5. extract করা ফোল্ডারের ভেতরের সব ফাইল (index.html, manifest.webmanifest, service-worker.js, icon.svg, app-icon-192.png, app-icon-512.png, apple-touch-icon.png) upload করুন। ফোল্ডারটি নিজে upload করবেন না; ফাইলগুলো repository-র root-এ থাকতে হবে।
6. **Commit changes** চাপুন।
7. repository-র **Settings → Pages** খুলুন।
8. **Deploy from a branch** নির্বাচন করুন; Branch `main`, folder `/(root)` নির্বাচন করে Save চাপুন।
9. প্রকাশিত URL হবে `https://YOUR-USERNAME.github.io/land-calculator/` (YOUR-USERNAME-এর জায়গায় আপনার GitHub username)।

## iPhone-এ ইনস্টল

1. iPhone-এ Safari খুলুন।
2. GitHub Pages URL খুলুন।
3. Share বোতাম চাপুন।
4. **Add to Home Screen** নির্বাচন করুন।
5. **Add** চাপুন। Home Screen-এ অ্যাপের আইকন দেখা যাবে।

## ব্যবহার

- প্রথম ও দ্বিতীয় ঘরে মোট জমি ও আবেদনকৃত জমি লিখুন।
- প্রতিবার তৃতীয় ঘরে দাগের জমি লিখে লাল হিসাব বোতাম চাপুন।
- প্রতিটি হিসাবের পর তৃতীয় ঘর সঙ্গে সঙ্গে খালি হবে।
- সব তৃতীয় ঘরের ইনপুটের যোগফল প্রথম ঘরের সমান হলে সফলতার বার্তা আসবে।
- নীল reset বোতাম সব ঘর ও ফলাফল মুছে দেয়।

নোট: GitHub Pages-এর জন্য repository Public রাখুন। PWA install এবং offline cache কাজ করতে HTTPS প্রয়োজন; GitHub Pages HTTPS দেয়।
