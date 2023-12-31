# Подсказка по GIT

1. Создание репозитория

```sh
git init
```
Добавили указанную папку в репозиторий для отслеживания GIT 

2. Отслеживание файла

```sh
git add
```
Добавили отслеживание созданного файла для дальнейшего сохранения и работы

3. Добавление комментария
```sh
git commit -m "Message text"
```
Добавление комментария к введенному тексту

4. Просмотр изменений в файле

```sh
git log
```
Функция просмотра изменений в файле и комментарий к этим изменениям

5. Вывод всех изменений к текущему файлу

```sh
git log --oneline
```
Вывод всех изменений в файле списком

6. Возврат к предыдущим версиям файла

```sh

git checkout <branch name>

```
Возможность возврата к предыдущим версиям файла 

7. Сравнение изменений ранее сохраненной версии файла с текущей версией

```sh
git diff
```
Функция сравнения предыдущей сохраненной версией файла с текущей

# Добавим как добавлять картинки в Marddown

Это BMW
![Бумер](BMW.png)

Отображение всех веток созданных в файле
```sh
git branch
```
Создание новой ветки
```sh
git branch <add new branch>
```
Delete branch
```sh
git branch -d <branch_name>
```
Вывод всех веток и всех изменений
```sh
git --oneline --graph
```

Добавили картинку с ауди
![ауди](audi.png)

# Добавление ссылок 

Так выглядит добавленная ссылка на сайт яндекс:

[ЖМИ](https://www.yandex.ru)

