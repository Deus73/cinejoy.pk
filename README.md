# Cinejoy voor Android en iOS

Een eenvoudige WebView voor https://cinejoy.pk/ met een Android TV-starttegel en ondersteuning voor schermvullende video. De website en externe videospelers worden online geladen. Dit is een onafhankelijk project en geen officiële app van Cinejoy.

## Installatie

- **Android / Android TV:** installeer `Cinejoy-Android-TV.apk` op Android 6.0 of hoger. Voor handmatige installatie moet de installatiebron voor APK-bestanden op het toestel toegestaan zijn.
- **iPhone / iPad:** open `Cinejoy-iOS.mobileconfig` op het toestel, ga naar **Instellingen → Profiel gedownload** en installeer het profiel. Het plaatst een verwijderbare webclip op het beginscherm. Het profiel is niet ondertekend.

De bediening en het afspelen zijn afhankelijk van de website, externe spelers en de WebView-versie op het apparaat. Niet alle externe spelers zijn geschikt voor afstandsbedieningen of Android WebView. Internet is vereist.

## Bouwen

Installeer Android SDK platform 35, build-tools 35.0.0 en JDK 17 of hoger. Voer `./build.sh` uit. De lokale buildsleutel wordt aangemaakt in `~/.android/cinejoy-debug.keystore`. Bewaar dezelfde sleutel om updates over een eerder geïnstalleerde versie te kunnen installeren. Deze sleutel is bedoeld voor lokale builds; gebruik een eigen beveiligde ondertekenprocedure voor distributie.
