---
##### _Для того что-бы развернуть и запустить данный проект, выполните следующие команды:_
- Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/dagistanik/api_final_yatube.git
```
```
cd api_final_yatube
```
- Cоздать и активировать виртуальное окружение:
```
python -m venv env
```
```
source venv/Scripts/activate
```
- Установить зависимости из файла requirements.txt:
```
python -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```
- Выполнить миграции:
```
python manage.py migrate
```
- Запустить проект:
```
python3 manage.py runserver
```