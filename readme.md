# Установка голосовых пакетов для робота пылесоса

Позволяет установить русскую озвучку на устройства с вшитой китайской озвучкой.

## Поддерживаемые модели

* ijai.vacuum.v1
* ijai.vacuum.v2
* ijai.vacuum.v3

возможно и другие версии, нужно проверять...

## Инструкция

1. Установить [Mi Home vevs mod](https://www.vevs.me/2017/11/mi-home.html).
2. Через настройки телефона дать приложению разрешение на доступ к памяти.
3. В Mi Home зайти в профиль - экспериментальные функции и установить переключатель на "Выключить перехват DNS" и "Логировать полезные данные".
4. Перезапустить Mi Home.
5. В файлах телефона найти директорию /vevs/automations/ и добавить в нее файл модели вашего устройства из перечисленных:
   
   [ijai.vacuum.v1.json](https://github.com/Q0/ijai.vacuum/raw/master/ijai.vacuum.v1.json) для Xiaomi Mijia MJSTS1 Pro
   
   [ijai.vacuum.v2.json](https://github.com/Q0/ijai.vacuum/raw/master/ijai.vacuum.v2.json) для Xiaomi Mijia LDS Vacuum Cleaner Robot 2 MJST1S

   [ijai.vacuum.v3.json](https://github.com/Q0/ijai.vacuum/raw/master/ijai.vacuum.v3.json) для Xiaomi Mi Robot Vacuum mop 2 pro
   

6. В Mi Home зайти в автоматизации и создать конфигурацию. 
   
   Нажать на "+" в верхнем правом углу.
   
   Нажать на "Выполнить вручную".

   Нажать на умное устройство пылесос.
   
   Выбрать нужный пункт с озвучкой, например "~ Install RU voicepack".

7. Выполнить конфигурацию. Подождать 20 секунд и проверить.

## Голосовые пакеты

1. Английский
2. Китайский
3. Русский
4. Максим 18+ (кастомный пакет)