# Подсказак по Git

Создали репозиторий 
```
git init
```
Добавление отдельных файлов или всех файлов в область подготовленных файлов
```
git add somefile.js
```
 Внесение изменений однострочным сообщением или через редактор
 ```
 git commit - m 'комиты текст'
 ```
  Просмотр истории коммитов с изменениями
  ```
  git log
  ```
  в одну строку 
  ```
  git log --p
  ```
  перемещение по веткам

  ```
  git checkout <имя_ветки>
  ```
  Восстановить файлы рабочего дерева, не подготовленные к коммиту.

  Добавили картинку в инструкцию
  ![apple](apple.ipg.jpg)

  # Обьединение ветотк
  ```
  git merge
  ```
  Отображение всех веток 
  ```
  git branch
  ```

  Создание новой ветки + Конфликт

```sh
git branch <имя_ветки>
```

  ### Создание 4 веток и конфликта !
  с помошью команды 
  ```sh
git branch <Name_txt>
```
я создал ветку 
