# <p style="text-align: center;">**Tutor git and code python**</p>

## <p style="text-align: center;">Что такое git</p>
---
>Git распределённая система управления версиями. Проект был создан Линусом Торвальдсом для управления разработкой ядра Linux, первая версия выпущена 7 апреля 2005 года. На сегодняшний день его поддерживает Джунио Хамано. 

---
### Menu
1. [Git command](#git-command)
2. [Quotes](#quotes)
3. [Code](#code)
4. [Email](#email)

---
### Git command
---
* **git --help** - Всё по гиту
* **git init** - инициализация гита
* **git status** - проверка статуса файлов
* **git diff** - Просмотр изменений
* **git add** - добавление файла для дальнейшего коммита
* **git add .** - добавление все файла для дальнейшего коммита
* **git commit -m "описание коммита"** - коммит файла
* **git log** - список коммитов
* **git checkout номер коммита/master** - переключится на коммит или вернуться к ветки мастер
* **git branch <Название ветки>** - Создать ветку
* **git branch -d <Название ветки>** - Удаление ветки
* **git branch** - Просмотр ветки в которой находишься
* **git checkout -b <Название ветки>** - Создание ветки и переход на неё
* **git merge <Название ветки>** - Слияние веток
* **git merge --abort** - Отменить слияние веток
* **git log --graph** - Визуализировать лог коммитов
* **git push** - Залить репозиторий на удаленный Git
* **git pull** - Подтянуть изменения из удаленного репозитория

---
### Quotes
---
> Я сказал братьям, что «Книга Мормона» — самая верная из всех книг на Земле и замковый камень нашей религии, и человек станет ближе к Богу, живя по ее учениям, чем по учениям любой другой книги. 
>
> *Джозеф Смит (1805–1844) — американский религиозный деятель*

> Открыв антологию религиозных текстов, я сразу напал на такое изречение Будды: «Ни один предмет не стоит того, чтобы его желать». Я тотчас же закрыл книгу, ибо что еще читать после этого? 
>
> *Эмиль Мишель Чоран (1911–1995) — румынский и французский мыслитель-эссеист*

>Если человек не нашёл, за что может умереть, он не способен жить
>
> *Мартин Лютер Кинг*

>Чем умнее человек, тем легче он признает себя дураком
>
> *Альберт Эйнштейн*

>Безвыходным мы называем положение, выход из которого нам не нравится.
>
> *Станислав Ежи Лец*

> Жизнь состоит не в том, чтобы найти себя. Жизнь состоит в том, чтобы создать себя.
>
> *Джордж Бернард Шоу*

---
### Code
---
**Просто код и просто на python**

```
numbers = [2, 5, 13, 7, 6, 4]
size = len(numbers)
index = 0
max_idx = 0
max = numbers[max_idx]

while index < size:
    if numbers[index] > max:
        max_idx = index
        max = numbers[index]
    index = index + 1

numbers[max_idx] = numbers[size - 1]
numbers[size - 1] = max
print(numbers)
```

```
def capitalize(String):
    return String.title()
capitalize("shop")
capitalize("python programming")
capitalize("how are you!")
```

```
n=5
string="Hello World "
print(string * n)
```

```
from collections import Counter
def anagrams(str1, str2):
    return Counter(str1) == Counter(str2)
anagrams("abc1", "1bac") # True
```

```
my_list = ["leaf", "cherry", "fish"]
my_list1 = ["D","C","B","A"]
my_list2 = [1,2,3,4,5]

my_list.sort() # ['cherry', 'fish', 'leaf']
my_list1.sort() # ['A', 'B', 'C', 'D']
print(sorted(my_list2, reverse=True)) # [5, 4, 3, 2, 1]
```

![img](Python.jpg)

---
### Email
---
* Для связи с нами пишите на e-mail
    * [могу все что хочу](https://mail.ru/)
    * [не могу все что хочу](https://yandex.ru/)
    * [а вдруг](https://google.ru/)
    * [не точно](https://yandex.ru/)
    * [грамотно](https://google.ru/)