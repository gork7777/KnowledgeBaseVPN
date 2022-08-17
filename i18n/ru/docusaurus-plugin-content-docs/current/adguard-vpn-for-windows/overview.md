---
title: Обзор функций
sidebar position: 1
---

## Что такое AdGuard VPN для Windows

VPN, или виртуальная частная сеть, — это инструмент, который обеспечивает безопасность вашего интернет-соединения и помогает вам сохранять анонимность в Сети. Как это работает? Каждый раз, когда вы открываете вебсайт без использования VPN, ваш интернет-провайдер видит это. Он знает, кто вы и что ищете, может собирать эти данные и продавать их. В свою очередь, сайт, на который вы пришли, также может отслеживать вашу онлайн-активность. Когда вы активируете VPN-приложение, оно перенаправляет ваш трафик через зашифрованный туннель на удалённый VPN-сервер, обеспечивая вашу конфиденциальность: интернет-провайдер не знает, куда вы отправили запрос, а сайт не в курсе, откуда вы пришли.

**Что делает AdGuard VPN для Windows**

* Защищает от перехвата сетевого трафика (спуфинга). VPN создаёт зашифрованный туннель между вашим устройством и удалённым сервером. Через этот туннель проходит весь ваш интернет-трафик, так что на этом пути ваши данные защищены. А благодаря [уникальному протоколу AdGuard](/general/adguard-vpn-protocol.mdx), вы получаете гарантированно быстрое и безопасное соединение.

* Маскирует ваш IP-адрес.  Ваш настоящий IP-адрес — ключ к вашим персональным данным для киберпреступников. Ваше имя, адрес элетронной почты, номер телефона, данные банковской карты могут попасть в руки мошенников, если вы не спрячете свой IP. С AdGuard VPN, как мы говорили ранее, весь ваш трафик через зашифрованный туннель приходит на VPN-сервер. Таким образом, со стороны кажется, что ваше устройство имеет IP-адрес указанного VPN-сервера.

* Скрывает ваше местоположение. Как только вы выбираете любой из серверов AdGuard VPN, вы мгновенно «телепортируетесь» туда, где он расположен. Для чего это нужно? Например, чтобы забронировать отель по ценам «для своих» или спрятаться от геотаргетированной рекламы.

У AdGuard VPN для Windows есть большое количество преимуществ, так что этой теме мы посвятили [отдельную статью](/general/why-adguard-vpn.md). А здесь мы хотим больше сосредоточиться на самом приложении и на том, как оно работает.

## Как начать пользоваться AdGuard VPN для Windows

