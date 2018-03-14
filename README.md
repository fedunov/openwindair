# openwindair
OpenWindAir Smart CO2 sensor

Скетч Arduino IDE для датчика углекислого газа OpenWindAir.
В проекте использованы сторонние библиотеки, все права на которые принадлежат их Авторам.

Основные возможности датчика: 
* Датчик CO2: MH-Z19.
* Датчик температуры \ влажности: AM2302.
* Реле для управления нагрузкой.
* Светодиодная и звуковая индикация.
* Вывод результатов измерения: USB (CP2102), Blynk, MQTT.
* Обновление по OTA и USB.
* Настройка всех параметров через WiFi.
* Питание от miniUSB 5V.

Особенности проекта:
* Автоматический инкремент версии ПО при сборке в Arduino IDE.
* Возможно активировать ОТА обновление на удаленном устройстве.
* Реализована отправка показаний на сайт narodmon.ru по протоколу MQTT.
* Возможен офлайн режим, когда уровень СО2 отображается с помощью трех светодиодов (зеленый, желтый, красный).
* Настройка параметров WiFi и MQTT осуществляется через Сaptive portal.
* Изменение пользовательских настроек осуществляеся через приложение Blynk.

Демо:
* Скачайте прилоение Blynk
	https://itunes.apple.com/us/app/blynk-control-arduino-raspberry/id808760481?ls=1&mt=8
	https://play.google.com/store/apps/details?id=cc.blynk
* Просканируйте в приложение QR код http://openwind.ru/OpenWindAir-demo-QR.png
* Перед вами полноценное демо.

Подробнее про датчик OpenWindAir на сайте http://openwind.ru вопрсы и пожелания отправляйте на mailto:hello@openwind.ru


