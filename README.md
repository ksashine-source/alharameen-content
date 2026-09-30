# AL-HARAMEEN — app content mirror

This repository holds only the downloadable content used by the AL-HARAMEEN app
(adhan and adhkar recordings, Hisn al-Muslim audio, Quran translations, reciter timings,
content manifests). It contains no source code.

The app downloads from the owner's server first (https://api.al-harameen.app) and uses this
mirror, served through jsDelivr, only when a file is not available there.

Layout mirrors the server paths: `content/v2/...` and `audio/v2/...`.
Every file is checked by the app against the SHA-256 in `content/v2/CONTENT_MANIFEST.json`
and `audio/v2/AUDIO_MANIFEST.json`.

© AL-HARAMEEN. All rights reserved. Quran text attribution: Tanzil Project (tanzil.net).

---

# الحرمين — مرآة محتوى التطبيق
يحوي هذا المستودع ملفات التنزيل فقط التي يستخدمها تطبيق الحرمين (الأذان والأذكار وحصن المسلم
وترجمات القرآن وتوقيتات القرّاء)، ولا يحوي أي كود. التطبيق ينزّل من خادم الحرمين أولاً، ويستعمل
هذه المرآة احتياطاً فقط. © الحرمين، جميع الحقوق محفوظة.
