## Установка и запуск проекта
1. Проект написан на Python и Node.js

2. В комнадной строке клонируйте этот репозиторий себе на компьютер:
```
$ git clone git@github.com:gresha9906/infra_sprint1.git
```

3. Перейдите в папку infra_sprint1
```
$ cd infra_sprint1
```

4. Создайте и активируйте виртуальное окружение:
```
$ python3 -m venv venv

$ source venv/bin/activate
```

5. Установите зависимости проекта:
```
$ python -m pip install --upgrade pip

$ pip install -r requirements.txt
```

6. Перейдите в папку проекта и выполните миграции:
```
$ cd backend

$ python manage.py migrate
```

7. Запустите проект:
```
$ python manage.py runserver
```

### Сейчас backend проекта должен быть доступен по адресу: http://127.0.0.1:8000/
### *Для установки и запуска frontend проекта:*


1. Перейдите в папку infra_sprint1/frontend/ (если находитесь в папке backend):
```
$ cd ../frontend
```

2. Проверьте, что установлен пакетный менеджер npm и установите зависимости для фронтэнд приложения:
```
$ npm -v

$ npm i
```

3. Запустите фронтэнд приложение:
```
$ npm run start
```

### Приложение должно быть доступно по адресу: http://127.0.0.1:3000/

### Настройки Nginx и Gunicorn находятся в директории infra.

