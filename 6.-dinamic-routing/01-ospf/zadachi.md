# Задачи

[![](http://img-fotki.yandex.ru/get/6622/83739833.1f/0_9e219_a466f149_S.jpg)**Задача №2**](https://linkmeup.ru/blog/20.html)  
После настройки OSPF на маршрутизаторах в сибирском кольце, все сети, которые находятся за маршрутизатором в центральном офисе в Москве \(msk-arbat-gw1\), для Хабаровска доступны по двум маршрутам \(через Красноярск и через Владивосток\). Но, так как канал через Красноярск лучше, то надо изменить настройки по умолчанию таким образом, чтобы Хабаровск использовал канал через Красноярск, когда он доступен. И переключался на Владивосток только если что-то случилось с каналом на Красноярск.  
[Ответ](https://linkmeup.ru/blog/20.html)

Как любой хороший протокол, OSPF поддерживает аутентификацию — два соседа перед установлением соотношений соседства могут проверять подлинность полученных OSPF-сообщений. Оставляем на самостоятельное изучение — довольно просто.

[![](http://img-fotki.yandex.ru/get/6622/83739833.1f/0_9e219_a466f149_S.jpg)**Задача №3**](https://linkmeup.ru/blog/24.html)  
С провайдером «Филькин сертификат» случилась неприятная история. Из-за их ошибки в настройках VPN на маршрутизатор во Владивостоке начали приходить какие-то непонятные маршруты, вероятно, от другого клиента или внутренние самого сети провайдера. Некоторые сети пересекались с локальными сетями и была потеряна связь с некоторыми участками сети. После этого случая было решено защититься на будущее от подобных ситуаций.  
Ситуация, вообще говоря, надуманная и маловероятная, но в качестве задачки подойдёт.  
На участке между Москвой и Владивостоком необходимо настроить маршрутизаторы таким образом, чтобы они, при установке отношений соседства, проверяли ещё и установленный пароль. Пароль должен быть: MskVladPass и передаваться он должен в виде хеша md5 \(номер ключа 1\).  
[Ответ](https://linkmeup.ru/blog/24.html)
