# RECOVERY — שיתוף מסך

- **מקור:** `C:\SCREENSHARE`, מאגר git, ענף `main`.
- **פריסה:** GitHub Pages מהענף `main`, מאגר `6435786/screenshare`. כתובת: https://6435786.github.io/screenshare/
- **תלויות חיצוניות:**
  - שרת התיווך הציבורי של PeerJS (`0.peerjs.com`). אם ייפול: להעלות שרת PeerJS משלנו (`npm i -g peer`) או לעבור לתיווך דרך Supabase Realtime, ולעדכן את `newPeer()` ב-`index.html`.
  - שרת ממסר (TURN) של metered.ca: אפליקציה `screenshare6435786`, תוכנית חינמית TURN TRIAL GLOBAL 500MB, מתחדשת ב-10 בכל חודש, בלי אמצעי תשלום. לוח בקרה: dashboard.metered.ca, עמוד TURN Server. פרטי החיבור ב-`index.html` (`TURN_USER` / `TURN_PASS`). אם המכסה נגמרת או שהתוכנית נסגרת: בלי ממסר החיבור נכשל ברשתות שחוסמות חיבור ישיר. להחלפה: ליצור Credential חדש שם ולעדכן את שני המשתנים.
- **אין נתונים, אין DB, אין משתמשים.** שחזור = clone ו-push מחדש.