Чтобы начать пользоваться AdGuard VPN для Windows, необходимо скачать приложение с [нашего сайта](https://adguard-vpn.com/en/welcome.html). Установка займёт не больше минуты — и вы увидите диалоговое окно, в котором потребуется поставить как минимум одну галочку, чтобы принять условия Пользовательского соглашения и Политики конфиденциальности. А вот, давать ли AdGuard право собирать анонимные данные об использовании приложения на вашем устройстве или нет, решать вам. В завершении процесса установки программа попросит вас войти в систему, либо через [учётную запись AdGuard](https://auth.adguard.com/login.html), либо через социальные сети (Apple, Google, Facebook). Вот и всё, теперь вы можете начать пользоваться AdGuard VPN для Windows.


## Главный экран

![Главный экран AdGuard VPN для Windows](https://cdn.adguard.com/content/kb/VPN/windows/main_en.png)

Наиболее заметный элемент на **Главном экране** — это кнопка включения/выключения AdGuard VPN. Под ней указан [режим](#exclusions), в котором работает приложение, а ещё ниже — выбранный сервер. В правой части экрана вы найдёте все доступные локации, причём самые быстрые, т.е. с самым маленьким пингом, будут указаны вверху списка.

В верхней части экрана расположена навигационная панель с четырьмя вкладками: **Главная**, **Исключения**, **Поддержка**, **Настройки**. С первой вкладкой закончили — двигаемся дальше.


## Исключения

AdGuard VPN для Windows может работать в двух режимах — **Обычном** или **Выборочном**. Что это значит? Если вы хотите, чтобы приложение работало на всех сайтах, кроме нескольких, активируйте **Обычный режим** и перечислите ресурсы, которые надо исключить из туннеля. У **Выборочного режима** обратный принцип действия: он активирует работу AdGuard VPN только на сайтах, указанных в списке исключений. Обратите внимание, что списки исключений в этих двух режимах не зависят друг от друга.

![Исключения](https://cdn.adguard.com/content/kb/VPN/windows/exclusions_en.png)

Для создания списков исключений есть две опции: **Вручную** и **Из списка**. Нажмите на строку **Добавить сайт** и выберите удобный вам формат добавления сайтов в исключения.

![Добавить исключения](https://cdn.adguard.com/content/kb/VPN/windows/exclusions_add_en.png)

![Добавить исключения из списка](https://cdn.adguard.com/content/kb/VPN/windows/exclusions_from_list_en.png)

> При ручном добавлении доменов нужно учитывать некоторые нюансы. Например, если вы вручную исключите домен `google.com`, все поддомены `*.google.com` также будут внесены в список исключений. Однако доменные имена с другими доменами верхнего уровня, такие как `google.es` или `google.it`, не будут исключены. Или вы можете добавить `youtube.com` в исключения, но домен того же сервиса `youtu.be` не попадёт в список.

Учитывая всё вышесказанное, мы рекомендуем пользоваться опцией **Из списка**, чтобы избежать ненужных хлопот. Мы уже сгруппировали самые популярные сервисы в восемь тематических категорий: Социальные сети, Мессенджеры, Видео, Музыка, Игры, Магазины, Поисковые системы и Работа. В каждую группу мы поместили все доменные имена и поддомены, относящиеся к каждому сервису. Таким образом, вы будете уверены, что не забыли какой-либо сервис или домен, который вы хотели бы сохранить функционирующим при включенном VPN, или наоборот.

### Импорт/экспорт списков исключений

Во вкладке **Исключения** в правой стороне экрана расположен раздел **Действия**. Он может пригодиться, если у вас возникнет потребность экспортировать или импортировать готовые списки исключений.

Чтобы выгрузить список исключений из AdGuard для Windows на ваш компьютер, нажмите **Экспортировать исключения**, выберите папку, где будет храниться список, и нажмите **Сохранить**. Будет загружен архив `exclusions.zip` с двумя файлами `.txt`, по одному для каждого из списков — **Основного** и **Выборочного**. Вы можете их редактировать, добавляя новые исключения или удаляя старые.

Чтобы передать списки исключений на другое устройство, отправьте файл `.zip` по назначению. Откройте AdGuard VPN на устройстве, куда вы хотите импортировать архив с готовыми списками исключений, нажмите *Исключения*, затем *Импортировать исключения* и выберите ранее отправленный архив.

## Настройки

![Настройки](https://cdn.adguard.com/content/kb/VPN/windows/settings_en.png)

В последней верхней вкладке AdGuard Vpn для Windows собраны разделы, которые помогут вам настроить приложение под себя. Особое внимание стоит уделить двум из них: **Основные** и **Раздельное туннелирование**.


### Основные

Раздел **Основных** настроек содержит много полезных функций. Здесь вы можете установить язык приложения, а также включить **Kill Switch**, благодаря которому при обрыве VPN-соединения будет заблокирован доступ к интернету. Это нужно, чтобы не дать злоумышленникам добраться до ваших данных, если вы окажетесь без защиты VPN, будучи подключёнными к общественному Wi-Fi или к мобильной сети.

Также, одним нажатием на переключатель вы можете активировать следующие функции: **Автообновление**, **Запускать AdGuard VPN при загрузке Windows**, **Автоподключение при запуске приложения**, а ещё — разрешить AdGuard собирать анонимизированные данные об использовании приложения, чтобы мы могли сделать его лучше. Здесь же можно поменять **Светлую тему**, установленную по умолчанию, на любимую многими **Тёмную**.

Внизу страницы расположены два важных раздела — **DNS-серверы** и **Расширенные настройки**.

![Настройки DNS и Расширенные настройки](https://cdn.adguard.com/content/kb/VPN/windows/settings_dns_and_advanced_en.png)

#### DNS-серверы

Во вкладке **DNS-серверы** вы можете добавить собственный пользовательский DNS-сервер. Зачем это делать? Например, чтобы не полагаться на DNS-сервер, который установлен по умолчанию, и часто контролируется вашим интернет-провайдером.

Вы можете настроить DNS-сервер от любого провайдера. Мы рекомендуем добавить [AdGuard DNS](https://kb.adguard.com/en/general/dns-providers#adguard-dns), сервер, который помимо стандартных функций умеет осуществлять защиту от рекламы, трекинга и фишинга.

#### Расширенные настройки

Вы вполне можете пользоваться AdGuard VPN для Windows, вообще не открывая Расширенные настройки. Однако они могут быть полезны, если вы найдёте время в них разобраться.

**Режим работы**

Несмотря на то, что режимов работы два — VPN и SOCKS5 — мы советуем использовать лишь тот, что выбран по умолчанию (VPN). При включённом **VPN-режиме** весь трафик устройства направляется через AdGuard VPN, в то время как в **режиме SOCKS5** AdGuard VPN использует локальный прокси-сервер, которым могут воспользоваться другие приложения для перенаправления своего трафика.

**Уровень логирования**

К выбору доступны два уровня логирования: **Записывать по умолчанию** и **Записывать всё**. Первый вариант включён по умолчанию. Вариант **Записывать всё** стоит активировать только если наша служба поддержки попросила вас об этом. Продолжительная работа приложения в этом режиме может привести к повышенному потреблению ресурса батареи.

Все логи хранятся локально на вашем устройстве, и вы можете отправить их команде поддержки, если возникнет необходимость.

**Использовать QUIC**

Это экспериментальная функция, включение которой позволит AdGuard использовать передовой протокол шифрования QUIC. У него много преимуществ, но самое заметное в том, что он может улучшать качество соединения в неидеальных условиях – например, при использовании мобильного интернета или при подключении к общественным сетям Wi-Fi.


### Раздельное туннелирование

![Раздельное туннелирование](https://cdn.adguard.com/content/kb/VPN/windows/split_tunneling_en.png)

AdGuard VPN шифрует трафик не только браузеров, но и приложений, установленных на вашем компьютере. Если хотите исключить из работы AdGuard некоторые приложения, перечислите их в списке **Раздельного туннелирования**.

## Другие настройки

### О программе

Во вкладке **О программе** вы найдёте информацию о текущей версии AdGuard VPN для Windows, кнопку проверки наличия обновлений, а также несколько полезных ссылок: на сайт, форум, лицензионное соглашение и политику конфиденциальности.

### О лицензии

Здесь размещена информация о статусе вашей лицензии, а также ссылка на ваш личный кабинет AdGuard, где вы можете купить новую подписку, улучшить или продлить уже существующую.

## Поддержка

В этой вкладке мы собрали множество полезных ссылок: страницу с ответами на часто задаваемые вопросы, форму для отправки отзыва о приложении, ресурсы, где можно обсудить AdGuard VPN, и **Базу знаний**.