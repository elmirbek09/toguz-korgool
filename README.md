# Тогуз коргоол / Toguz Korgool

**Кыргызча · Русский · English**

Национальная игра кыргызов в одном файле `index.html`, без сборки и без сервера.
A traditional Kyrgyz board game in a single `index.html`: no build step, no server.

## Режимы / Modes

- Против компьютера (3 уровня) / vs computer (3 levels): works offline
- Двое на одном устройстве / two players, one device: works offline
- Онлайн по коду комнаты / online by room code (peer-to-peer, WebRTC via PeerJS): needs internet

## Запуск / Run

Откройте `index.html` в браузере. / Open `index.html` in a browser.

## Публикация на GitHub Pages / Publish on GitHub Pages

1. Создайте репозиторий и загрузите `index.html` и `README.md`. / Create a repo and upload both files.
2. Settings → Pages → Source: `main` branch, folder `/ (root)`.
3. Игра откроется по адресу `https://<user>.github.io/<repo>/`. / The game will be live at that URL.

## Язык / Language

Кнопки вверху страницы: Кыргызча, Русский, English. Выбор запоминается в браузере.
Переводы находятся в объекте `T` в начале скрипта: добавить язык или поправить текст можно там.
