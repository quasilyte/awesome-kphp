# Awesome KPHP

A curated list of amazingly awesome [KPHP](https://github.com/VKCOM/kphp/) libraries, resources and software.

## Table of Contents

* Libraries
  * [PHP polyfills](#php-polyfills)
  * [Libraries](#libraries)
  * [FFI Libraries](#ffi-libraries)
* Tools
  * [Developer tools](#developer-tools)
  * [Infrastructure tools](#infrastructure-tools)
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
* [quasilyte/KTemplate](https://github.com/quasilyte/KTemplate) - A simple text template engine with Twig-like syntax

### FFI libraries

FFI-based libraries. Usually can be used in both PHP and KPHP.

* [quasilyte/KLua](https://github.com/quasilyte/KLua) - liblua5 bindings to run Lua scripts on the fly
* [quasilyte/KSQLite](https://github.com/quasilyte/KSQLite) - fully functional SQLite3 bindings
* [quasilyte/kphp-sdlite](https://github.com/quasilyte/kphp-sdlite) - SDL2 bindings example

### Developer tools

Various CLI programs, editor/IDE plugins, language servers and so on. Everything that can make the KPHP developer life easier.

* [VKCOM/KPHPStorm](https://github.com/VKCOM/kphpstorm) - PhpStorm plugin that makes IDE understand KPHP specifics
* [VKCOM/ktest](https://github.com/VKCOM/ktest) - a tool to execute unit tests and benchmarks for KPHP
* [VKCOM/noverify](https://github.com/VKCOM/noverify) - a static analyzer (linter) that supports PHP and KPHP

### Infrastructure tools

Various tools that helps you to integrate the KPHP toolchain.

* [VKCOM/nocc](https://github.com/VKCOM/nocc) - A distributed C++ compiler: like distcc, but faster; works nicely with KPHP

### Games

Games created with KPHP.

* [quasilyte/kphp-game](https://github.com/quasilyte/kphp-game) - a simple rogue-like RPG game with 2D graphics (uses SDL2 for rendering)

### Articles (ru)

* [nocc — распределённый компилятор для гигантских проектов на С++](https://habr.com/ru/company/vk/blog/694536/)
* [Цветные функции: ищем плохие архитектурные паттерны](https://habr.com/ru/company/vk/blog/691828/)
* [Встраиваем Lua в PHP через FFI](https://habr.com/ru/company/vk/blog/681400/)
* [Используем SQLite в KPHP и PHP через FFI](https://habr.com/ru/post/653677/)
* [Создаём игру на KPHP с помощью FFI и SDL](https://habr.com/ru/company/vk/blog/581238/)
* [Пробуем KPHP: реально ли его использовать в своих проектах](https://php.zone/post/kphp-in-life)
* [Заметки KPHP: тестирование и бенчмарки](https://habr.com/ru/company/vk/blog/572424/)
* [ВКонтакте снова выкладывает KPHP](https://habr.com/ru/company/vk/blog/527420/)

### Talks (ru)

* [Разбор nocolor и концепции цветных функций в KPHP](https://www.youtube.com/watch?v=DCMp_FgEITwhttps://www.youtube.com/watch?v=DCMp_FgEITw)
* [nocc: распределённый компилятор, который быстрее distcc](https://www.youtube.com/watch?v=8v0HOMrGixY)
* [KPHP FFI](https://speakerdeck.com/quasilyte/kphp-ffi)
* [Плюсы и минусы компилируемого PHP](https://vk.com/wall-147415323_4677?z=video-147415323_456239083%2Fab939a83cc8e115d47%2Fpl_post_-147415323_4677)
* [PHP scripts -> Release binaries](https://www.youtube.com/watch?v=nr1883za8tM&t=306s)
* [KPHP внутри VK: что там у нас происходит](https://www.youtube.com/watch?v=3vO2TAkq7zE)

### Community

* <https://t.me/kphp_chat> - main KPHP users chat in Telegram
* <https://t.me/kphp_dev_blog> - KPHP developers blog (currently only in Russian)
