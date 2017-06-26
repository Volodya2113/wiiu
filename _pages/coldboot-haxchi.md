---
title: "Coldboot Haxchi" #
lang: ru
permalink: /coldboot-haxchi.html
sidebar:
  nav: "mocha-cfw-cbhc"
---

CBHC (Coldboot Haxchi) изменяет системный тайл, запускающийся по-умолчанию при старте SysNAND, на игру из DS virtual console, которая настроена на запуск пропатченного SysNAND.
{: .notice}

Выполнение инструкций на этой странице не обязательно. Обычный Haxchi прекрасно работает; станет просто слегка удобней. Если вы хотите пропустить эту часть, переходите к [Homebrew Launcher (Channel)](homebrew-launcher-channel)).
{: .notice--info}

**Для продолжения необходимо иметь функционирующий Haxchi. Без него получите гарантированный БРИК!**
{: .notice--danger}

**Ваша игра от DS virtual console, используемая для Haxchi, ДОЛЖНА находится во внутренней памяти Wii U. Если она находится на USB, гарантированно получите БРИК!**
{: .notice--danger}

**Ваша игра от DS virtual console, используемая для Haxchi, ДОЛЖНА быть ЛЕГАЛЬНОЙ копией, в иных случаях, гарантированно получите БРИК!**
{: .notice--danger}

**Все USB-устройства должны быть отключены перед установкой, иначе есть шанс получить БРИК!**
{: .notice--danger}

#### <a name="instructions" />Инструкция:

1. Отключите все USB-устройства от Вашей Wii U
1. Войдите в Homebrew Launcher, удерживая (A) во время запуска хакнутой игры для DS virtual console
1. Запустите инсталлятор CBHC
1. Выберите игру от DS virtual console, в которую вы собираетесь установить CBHC, а затем нажмите (A) для подтверждения
  + **Игра уже ДОЛЖНА содержать установленный и работающий Haxchi**
1. Ознакомьтесь с появившимся предупреждением и нажмите (A) для установки
1. После окончания процесса установки, вы вернетесь в системное меню
1. Вы можете подсоединить обратно все USB-устройства, которые были отключены раннее.
1. Перезагрузите Wii U
1. Если эксплойт сработал корректно, вы увидите меню с различными опциями загрузки
1. Наведите курсор на **"Autoboot: Disabled"** и нажимайте (A) до тех пор, пока надпись не поменяется на **"Autoboot: System Menu"**
1. Нажмите (A) на пункте "Boot System Menu"
1. Перезагрузите консоль, чтобы убедиться, что эксплойт срабатывает корректно и приставка автоматически загружается в соответствии с настройками
1. Переместите игру для DS virtual console с установленным CBHC на последнюю страницу системного меню
  + Внимательно прочитайте предостережения на этой странице. Это поможет вам уберечь консоль от брика!

___

Ваша приставка теперь автоматически будет запускать пропатченный SysNAND при каждой загрузке.
{: .notice}

{% capture notice-1 %}
**Нажатие кнопки (HOME) при загрузке CBHC, вызовет меню настроек программы. Ниже краткое описание каждого из пунктов:**

    + Boot System Menu -> Загрузиться в SysNAND
    + Boot Homebrew Launcher -> Загрузиться в Homebrew Launcher в SysNAND
    + Boot Mocha CFW -> Загрузиться в Mocha CFW в RedNAND
    + Boot fw.img on SD Card -> Загрузить старую CFW из файла fw.img из корня SD-карты
    + Boot vWii System Menu -> Загрузиться в vWii в SysNAND
    + Boot vWii Homebrew Channel -> Загрузиться в vWii Homebrew Channel в SysNAND

{% endcapture %}

<div class="notice--info">{{ notice-1 | markdownify }}</div>

Вы можете подсоединять USB-устройства после завершения установки.
{: .notice--info}

**Никогда не удаляйте игру от DS virtual console с установленным CBHC, иначе получите БРИК.**    
{: .notice--danger}

**Никогда не переустанавливайте игру от DS virtual console с установленным CBHC через eShop, иначе получите БРИК.**
{: .notice--danger}

**Никогда не перемещайте игру от DS virtual console с установленным CBHC на USB-носитель, иначе получите БРИК.**
{: .notice--danger}

**Никогда не удаляйте пользовательский NNID аккаунт через который была куплена игра для DS virtual console, используемая для CBHC, или вы получите БРИК!**
{: .notice--danger}

**Никогда не форматируйте приставку, если у вас установлен CBHC, иначе получите БРИК.**
{: .notice--danger}

Следующий шаг: [Homebrew Launcher (Channel)](homebrew-launcher-channel).
{: .notice--primary}