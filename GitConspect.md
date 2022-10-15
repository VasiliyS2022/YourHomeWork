# Инструкция по работе с Git
## 1 часть
### 1 семинар
* *git init* - команда, инициализирующая репозиторий в заданной директории.

* *git version* - команда, отображающая текущую установленную версию Git.

* *git status* - команда, отображающая состояние репозитория.

# Четыре шага работы с Git

1. Создаем / делаем изменение в коде.

2. Сохраняем изменения (Ctrl+S).

3. Добавляем изменение в репозиторий (git add).

4. Записываем изменение в репозиторий (git commit).

*Дополнительную информацию можно искать на habr.com*

*Данный сайт можно открыть* [по ссылке](habr.com/ru/all/)

> # Цитата

> Мудрые люди учатся на ошибках других,
> а глупые на своих.

> *-  автор неизвестен*

![Изображение](https://demotivation.ru/wp-content/uploads/2020/04/1535659057_stoit-li-sovmeschat-uchebu-i-rabotu-768x576.jpg)

## 2 часть
### 2 семинар
### Создание веток

* *git branch* - команда, отображающая все существующие ветки в репозитории;

* *git branch <branch_name>* - команда, создающая новую ветку с именем branch_name;

### Слияние веток

* *git merge <branch_name>* - команда, осуществляющая слияние текущей ветки с указанной (branch_name);

__*NB*__ Перед слиянием веток необходимо убедиться в том, что базовая и принимаемая ветка указаны верно!

### Конфликты




### Режимы слияния веток


* *Fast-Forward* - в главной ветке не вносятся изменения, а вносятся только в побочной;


* *ort* - изменения вносятся в обе ветки, но не затрагивют одну и ту же область (в этом случае возникнет конфликт)

*конфликт можно разрешить*




### Разрешение конфликта




*при возникновении конфликта, его можно разрешить, выбрав нужный вариант*

* *current* - текущий

* *incoming* - входящий

* *both* - оба

После выбора нужно сохранить изменения (Ctrl+S), добавить в репозиторий (git add) и записать (git commit). Только в этом случае конфликт считается разрешенным.


## Работа с удаленными репозиториями в Git

* *git status* - проверка статуса;

* *clear* - очистка терминала;

* *git clone <адрес>* - копия репозитория;

*git log* - посмотреть изменения;

*q* - выход;

*git log --graph* - лог в виде графа;

*git push* - отправить в удаленный репозиторий;

*git pull* - вытянуть с удаленного репозитория;

*кнопка Fork на Github* - создать ответвление от чужого репозитория, с сохранением связи;

*README.md* - файл с описанием проекта.

Примечание: при fork изменения проводятся в новой ветке.