# Lab 3: Управление директориями

---

## 1. Создание структуры

```bash
cd ~
mkdir -p projects/testproject/{docs,src}
echo "Test project initialized." > projects/testproject/README.md
```

![mkdir](images/mkdir.png)

* * *

## 2. Перемещение проекта

```bash
mv projects/testproject /tmp/
```

![mv](images/mv.png)

* * *

## 3. Проверка структуры

```bash
ls -R /tmp/testproject
cat /tmp/testproject/README.md
```

![ls](images/ls.png)

* * *

## 4. Копирование проекта обратно

```bash
cp -r /tmp/testproject ~/project_copy
```

![cp](images/cp.png)

## 5. Проверка структуры копии

```bash
ls -R ~/project_copy
```

* * *

## 6. Просмотр прав доступа
```bash
ls -ld ~/project_copy
ls -l ~/project_copy
```

![ls_l](images/ls_l.png)

* * *

## 7. Удаление из /tmp

```bash
rm -r /tmp/testproject
```

![rm](images/rm.png)

* * *

## 8. Убедиться, что копия осталась

```bash
ls ~/project_copy
```

![ls_last](images/ls_last.png)

* * * 

## Выводы

- `mkdir -p` позволяет быстро создать вложенную структуру.
- `echo >` удобно использовать для создания и наполнения файлов.
- `mv` и `cp -r` помогают перемещать и копировать директории с содержимым.
- `ls -R` полезен для просмотра всей структуры сразу.
- Проверка через `ls -ld` и `ls -l` показывает права доступа и владельцев.
- `/tmp` удобно использовать как временное хранилище.
