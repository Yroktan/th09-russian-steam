# Авторы и сторонние компоненты

Этот пакет объединяет существующие материалы Touhou Patch Center с установочными скриптами для Steam-версии TH09.

## Игра

Touhou Project и Touhou Kaeizuka — Phantasmagoria of Flower View принадлежат Team Shanghai Alice / ZUN. Steam-издание выпущено Mediascape. Файлы оригинальной игры не входят в пакет.

## Перевод

Русский перевод, переведённые изображения и шрифтовые материалы получены из `thpatch/lang_ru`; резервный английский перевод — из `thpatch/lang_en`.

Источники:

- https://www.thpatch.net/wiki/Portal:Ru
- https://srv.thpatch.net/lang_ru/
- https://srv.thpatch.net/lang_en/

Авторство и применимые условия этих материалов сохраняются за исходными авторами. Пакет не объявляет сторонние переводные изображения и шрифты своей оригинальной работой и не перелицензирует их.

## Движок и библиотеки

- thcrap и win32_utf8: https://github.com/thpatch/thcrap — Unlicense; полный текст в `licenses/thcrap-UNLICENSE.txt`.
- Jansson: https://github.com/akheron/jansson — полный текст в `licenses/jansson-LICENSE.txt`.
- libpng: https://github.com/pnggroup/libpng — полный текст в `licenses/libpng-LICENSE.txt`.
- zlib-ng: https://github.com/zlib-ng/zlib-ng — полный текст в `licenses/zlib-ng-LICENSE.md`.

Используется 32-битная версия thcrap `2026-10-21`. Файл `runtime/bin/update.json` содержит пустой список: миграции предыдущих установок для нового автономного каталога не нужны. Онлайн-обновлятор не включён; бинарный код движка не изменялся.

Точный состав и SHA-256 ресурсов перечислены в `payload-manifest.json`; происхождение файлов перевода — в `translation-sources.json`. Лицензионные сведения, встроенные в шрифты, дополнительно сохранены в `licenses/font-metadata.txt`.
