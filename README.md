# Git cheatsheet 🚀

Мини-шпаргалка по самым нужным командам Git.

---

### Настройка

```bash
git config --global user.name "Имя"
git config --global user.email "your.email@example.com"
git config --list   # показать текущие настрой 
```

### Создание репозитория
 
```bash
git init              # инициализация репозитория
git clone URL         # клонирование удалённого репо
```

### Работа с файлами 

```bash
git status            # статус репозитория
git add file.txt      # добавить файл в индекс
git add .             # добавить все изменения
git commit -m "msg"   # зафиксировать изменения
```

### История и просмотр

```bash
git log               # история коммитов
git diff              # показать изменения
```

### Ветки

```bash
git branch            # список веток
git branch new-branch # создать ветку
git checkout new-branch   # переключиться
git checkout -b new-branch # создать и сразу переключиться
git merge branch-name     # слить ветку 
```

### Работа с Git 

```bash
git remote add origin URL  # подключить удалённый репо
git push -u origin main    # загрузить изменения
git pull                   # стянуть изменения
```

### Отмена изменений 

```bash
git reset file.txt         # убрать из индекса
git checkout -- file.txt   # отменить изменения в файле
```
