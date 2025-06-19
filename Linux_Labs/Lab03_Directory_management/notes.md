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

