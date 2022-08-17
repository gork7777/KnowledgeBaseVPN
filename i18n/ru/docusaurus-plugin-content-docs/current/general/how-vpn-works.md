---
title: Как работает VPN
sidebar_position: 1
---

Чтобы понять, как работает AdGuard VPN, для начала следует разобраться с основными принципами работы VPN-сервиса.

## Функции VPN

VPN — это виртуальная частная сеть (Virtual Private Network), которая помогает скрыть ваше местоположение и защитить ваши данные в интернете. VPN соединяет компьютер или мобильное устройство с VPN-сервером и использует его IP-адрес, чтобы стороннему наблюдателю казалось, что вы находитесь в другом месте. Это позволяет вам безопасно получать доступ к различным интернет-ресурсам и защищать свои личные данные.

Таким образом, VPN выполняет две важные функции:

1. **Обеспечивает анонимность**

Пользуясь интернетом человек оставляет свой цифровой след, который затем может быть проанализирован и использован третьими лицами. Например, один из интернет-магазинов, который вы посещали, может сохранить историю вашего поиска и затем предложить вам свои товары на её основе с помощью таргетированной рекламы. Или же секретные службы, узнав ваше местоположение по IP-адресу вашего устройства и определив вашу личность, могут тайно следить за вашей активностью в интернете. Кроме того, сами веб-браузеры и интернет-провайдеры могут использовать историю просмотров в своих целях, а также продавать её рекламодателям и предоставлять государственным учреждениям. VPN позволяет скрыть ваш IP-адрес и заменить его IP-адресом VPN-сервера, к которому вы подключены. Таким образом, вы сможете сохранить свою конфиденциальность и анонимно искать информацию в интернете.

2. **Защита данных**

Если вы подключаетесь к ненадежной или общедоступной сети, данные на вашем устройстве могут стать уязвимыми для киберпреступников. Данные банковских карт, имена пользователей и пароли, паспортные данные — все эти данные могут быть перехвачены мошенниками. VPN-туннель шифрует информацию, которую вы отправляете и получаете из интернета, чтобы она не попала в чужие руки.

## Структура VPN

Когда вы подключаетесь к Cети, вашему компьютеру или мобильному устройству присваивается уникальный идентификационный номер или IP-адрес. Обычно он состоит из чисел от 0 до 255, разделённых точками или двоеточиями. Зная эту последовательность, можно определить местоположение устройства. Обычно ваш IP-адрес задаёт интернет-провайдер, и он остаётся видимым на всём пути к нужному ресурсу. По этой причине веб-сервер сайта, который вы посещаете, может зарегистрировать ваш IP-адрес и запомнить все ваши запросы. Затем эта запись может быть использована для сбора данных и анализа трафика.

VPN создает туннель между вашим устройством и VPN-сервером. Ваши данные проходят через него, шифруются и затем попадают в открытый интернет в защищённом виде. Поэтому веб-серверу будет казаться, что у вашего устройства IP-адрес конечной точки туннеля, то есть VPN-сервера, а не ваш реальный IP. Таким образом, сайт, на который вы попадёте после прохождения через VPN-туннель, будет считать геолокацию выбранного вами VPN-сервера вашим реальным местоположением. А зашифрованные данные не попадут в руки рекламодателей, хакеров и служб безопасности.

