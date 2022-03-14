# Awesome KPHP

A curated list of amazingly awesome [KPHP](https://github.com/VKCOM/kphp/) libraries, resources and software.

> Note: this list is a work in progress, but stay tuned!

## Table of Contents

* Libraries
  * [PHP polyfills](#php-polyfills)
  * [Libraries](#libraries)
  * [FFI Libraries](#ffi-libraries)
* [Developer tools](#developer-tools)
* [Games](#games)
* Learning materials
  * [Articles (ru)](#articles-ru)
  * [Talks (ru)](#talks-ru)
* [Community](#community)
  
### PHP polyfills

Libraries that can help to reduce the feature gap between the KPHP and PHP.

For example, some builtin PHP extensions that are written in C can be implemented in PHP.
That PHP library can be used as a KPHP polyfill so it can use that functionallity even without
a C library port.

* [VKCOM/kphp-polyfills](https://github.com/VKCOM/kphp-polyfills) - use KPHP-specific functions from PHP

### Libraries

Libraries that work in both PHP and KPHP.

* [quasilyte/KFinalize](https://github.com/quasilyte/KFinalize) - `register_shutdown_function()` without limits

### FFI libraries

FFI-based libraries. Usually can be used in both PHP and KPHP.

* [quasilyte/KSQLite](https://github.com/quasilyte/KSQLite) - fully functional SQLite3 bindings
* [quasilyte/kphp-sdlite](https://github.com/quasilyte/kphp-sdlite) - SDL2 bindings example

### Developer tools

Various CLI programs, editor/IDE plugins, language servers and so on. Everything that can make the KPHP developer life easier.

* [unserialize/KPHPStorm](https://github.com/unserialize/kphpstorm) - PhpStorm plugin that makes IDE understand KPHP specifics
* [VKCOM/ktest](https://github.com/VKCOM/ktest) - a tool to execute unit tests and benchmarks for KPHP

### Games

Games created with KPHP.

* [quasilyte/kphp-game](https://github.com/quasilyte/kphp-game) - a simple rogue-like RPG game with 2D graphics (uses SDL2 for rendering)

### Articles (ru)

* [Создаём игру на KPHP с помощью FFI и SDL](https://habr.com/ru/company/vk/blog/581238/)
* [Пробуем KPHP: реально ли его использовать в своих проектах](https://php.zone/post/kphp-in-life)
* [Заметки KPHP: тестирование и бенчмарки](https://habr.com/ru/company/vk/blog/572424/)
* [ВКонтакте снова выкладывает KPHP](https://habr.com/ru/company/vk/blog/527420/)

### Talks (ru)

* [Используем SQLite в KPHP и PHP через FFI](https://habr.com/ru/post/653677/)
* [KPHP FFI](https://speakerdeck.com/quasilyte/kphp-ffi)
* [Плюсы и минусы компилируемого PHP](https://vk.com/wall-147415323_4677?z=video-147415323_456239083%2Fab939a83cc8e115d47%2Fpl_post_-147415323_4677)
* [PHP scripts -> Release binaries](https://www.youtube.com/watch?v=nr1883za8tM&t=306s)
* [KPHP внутри VK: что там у нас происходит](https://www.youtube.com/watch?v=3vO2TAkq7zE)

### Community

* <https://t.me/kphp_chat> - main KPHP users chat in Telegram
