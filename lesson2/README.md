# Занятие 2

Занятие было посвещяно инструментам Data Scientist. Говорили о Python, библиотек для него (numpy и pandas).
А так же о Jupiter notebook.

## Как настроить виртуальную среду

Создать виртуальную среду с именем *test_venv*.

```cmd
python3 -s venv 'test_venv'
```

Активировать виртуальную среду

```cmd
source test_venv/bin/activate
python3 -m ipykernel --user --name test_venv
```

Теперь должна быть виртуальная среда

#### Может пригодится

```cmd
pip install ipykernel
```

## Запуск Jupiter notebook

```cmd
jupyter notebook
```
