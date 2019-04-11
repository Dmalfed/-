#Лабораторная работа №1
## Создание виртуального окружения
Создается через модуль virtualenv
```
pip install virtualenv
```
Используется команда python -m virtualenv и название директории, в которой требуется создать окружение.
```
mkdir projectname
cd projectname
python -m virtualenv env
```
Использование:

Для активации окружения необходимо запустить activate.bat в директории с виртуальным окружением.
```
C:\project\env\Scripts\activate.bat
pip install jupyterhub
pip install jupyterlab
C:\project\env\Scripts\deactivate.bat
```

## Запуск Jupyter
```
jupyter lab 
```
