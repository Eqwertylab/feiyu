Sjcam template
==============

Использование
-------------

### Для разработки

Возможно удобнее будет использовать исходники. Берем файлы из src и используем как есть. Папку `src/less` на сервер можно не заливать. Исходные стили в `src/less/**/*.less`. Для компиляции используется Grunt. Команда `grunt watch:theme` запускает вотчер который компилирует less в css. При этом можно редактировать след. файлы:

  * theme.less
  * theme-base.less
  * theme-sm.less
  * theme-md.less
  * theme-lg.less

### Продакшн

Для сборки билда команда `grunt build` при этом объединяются и сжимаются все .css и .js файлы. Результат попадает в папку `build`.