![Структура VPN](https://cdn.adguard.com/public/Adguard/Website/Images/seo/ru/how_vpn_3.jpg)

## Типы VPN-протоколов

Протоколы безопасности VPN – это главные инструменты, которые шифруют данные в VPN-туннеле и обеспечивают конфиденциальность пользователя в интернете. В настоящее время подавляющее большинство современных VPN-сервисов используют один из следующих трёх VPN-протоколов:

1. [*IPSec*](https://ru.wikipedia.org/wiki/IPsec). Одно из его основных преимуществ в том, что он доступен на большинстве устройств и операционных систем и обеспечивает высокий уровень безопасности. Однако использование двойной [инкапсуляции](https://en.wikipedia.org/wiki/Encapsulation_(networking)) в этом протоколе может привести к снижению скорости соединения.

2. [*OpenVPN*](https://ru.wikipedia.org/wiki/OpenVPN). У этого современного протокола открытый исходный код, поэтому сторонние производители могут совершенствовать и обновлять технологию.

3. [*WireGuard*](https://en.wikipedia.org/wiki/WireGuard). Его основными преимуществами являются простота использования, высокая эффективность и низкая уязвимость.

Помимо этих VPN-протоколов существуют и другие (например, TLS, SSTP, IKEv2), но они непопулярны или не соответствуют современным стандартам шифрования данных.

![Как работает VPN-протокол](https://cdn.adguard.com/public/Adguard/Blog/vpn/protocol/4.svg)

У AdGuard VPN также есть свой [*протокол*](adguard-vpn-protocol.mdx). Одно из его преимуществ заключается в том, что трафик, передаваемый по протоколу AdGuard VPN, трудно отличить от обычного. VPN-туннель выглядит как обычный HTTPS-трафик, поэтому обнаружить и заблокировать его крайне сложно. Кроме того, он основан на механизмах современного протокола HTTP/2, что обеспечивает высокую скорость соединения.

![Как работает скрытый VPN](https://cdn.adguard.com/public/Adguard/Blog/vpn/protocol/5.svg)

## Недостатки VPN

Несмотря на очевидные преимущества, VPN не совершенен и имеет некоторые недостатки:

**Снижение скорости**

Поскольку ваш трафик не идет напрямую на веб-сервер, а сначала проходит через VPN-сервер, скорость VPN-соединения снижается. На скорость при использовании VPN влияют и другие факторы: загруженность VPN-сервера, его пропускная способность, совместимость VPN-протокола с вашей операционной системой. Все эти факторы, а также скорость самой сети, могут снизить качество вашего VPN-соединения.

**Блокировка доступа**

У некоторых онлайн-сервисов есть система для обнаружения использования VPN, и если они думают, что кто-то подключается через VPN, то могут заблокировать доступ. Однако не многие VPN могут маскировать свой трафик под обычный. Поэтому многие попытки зайти на тот или иной сайт без отключения VPN заканчиваются ничем.

**Обрыв VPN-соединений**

Слабый сигнал, перегрузка сети, несовместимость VPN с брандмауэром, антивирусом и другими программами, устаревший VPN-протокол — всё это может стать причиной внезапного обрыва VPN-соединения, особенно у ненадежных VPN-провайдеров.

## AdGuard VPN

Наш VPN-сервис обладает рядом важных [преимуществ](why-adguard-vpn.md):

* [*Собственный VPN-протокол*](adguard-vpn-protocol.mdx), который стабильно работает даже при медленном интернет-соединении и маскируется под обычный трафик, что затрудняет его отслеживание и блокировку

* [*Политика нулевого логирования*](https://adguard-vpn.com/en/privacy.html), которая означает, что AdGuard VPN не собирает ваши личные данные и не передает их третьим лицам

* *Более 50 VPN-серверов в десятках стран;*

* *Простота использования и широкие возможности настройки.*

В настоящее время AdGuard VPN доступен как:

* [Браузерное расширение](../adguard-vpn-browser-extension/overview.md) для Chrome, Firefox и Edge;

* Мобильное приложение для [Android](../adguard-vpn-for-android/overview.md) и [iOS](../adguard-vpn-for-ios/overview.md);

* Десктопное приложение для [Windows](../adguard-vpn-for-windows/overview.md) и [Mac](../adguard-vpn-for-mac/overview.md).

Вы можете узнать больше о возможностях AdGuard VPN (включая безлимитную версию) [здесь](https://adguard-vpn.com/en/welcome.html).