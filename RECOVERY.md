# RECOVERY — שיתוף מסך

- **מקור:** `C:\SCREENSHARE`, מאגר git, ענף `main`.
- **פריסה:** GitHub Pages מהענף `main`, מאגר `6435786/screenshare`. כתובת: https://6435786.github.io/screenshare/
- **תלויות חיצוניות:**
  - שרת התיווך הציבורי של PeerJS (`0.peerjs.com`). אם ייפול: להעלות שרת PeerJS משלנו (`npm i -g peer`) או לעבור לתיווך דרך Supabase Realtime, ולעדכן את `newPeer()` ב-`index.html`.
  - TURN חינמי של Open Relay (`openrelay.metered.ca`). אם ייפול, השיתוף עדיין יעבוד ברוב הרשתות דרך STUN בלבד. חלופה: חשבון חינמי ב-metered.ca עם פרטי TURN משלנו.
- **אין נתונים, אין DB, אין משתמשים.** שחזור = clone ו-push מחדש.
