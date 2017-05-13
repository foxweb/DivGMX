# Базовая конфигурация (сборка 20170513)
Конфигурация для DivGMX, расширяющая аппаратные возможности ZX Spectrum и клонов.

Назначение:
- Простое подключение ZX Spectrum и его клонов к современному ТВ или монитору через HDMI
- Подключение USB клавиатуры
- Подключение USB мыши
- Работа с файлами на microSD
- Расширение звуковых возможностей

Совместимость:
- ZX Bus
- Nemo Bus

Поддержка в конфигурации:
- HDMI 640x480@60Hz
- Audio out
- K-Mouse Turbo http://velesoft.speccy.cz/kmsoft.htm
- DivMMC (ROM 8K + RAM 512K) NMI кнопка на плате http://www.esxdos.org/
- SounDrive http://velesoft.speccy.cz/da_for_zx-cz.htm
- Turbo Sound Easy (2x AY-3-8912 + SAA1099 (12 channels stereo)) http://velesoft.speccy.cz/turbosound-cz.htm
- Z-Controller http://speccy.info/Z-Controller

При подключенной USB клавиатуре:
F6 = DivMMC/Z-Controller (по включению)
F7 = USB Keyboard/ZX Spectrum Keyboard (по включению) 


- ZXM-Phoenix 1024K (вывод A25 (X1) нужно изолировать (можно наклеить тонкую полоску скотча) и установить перемычку JP1 для возможности отключения ROM)
- ZX Spectrum (вывод A25 (X1) нужно изолировать и установить перемычку JP1 для возможности отключения ROM)
- ZX Spectrum +3 (установить перемычку JP1)

