<br />
<p align="center">
  <a href="https://www.tk-nav.ru/">
    <img src="img/logo_TK_big_ru.png" alt="Logo" width="133" height="29">
  </a>
</p>
<h3 align="center">Видеомониторинг</h3>

  <p align="center"> 
Приложение для видеомониторинга транспорта с помощью облачного сервиса М2Медиа
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Содержание</h2></summary>
  <ol>
    <li>
      <a href="#о-проекте">О проекте</a>
    </li>
    <li>
      <a href="#перед-началом">Перед началом</a>
      <ul>
        <li><a href="#установка">Установка</a></li>
      </ul>
    </li>
    <li><a href="#использование">Использование</a></li>
    <li><a href="#контакты">Контакты</a></li>
  </ol>
</details>

## О проекте

<p align="center">
<img src="img/screen.png" alt="Внешний вид" width="760" height="335">
</p>

Приложение "Видеомониторинг" позволяет отслеживать транспорт с видеорегистраторами
компании [М2Медиа](https://www.m2media.ru/) и смотреть онлайн-видео с камер в транспорте.

## Перед началом

Для установки приложения понадобятся адрес, логин и пароль сервиса М2Медиа.

### Установка

Для установки приложения нужен доступ к AutoGRAPH Web под учетной записью администратора.

1. Скопируйте папку с App в AppTemplates.

2. Зайдите в Apps

  <p align="center"> 
    <img src="img/menu-apps.png" alt="Меню" width="800" height="600">
</p>

3. Добавьте новый App и настройки для доступа к сервису М2Медиа:

* **M2MServiceUrl** _обязательный_

> Адрес сервера M2M.

* **M2MPort**

> Порт сервера М2М.

* **M2MLogin** _обязательный_

> Логин сервиса М2М.

* **M2MPassword** _обязательный_

> Пароль сервиса М2М.

<p align="center">
   <img src="img/app-settings.png" alt="Настройки приложения" width="651" height="535">
</p>
4. Для всех автомобилей с видеорегистраторами добавьте свойство "VideoServiceID" с идентификатором устройства М2Медиа.

<p align="center">
   <img src="img/setup-device.png" alt="Настройки устройства" width="700" height="300">
</p>

5. Откройте App в отдельном окне.

<p align="center">
    <img src="img/start-app.png" alt="Запуск" width="802" height="403">
</p>
<!-- USAGE EXAMPLES -->

## Использование

Приложение будет работать с минимальными правами доступа в организацию (ReadOnly).

Поставьте флаг канала автомобиля, который требуется просмотреть, активируется окно с онлайн-трансляцией данного канала.

<!-- CONTACT -->

## Контакты

E-mail: <a href="mailto:support@tk-chel.ru">support@tk-chel.ru</a>
