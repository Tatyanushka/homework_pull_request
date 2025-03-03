# Инструкция по работе с Git
Для создания локального репозитория, нужно запустить команду:
> git init

Для добавления файла к следующему коммиту, нужно ввести команду:
> git add

Для фиксации (создания) коммита, нужно запустить команду:
> git commit

Для отслеживания текущего состояния репозитория, можно ввести команду:
> git status

Чтобы посмотреть все коммиты, используем команду:
> git log

Для просмотра разницы между закоммиченными файломи и текущими изменениями, вводят команду:
> git diff

Для перехода к прошлым коммитам (c кодом commit_code),можно использовать команду:
> git checkout commit_code
а чтобы вернуться к актуальному состоянию и продолжить работать:
> git checkout master

Для всех веток, нам нужно:
> git branch
Чтобы создать ветку, нужно:
> git branch branch_name

Для совмещения текущей ветки с веткой branch_name, нужно:
> git merge branch_name
изменения добавятся в текущую


Для того чтобы удалить ветку branch_name, нужно ввести:
> git branch -d branch_name


Для визуализации веток, можно использовать:
> git log --graph


Если наша ветка не полностью замерджена, то с помощью тега -d удалить ее не получится, тогда нужно использовать тег -D:
> git branch -D branch_name

Чтобы добавить картинку, нужно ввести:
![GitHub](GitHub.png)


# Инструкция по работе с Markdown

Для выделения заголовка в начале строки нужно поставить символ "#" (количество символов "#" задает уровень заголовка). Например:
# Заголовок
## Заголовок

Чтобы задать для текста полужирное начертание, нужно заключить его в двойные звездочки "**" или "__". Например, вот так:
**полужирное начертание**,
__полужирное начертание__

Чтобы задать для текста курсивное начертание, нужно заключить его в одинарные звездочки "*" или "_". Например:
*курсивное начертание*,
_курсивное начертание_

Чтобы задать для текста полужирное и курсивное начертание, нужно заключить его в тройные звездочки "***". Например:
 ***полужирное и курсивное начертание***

Чтобы зачеркнуть текст, необходимо заключить его в символы "~~". Например:
~~зачеркнутый текст~~


# Списки
Чтобы получить ненумерованные списки, необходимо в начале строки поставить звездочку "*". Например:
* Список 1
* Список 2
* Список 3

Чтобы получить нумерованный список, нужно пронумеровать их - "1,2,3". Например:
1. Список 1
2. Список 2
3. Список 3

Блоки цитирования создаются с помощью символа ">". Отображается с отступом и имеет другой цвет фона. Например:
> Блок цитирования

## Инструкция по работе с удаленными репозиториями на GitHub

1. Делаем Fork интересующего нас репозитория.
2. Клонируем внешний (удаленный) репозиторий на наш локальный ПК, с помощью команды:
> git clone <url-адрес репозитория>
3. Производим все изменения только в данной ветке (делаем коммиты).
4. Отправляем все изменения локального репозитория на внешний репозиторий, с помощью команды:
> git push
5. В окне на GitHub появляется возможность отправить pull request с нашими изменениями.





