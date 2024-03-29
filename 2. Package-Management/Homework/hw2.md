# Домашнее задание к занятию "Управление пакетами"

Любые вопросы по решению задач задавайте в чате учебной группы.

---

### Кейс 1.

Опишите плюсы работы с пакетным менеджером и репозиторием.

* Как вы считаете, в чем основные достоинства такой организации ПО?
* Есть ли минусы?

*Напишите ответ в свободной форме.*

---

### Кейс 2.

При подключении стороннего репозитория надо выполнить ряд определенных действий.

* Каких?
* В чем опасность такого способа распространения ПО?
* Как это решается?

*Напишите ответ в свободной форме.*

---

### Кейс 3.

#### Перейдем к практике.

1. Запустите свою виртуальную машину.
2. Найдите в репозиториях и установите одной командой пакет `htop`.

Какие зависимости требует `htop`?

*Ответ приведите в виде текста команды, которой вы это выполнили, а также приложите скриншот места расположения исполняемых файлов установленного ПО.*

---

### Кейс 4.

1. Подключите репозиторий PHP и установите PHP 8.0.

*Приложите скриншот содержимого файла, в котором записан адрес репозитория.*

2. При помощи команды `php -v` убедитесь, что бы поставлена корректная версия PHP.

*Приложите к ответу скриншот версии.*

---

### Кейс 5.

Ваш коллега-программист просит вас установить модуль `google-api-python-client` на сервер, который необходим для программы, работающей с Google API.

Установите данный пакет при помощи менеджера пакетов `pip`.

**Примечение №1:** для установки может быть необходим пакет `python-distutils`, проверьте его наличие в системе.

**Примечение №2:** не забудьте выдать права на исполение скачанному файлу. Возможно, будет ошибка при установки при помощи Python версии 2, в таком случае воспользйтесь командой `python3`.

*Приложите скриншоты  с установленным пакетом `python-distutils`, с версией `Pip` и установленными модулями (должны быть видимы)*

---

### Кейс 6.

1. Перечислите менеджеры пакетов, кроме тех, о которых говорилось на лекции.
В каких дистрибутивах они работают?

2. Есть ли альтернативные менеджеры для тех, которые разбирались на лекции?

*Напишите ответ в свободной форме.*

---

### Кейс 7.

1. Скачайте исходники любого приложения и соберите пакет для того дистрибутива, на котором вы работаете.
2. Установите его при помощи менеджера пакетов

*Ответ приведите в виде скриншота.*