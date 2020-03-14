# BufferStructCircular #
# Модуль буфера структурного кольцевого <br> и программа тестирования #

## Установка ##

Модуль был разработан и протестирован в Visual Studio 2015, поэтому установите Visual Studio версии не ниже 2015.

## Запуск ##

### Всё просто! ###
* Добавляете модуль "БуферСтруктурныйКольцевой.cs" в ваш проект
* Добавляете `using ОбластьБуфераСтруктурногоКольцевого;` в файл, который будет его использовать
* Создаёте экзепляр класса с указанием размера буфера. 
Например так : 

`КлассБуфераСтруктурногоКольцевого ОбъектБуфераСтруктурногоКольцевого =`

  `new КлассБуфераСтруктурногоКольцевого(1024);`
* Записывайте данные: 

`ОбъектБуфераСтруктурногоКольцевого.ЗаписатьСтруктурувБуфер(datatx)`
* Считывайте данные: 

`if (ОбъектБуфераСтруктурногоКольцевого.ПустЛиБуфер())`

  `ОбъектБуфераСтруктурногоКольцевого.ЗабратьСтруктуруИзБуфера(out datarx)`
