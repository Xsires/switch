---
permalink: /rcmloader.html
title: Инструкция по прошивке донгла RCMLoader
author_profile: true
---
{% include toc title="Разделы" %}

Инструкция предназначена владельцам донгла RCMLoader и создавалась в поддержку купивших устройство у меня. 

![](/images/dongle/rcmloader.jpg)
{: .text-center}
{: .notice--info}

Купить донгл с прошивкой, наиболее подходящей для гайда можно [здесь](https://vk.com/market-125012133?w=product-125012133_1694790%2Fquery){:target="_blank"}. Купленный у меня донгл по-умолчанию прошит таким образом, что будет загружать hekate 4, будучи вставленным в приставку. 

## Перепрошивка донгла

1. Подключите донгл к пк с помощью комплектного microUSB-USB кабеля
1. Донгл смонтируется как новый диск
1. Положите пейлоад, переименованный в `payload.bin` в папку, соответствующую его функции, согласно таблице

	![](/images/dongle/rcmloader_table.png)
	{: .text-center}
	{: .notice--info}

1. Отсоедините донгл от ПК
1. Длинным нажатием кнопки (+) переключите донгл в нужный режим, согласно цвету диода и соответствию его таблице

## Использование донгла

1. Выключите консоль
1. Вставьте карту памяти в ПК
1. Обновите [SDFiles от VK:3ds_cfw](https://github.com/rashevskyv/switch/releases/latest){:target="_blank"} по инструкции из репозитория, если не делали этого ранее
1. Верните карту памяти в приставку
1. Вставьте замыкатель вместо правого джойкона

![](/images/dongle/rcmloader_jig.png)
{: .text-center}
{: .notice--info}

1. Переключите донгл на голубой свет диода, с помощью длинного нажатия на кнопку (+)
	* Достаточно выставить единожды
1. Вставьте донгл в USBtype-C порт свитча
1. Удерживая (VOL+) включите приставку
1. Приставка загрузится в CFW

___

## [Запуск прошивки](launch-cfw)
{: .notice--success}

## [Запуск любого пейлоада через донгл](fusee-gelee#%D0%B7%D0%B0%D0%BF%D1%83%D1%81%D0%BA-%D1%87%D0%B5%D1%80%D0%B5%D0%B7-%D0%B4%D0%BE%D0%BD%D0%B3%D0%BB)
{: .notice--success}