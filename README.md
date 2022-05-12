### Проект «API для Yatube».

### Описание
Разработан REST API для проекта Yatube с спользованием Django REST Framework. Авторизация через JWT токены. Создание и удаление записей в дневниках используя API
интерфейс. Создание пользователя через API с подтверждением по электронной почте и выдачей JWT токенов. Разграничение прав доступа пользователей. Разработана документации к проекту.

#### Инструкция по развёртыванию
* Клонировать репозиторий и перейти в него в командной строке:
```python
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