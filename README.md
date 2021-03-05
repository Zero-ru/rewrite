# OSINT SAN Framework.
ДИСКЛЕЙМЕР!!!
ПЕРЕД ИСПОЛЬЗОВАНИЕМ ВЫ ОБЯЗАНЫ ОЗНАКОМИТЬСЯ С ЛИЦЕНЗИОННЫМ СОГЛАШЕНИЕМ.
ДАННЫЙ ИНСТРУМЕНТ МОЖЕТ НАРУШАТЬ ЗАКОНОДАТЕЛЬСТВО ВАШЕЙ СТРАНЫ!!! МЫ НЕ НЕСЁМ НИКАКОЙ ОТВЕТСТВЕННОСТИ ЗА ВАШИ ДЕЙСТВИЯ! ИСПОЛЬЗУЙТЕ НА СВОЙ СТРАХ И РИСК! 

## Обновление 3.5  Readme на редактировании ...

В данный момент тнаяверсия родукта. PRO версия находится в разработке. Точное время выхода не известно. Сейчас наша приоритетная задача доработать все модули.
![alt tag](https://github.com/Bafomet666/screen/blob/main/LOGOup.png)

Адаптировано под платформы: Kali Linux * Parrot OS

---

Главное меню Framework. В меню Вам будет доступно 45 функций для поиска. От простого до сложного. Сейчас пополняем только одно меню.

![alt tag](https://github.com/Bafomet666/screen/blob/main/OSINT-menu.png)

----

## Установка API.

Название API и сайты для их получения.


  API для получения информации о номере: [Открыть сайт](https://numverify.com)

  API для получения информации whois: [Открыть сайт](https://ipstack.com)

  Shodan API: [Открыть сайт](https://www.shodan.io)

  Проверка на CMS: [Открыть сайт](https://whatcms.org/API)

  Gmap для gui [Открыть сайт](https://developers.google.com/maps/documentation)

  VirusTotal бесплатная служба проверки: [Открыть сайт](https://developers.virustotal.com/v3.0/reference)
 
  Hunter.io API для получения сведений о @mail: [Открыть сайт](https://hunter.io/api)

  ZoomEye API, вход осуществляется путем авторизации в самом инструменте: [Открыть сайт](https://www.zoomeye.org)

  Torrent API: [Открыть сайт](https://iknowwhatyoudownload.com/en/api/)

  Обязательно прописывать API в settings.py
     
---
     
## Зависимости. ![Альтернативный текст](https://camo.githubusercontent.com/d4d0378438eebbdfdf98948d518a47cb34bd241b3c836aaae47255a64f2c3bbe/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d332e372532422d627269676874677265656e)
 
Как только Вы ввели все свои API, Вам нужно установить зависимости:

     sudo pip3 install -r requirements.txt
    
     В сложных модулях, Вам будет предоставлен выбор дополнительной установки модулей.
---

### Баннер авторизации.

Запускать командой: python3 osintsan.py

Пароль и логин хранится у нас в паблике в telegram.

Инструменты запускаются в двух режимах:

    Если Вам нужны функции без root [ выделены зеленым ], запускайте терминал:  python3 osintsan.py 
      
    Если Вам нужны функции root [ выделены красным ], запускайте терминал: sudo python3 osintsan.py
 
Official public https://t.me/osint_san_framework

![alt tag](https://github.com/Bafomet666/screen/blob/main/login.png)

После успешной авторизации Вам будет доступно меню с инструментами.

---

### Функция [ 01 ]
Начнем с простого инструмента - это проверка IP адреса в Shodan and Censys на утечки, здесь все просто, прописываете IP адрес и получаете результат.

![alt tag](https://github.com/Bafomet666/screen/blob/main/0130.png)

### Функция [ 02 ]
Здесь уже все куда интереснее. Используйте только с разрешения владельца ресурса.
Вам будет предложенно ввести адрес сайта (Пример: google.com) и ввести порт, можете просто нажать enter - он сам все сделает.
Функция обладает большим количеством подпунктов, используйте осторожно.

![alt tag](https://github.com/Bafomet666/screen/blob/main/3.0-002.png)

### Функция [ 03 ]
Вводите номер ( Пример: +74997059999 ) и получаете данные:

![alt tag](https://github.com/Bafomet666/screen/blob/main/3.0-003.png)

### Функция [ 04 ]
После успешного использования в папке инструмента появится детальная карта,имеющая высокое разрешение.

![alt tag](https://github.com/Bafomet666/screen/blob/main/044.png)

### Функция [ 05 ]
Если в фото есть геолокация,то софт её найдет.Вам будет необходимо указать путь. Пример пути: /home/bafomet/Desktop/deanon.png
### Функция [ 06 ]
Поиск по фото.
Вам нужно указать путь до картинки. После вас спросят:  хотите ли
Вы открыть браузер, вы жмете “ y “ и открывается браузер. Поиск осуществляется в Google and Yandex.

![alt tag](https://github.com/Bafomet666/screen/blob/main/0066.png)

### Функция [ 07 ]

Проверка сервера, либо IP адреса на HoneyPot ( ловушку для
хакеров ).

![alt tag](https://github.com/Bafomet666/screen/blob/main/07.png)

Показывает всё в процентах.

### Функция [ 08 ]

 Mac address info, с вероятностью 40% покажет еще и геолокацию.
 
![alt tag](https://github.com/Bafomet666/screen/blob/main/88854.png)

### Функция [ 09 ]
IP геолокация на картах.
Как по мне, это- самое вкусное,что я делал. IP геолокация GUI на картах.
При нажатии функции 9 Вам выпадет вот такое окно.

![alt tag](https://github.com/Bafomet666/screen/blob/main/00009.png)​

Далее Вам нужно либо ввести IP адрес, либо домен.
Также необходимо выбрать вариант поиска.
### Функция [ 10 ]
Проверяете что жертва в данный момент скачивает через torrent .
Попутно узнаёте её координаты.
 (Скрин сделан на версии продукта 2.0)
 
![alt tag](https://github.com/Bafomet666/screen/blob/main/photo_2020-12-13_02-33-17.jpg)​

Если в данный момент жертва ничего не загружает- будет
выведено окно:
 (Скрин сделан на версии продукта 2.0)
 
![alt tag](https://github.com/Bafomet666/screen/blob/main/011.png)

### Функция [ 11 ]

OSINT Instagram.

![alt tag](https://github.com/Bafomet666/screen/blob/main/1111111.png)
### Функция [ 12 ]

DNS info, огромнейший pack информации.

### Функция [ 13 ]

Находите адреса mail с сайтов. Используем API censys.

![alt tag](https://github.com/Bafomet666/screen/blob/main/014.png)

### Функция [ 14 ]

Подключение через ADB, точнее это оболочка для быстрого подключения. Обязательно нужно установить зависимости.

![alt tag](https://github.com/Bafomet666/screen/blob/main/14000.png)

### Функция [ 15 ]

Big bro 8.0 режим геолокации.

![alt tag](https://github.com/Bafomet666/screen/blob/main/big%20bro%20geo.png)

### Функция [ 16 ]

Массовый dump данных с Shodan. Работает через API. Это тот же поисковик только в разы удобнее и эффективнее.

![alt tag](https://github.com/Bafomet666/screen/blob/main/OSINT%20Menu%2016.png)

### Функция [ 17 ]

Графический мониторинг вашей сети.

![alt tag](https://github.com/Bafomet666/screen/blob/main/99.png)

https://etherape.sourceforge.io/
https://ru.wikipedia.org/wiki/EtherApe

### Функция [ 18 ]

Сейчас эта функция нечего не загружает. Пока я не буду выкладывать dls либо другие обновления.

![alt tag](https://github.com/Bafomet666/screen/blob/main/016.png)

### Функция [ 19 ]

Фишинг модификация Big bro. Находится в beta версии.

![alt tag](https://github.com/Bafomet666/screen/blob/main/OSINT%20menu%2019.png)

### Функция [ 20 ]

Функция открывает 10 сайтов для поиска человека по лицу.

### Функция [ 21 ]

OSINT Wikipedia.

![alt tag](https://github.com/Bafomet666/screen/blob/main/OSINT%20menu%2021.png)

### Функция [ 22 ]

Брутфорс instagram.

Указываете логин и вперед. Если вдруг надо пароли сменить, module лежит документ password, Пишите свои пароли туда.

### Функция [ 23 ]

Функция открывает 10 сайтов быстрой и анонимной почты

### Функция [ 24 ]

База данных паролей Bafomet +
Сейчас в базе собрано 1.9 миллиарда паролей. Все разбито по частями, чтобы удобно было загружать.  В наличии пароли под различные задачи.

### Функция [ 25 ]

Поднимаем сайт Beff-XSS в сеть

Сначал вам нужно будет нажать 1. Это вариант с онлайном.
Потом вам выпадет инструкция по установке ngrok в положение ( start --all на 4 ссылки ) После вы запускаете ngrok в полном режиме и даете старт программе.

![alt tag](https://github.com/Bafomet666/screen/blob/main/250.png)

После вас попросят вписать ссылки, вписываем до http, https в таком формате:

     f19d35259оaff5.ngrok.io  всегда сначала по 80 порту
     
     f19d3c96533ff5.ngrok.io  потом по 3000 порту
     
Установка стилей для сайта. Вам нужно перейти в папку "OSINT SAN" и скопировать все там из папки "Стили Beef" в директорию /var/www/html

Если вдруг у вас нет доступа к копированию стилей в beef html,то выполните:
         
         sudo chmod 777 /var/www/html

### Функция [ 26 ]

Наше большое сообщество OSINT СНГ. Здесь я собрал адреса всех ресурсов где есть полезная информация. Админов ресурсов знаю лично. Отличные парни.

### Функция [ 27 ]

Работа с доменом 2.0

![alt tag](https://github.com/Bafomet666/screen/blob/main/270.png)

### Функция [ 28 ]

Open Maltego - просто открывает мальтего.

![alt tag](https://github.com/Bafomet666/screen/blob/main/maltego.jpg)

### Функция [ 29 ]

Массовый дамп данных с ZoomEye. Аналог shodan.
Вход через логин и пароль от самого сайта. Анонимный поиск с выбором с какой страницы дампить данные. Все данные сохраняются в папке с инструментом.

![alt tag](https://github.com/Bafomet666/screen/blob/main/290.png)

### Функция [ 30 ]

Деанонимизация хакера его же ссылкой. Это обычный парсер. Представим ситуацию, где мамкин хакер вам скинул ссылку ngrok, чтобы вы перешли и он узнал вашу геолокацию. Но если вы возьмете эту ссылку и впишите в инструмент отслеживания и подождете, обычно он на себе ёё проверяет и деанонит себя.
Функция 30 направленна на то, чтобы автоматически воровать результат с его машины. Обратный деанон, Также можно отключить его ngrok, либо сломать, проверить с какого он железа работает. 

![alt tag](https://github.com/Bafomet666/screen/blob/main/300.png)

### Функция [ 31 ]

IP logger для профи, Firefox.
Вы можете создавать как ссылки логеры так и файлы. Практически любые, которые будут логировать данные о устройстве и IP адресе.

### Функция [ 32 ]

Загрузить OSINT Pack. Актуальная информация как в pdf файлах так и в книгах.

### Функция [ 33 ]
dns whois сайтов.

![alt tag](https://github.com/Bafomet666/screen/blob/main/OSINT%20menu%2033.png)

### Функция [ 34 ]

Данные по утечкам, взяты из открытых источников. Нходятся на редактировании.

![alt tag](https://github.com/Bafomet666/screen/blob/main/340.png)

### Функция [ 35 ]

Mod film миссия невыполнима.

### Функция [ 36 ]

В разработке. Будет в PRO версии.

### Функция [ 37 ]

В разработке. Будет в PRO версии.

### Функция [ 38 ]

В разработке. Будет в PRO версии.

### Функция [ 39 ]

В разработке. Будет в PRO версии.

### Функция [ 40 ]

В разработке. Будет в PRO версии.

### Функция [ 41 ]

В разработке. Будет в PRO версии.

### Функция [ 42 ]

В разработке. Будет в PRO версии.

### Функция [ 43 ]

В разработке. Будет в PRO версии.

### Функция [ 44 ]

Техническая поддержка 24/7

![alt tag](https://github.com/Bafomet666/screen/blob/main/Screenshot%20at%202021-02-02%2010-59-29.png)​

### Функция [ 45 ] Лицензионное соглашение.
![alt tag](https://github.com/Bafomet666/screen/blob/main/OSINT%20menu%2045.png)




