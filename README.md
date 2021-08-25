# Awesome KPHP

A curated list of amazingly awesome [KPHP](https://github.com/VKCOM/kphp/) libraries, resources and software.

> Note: this list is a work in progress, but stay tuned!

## Table of Contents

[PHP polyfills](#php-polyfills)

[Developer tools](#developer-tools)

* [KPHPStorm](#kphpstorm---phpstorm-plugin-that-makes-ide-understand-kphp-specifics)
* [ktest](#ktest---a-tool-to-execute-unit-tests-and-benchmarks-for-kphp)

[Articles](#articles)

[Talks](#talks)
  
### PHP polyfills

Libraries that can help to reduce the feature gap between the KPHP and PHP.

For example, some builtin PHP extensions that are written in C can be implemented in PHP.
That PHP library can be used as a KPHP polyfill so it can use that functionallity even without
a C library port.

### Developer tools

Various CLI programs, editor/IDE plugins, language servers and so on. Everything that can make the KPHP developer life easier.

#### [KPHPStorm](https://github.com/unserialize/kphpstorm) - PhpStorm plugin that makes IDE understand KPHP specifics

#### [ktest](github.com/quasilyte/ktest) - a tool to execute unit tests and benchmarks for KPHP

### Articles

* [Пробуем KPHP: реально ли его использовать в своих проектах](https://php.zone/post/kphp-in-life)
* [Заметки KPHP: тестирование и бенчмарки](https://habr.com/ru/company/vk/blog/572424/)
* [ВКонтакте снова выкладывает KPHP](https://habr.com/ru/company/vk/blog/527420/)

### Talks

* [PHP scripts -> Release binaries](https://www.youtube.com/watch?v=nr1883za8tM&t=306s)
* [KPHP внутри VK: что там у нас происходит](https://www.youtube.com/watch?v=3vO2TAkq7zE)
