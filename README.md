# Repository
---

## Create a new repository on the command line
```MARKDOWN
echo "# first-project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:%имя_аккаунта%/%имя_проекта%.git
git push -u origin main
```

## Push an existing repository from the command line
```MARKDOWN
git remote add origin git@github.com:%имя_аккаунта%/%имя_проекта%.git
git branch -M main
git push -u origin main
```
<br>
<br>
<br>

# Markdown
---


## Заголовки
```
# H1 — заголовок первого уровня, самый большой
## H2 — заголовок второго уровня, поменьше
### H3
#### H4
##### H5
###### H6 — заголовок шестого уровня, самый маленький
```


## Выделение текста
### Курсив
```
Курсив — это *звёздочки* или _подчёркивания_.
```

### Полужирный шрифт
```
Полужирный шрифт — двойные **звёздочки** или двойные __подчёркивания__.
Можно совместить выделение **звёздочки и _подчёркивания_**.
```

### Зачеркнутый текст
```
~~Зачёркнутый текст.~~
```

## Списки
### Нумерованный список
```
1. Первый пункт нумерованного списка.
2. Второй пункт.
```

### Ненумерованный список
```
* первый пункт ненумерованного списка;
* второй пункт ненумерованного списка

- первый пункт ненумерованного списка;
- второй пункт ненумерованного списка;
```

[Оформление файла README.md](https://practicum.yandex.ru/trainer/git-basics/lesson/c6b9607c-e8bc-4446-89f9-c74522c3492f/) <br>
[Markdown Cheat Sheet | Markdown Guide](https://www.markdownguide.org/cheat-sheet/)
