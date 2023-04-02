# Git tutorial

## Клонирование репозитория

*Клонировать удаленный репозиторий в одноименную директорию*

```
git clone https://github.com/cyberspacedk/Git-commands.git    
```

*Клонировать удаленный репозиторий в директорию «FolderName»*

```
git clone https://github.com/cyberspacedk/Git-commands.git FolderName 

```

*Клонировать репозиторий в текущую директорию*

```
git clone https://github.com:nicothin/web-design.git.
```

## Внесение изменений» в коммит

### Указана последовательность действий:

*редактируем и сохраняем разметку «шапки»*

```
subl inc/header.html          
```
*Индексируем измененный файл*

```
git add inc/header.html
```

*Делаем коммит*

```
git commit -m "Убрал телефон из шапки" 
```

## Синхронизация репозитория-форка с мастер-репозиторием