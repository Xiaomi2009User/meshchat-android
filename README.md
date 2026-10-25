# MeshChat (Android)

Android-клієнт MeshChat на Capacitor. Відкриває сайт MeshChat, тож інтерфейс оновлюється без нового APK.

## Збірка
```
npm install
npx cap add android
npm run sync
npm run open
```
Далі в Android Studio: Build → Build APK(s).

Адресу сайту задано в `capacitor.config.json` (`server.url`).

## Підпис релізу
Ключ підпису (`*.keystore`, `*.jks`) не потрапляє в репозиторій. Зберігайте його окремо і в резервній копії: без нього не можна оновлювати застосунок у Google Play.
