# Awesome KPHP

A curated list of amazingly awesome [KPHP](https://github.com/VKCOM/kphp/) libraries, resources and software.

> Note: this list is a work in progress, but stay tuned!

## Table of Contents

* [PHP polyfills](#php-polyfills)
* [Developer tools](#developer-tools)
* [Games](#games)
* [Articles (ru)](#articles)
* [Talks (ru)](#talks)
  
### PHP polyfills

Libraries that can help to reduce the feature gap between the KPHP and PHP.

For example, some builtin PHP extensions that are written in C can be implemented in PHP.
That PHP library can be used as a KPHP polyfill so it can use that functionallity even without
a C library port.

* [kphp-polyfills](https://github.com/VKCOM/kphp-polyfills) - use KPHP-specific functions from PHP

### Developer tools

Various CLI programs, editor/IDE plugins, language servers and so on. Everything that can make the KPHP developer life easier.

* [KPHPStorm](https://github.com/unserialize/kphpstorm) - PhpStorm plugin that makes IDE understand KPHP specifics
* [ktest](https://github.com/VKCOM/ktest) - a tool to execute unit tests and benchmarks for KPHP

### Games

Games created with KPHP.

* [quasilyte/kphp-game](https://github.com/quasilyte/kphp-game) - a simple rogue-like RPG game with 2D graphics (uses SDL2 for rendering)

### Articles (ru)

* [Пробуем KPHP: реально ли его использовать в своих проектах](https://php.zone/post/kphp-in-life)
* [Заметки KPHP: тестирование и бенчмарки](https://habr.com/ru/company/vk/blog/572424/)
* [ВКонтакте снова выкладывает KPHP](https://habr.com/ru/company/vk/blog/527420/)

### Talks (ru)

* [Плюсы и минусы компилируемого PHP](https://vk.com/wall-147415323_4677?z=video-147415323_456239083%2Fab939a83cc8e115d47%2Fpl_post_-147415323_4677)
* [PHP scripts -> Release binaries](https://www.youtube.com/watch?v=nr1883za8tM&t=306s)
* [KPHP внутри VK: что там у нас происходит](https://www.youtube.com/watch?v=3vO2TAkq7zE)
