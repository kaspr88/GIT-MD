![alt text](/logo@2x.png)
## Инструкция по системе контроля версий Git
---
[Оффициальный сайт](https://git-scm.com/)

[Инструкция по установке](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-Git)

**`git --version`** - версия git

**`git init`** - Позволяет проинициализировать репозиторий в текущей папке

**`git status` -** Показывает текущий статус

**`git add`** - добавить файл в репозиторий Отслеживает изменения файлов

> `git add index.html` — добавляет index.html(Можно использовать Tab)

> `git add` . — добавляет все файлы

**`git commit -m "добавил файл”` -** добавляет изменений в репозиторий и комментарий(**-m**) к сохранению 

**`git log --oneline` -** журнал изменений

**`git chekout 87b2` -** возвращение к определенной версии имя версии проверить в журнале. Переключается на другую ветку

> `git checkout branch-name` — переключается на последний коммит в ветке branch-name

> `git checkout -b branch-name` — создает и переключается на ветку branch-name

**`git diff` -** показывает отличие сохраненного файла commit

**`git branch` -** Работа с ветками в репозитории

> `git branch` — показывает список веток
> 

> `git branch branch-name` — создает новую ветку branch-name

> `git branch -d branch-name` — удаляет ветку branch-name

**`git merge` -** Совмещает текущую ветку с выбранной

> `git merge branch-name` — совмещает текущую ветку с branch-name
> 

**`git config` -** Конфигурация и параметры git

> `git config --global user.name` — Показывает имя пользователя
> 

> `git config --global user.name 'new user'` — Изменяет имя пользователя
> 

> `git config --global user.email` — Показывает email пользователя
> 

> `git config --global user.email 'test@mail.ru'` — Изменяет email пользователя
> 

**`git push` -** Заливает текущие локальные коммиты в удаленный репозиторий

**`git pull` -** Забирает изменения с удаленного репозитория в локальный

**`git clone` -** Клонирует проект с удаленного репозитория

**`git rebase -i (имя комита)` -** Редактирование коммита

**`git rebase --abort`** - Отмена редактирование коммита

Команды для залики репозитория на Guthub

**`git remote add origin https://github.com/kaspr88/GIT-MD.git`**

**`git branch -M main`**

**`git push -u origin main`**

<details>
<summary>Чтоб не скучтно было))</summary>
<br>

![Чтоб не скучтно было))](/11.jpg)

</details>

проверка pull
