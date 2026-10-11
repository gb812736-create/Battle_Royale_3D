BATTLE ROYALE 3D BD — মোবাইল-ফ্রেন্ডলি 3D Web Prototype
==========================================================

এই ZIP-এ আছে:
- web/index.html : Three.js দিয়ে বানানো 3D third-person arena prototype
- বাস্তব 3D scene, player character, bot enemies, camera, trees/rocks, shooting,
  ammo/reload, med/ammo loot, shrinking safe zone, minimap, touch controls
- README_BN.txt : বাংলা নির্দেশনা

চালানোর জন্য
1. ZIP Extract করো।
2. Android ফোনে এই HTML ফাইলটি সরাসরি local file হিসেবে খোলার বদলে web/index.html-কে
   HTTPS static hosting-এ প্রকাশ করো (যেমন GitHub Pages বা Netlify), কারণ Three.js
   CDN থেকে module হিসেবে লোড হয়।
3. প্রকাশিত HTTPS লিংক Chrome-এ খোলো এবং "ম্যাচ শুরু" চাপো।
4. কম্পিউটারে একই HTTPS পেজ খুলে WASD/arrow keys, Space=fire, R=reload ব্যবহার করো।
5. মোবাইলে স্ক্রিনের নিচের তীর, FIRE এবং RELOAD বোতাম ব্যবহার করো।

Android APK সম্পর্কে
- এই ZIP-এ APK নেই; APK build করা হয়নি।
- শুধু Android ফোন দিয়ে পূর্ণ native APK build করা কঠিন; Android Studio চালানোর মতো
  কম্পিউটার বা cloud build service দরকার।
- চাইলে পরের ধাপে Capacitor wrapper source যোগ করা যাবে; তারপর Android build করতে হবে।

সীমাবদ্ধতা
- এটি playable 3D single-player prototype; প্রকৃত online multiplayer নয়।
- bot AI সহজ, shooting simplified; অস্ত্রের inventory, parachute drop, lobby,
  accounts, server, anti-cheat, matchmaking, production optimization নেই।
- এটি Free Fire-এর সম্পদ/চরিত্র/ম্যাপ কপি করে না; নিজস্ব prototype।
- CDN ব্যবহারের জন্য প্রথম লোডে internet লাগবে।
