# SAMMAAN APP — Android Starter Project

Kun pirojektii jalqabaa Android Studio keessatti banamuudha. Dizaayini Navy Blue + Gold,
seenaa dubbisuu, gosa seenaa filachuu fi adminiin seenaa maxxansuu qaba.

## Wanti amma hojjetu
- Fuula jalqabaa SAMMAAN APP
- Gosa seenaa: Jireenya, Jaalala, Gaddaa
- Seenaa dubbisuu
- Firebase waliin yoo qindaa'e seenaawwan Firestore irraa dubbisa
- Admin Firebase Authentication'n seenee seenaa maxxansuu danda'a

## Wanti si barbaachisu
1. Kompiitara irratti Android Studio.
2. Firebase project (firebase.google.com).
3. Android app Firebase keessatti galmeessi; package name: `com.sammaan.app`.
4. `google-services.json` buusiitii gara `app/` keessa kaa'i.
5. Firebase Authentication keessatti Email/Password enable godhi; account admin uumi.
6. Cloud Firestore database uumi.
7. Firebase Console keessatti Authentication > Users irraa UID admin ilaali.
8. `firestore.rules` keessatti `REPLACE_WITH_YOUR_ADMIN_UID` bakka UID admin keetiin jijjiiri; rules publish godhi.
9. Android Studio keessatti pirojektii bani; Gradle sync godhi.
10. Build > Build APK(s) filadhu. APK: `app/build/outputs/apk/debug/app-debug.apk`

## Hubachiisa barbaachisaa
- Pirojektiin kun APK qophaa'e miti; source project Android Studio dha.
- `google-services.json` fi UID admin kan nama dhuunfaa waan ta'aniif si irraa barbaachisu; isaan malee maxxansi addunyaa guutuu hin hojjetu.
- Admin UID Firebase rules keessatti mirkanaa'a; password app keessa hin kaa'amu.
- Seenaawwan fakkeenyaa app keessatti argaman agarsiisa qofa; seenaawwan online Firebase irraa dhufu.
