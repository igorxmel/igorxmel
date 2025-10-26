
<div style="justify-self: center; display: flex; font-family: 'Arial'">
<img src="frontend/src/components/img/logo.svg" width="100px" margin-right="10">
<p style="font-size: 100;">Giga</p><p style="font-size: 100; color: #347bfd">NET</p>
</div>

<hr>

> [!WARNING]
> Продукт еще не готов к выпуску, есть много недочетов, возможны баги

> 🏆 Этот проект был разработан в рамках хакатона **Хакатон Осень 2025** (24-26 октября 2025) <br>
> <img src="https://img.icons8.com/fluency/48/000000/microsoft-powerpoint-2019.png" width="20" height="20" style="margin-bottom: -4"/> **[Презентация проекта](GigaTeamTitanit.pptx)**  

<br>

GigaNET - интеллектуальная платформа, которая помогает пользователям находить нужных людей для широкого круга задач — дружбы, совместных проектов, работы, обучения или простого общения. В основе платформы лежат продвинутая аналитика, алгоритмы машинного обучения и интуитивно понятное ВЕБ приложение.

## Stack:

- <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width="13" height="13"/> Python  
- <img src="https://cdn.worldvectorlogo.com/logos/fastapi-1.svg" width="13" height="13"/> FastAPI  
- <img src="https://img.icons8.com/color/48/000000/react-native.png" width="13" height="13"/> React  
- <img src="https://img.icons8.com/color/48/000000/html-5--v1.png" width="13" height="13"/> HTML5  
- <img src="https://img.icons8.com/color/48/000000/css3.png" width="13" height="13"/> CSS3  
- <img src="https://img.icons8.com/color/48/000000/javascript--v1.png" width="13" height="13"/> JavaScript  
- <img src="https://img.icons8.com/color/48/000000/postgreesql.png" width="13" height="13"/> PostgreSQL  
- <img src="https://img.icons8.com/color/48/000000/figma--v1.png" width="13" height="13"/> Figma ([ссылка на проект](https://www.figma.com/design/EHez8gFEp24QpTw1GITMRQ/Untitled?node-id=0-1&p=f&t=F9OU8Og8CvuYoag2-0))

## Хакатон Осень 2025:

1) Для успешного запуска клонируйте репозиторий, пользуясь документацией sourcecraft.dev <img src="https://46f32a42-e4ff-489b-8e03-b52e4d70fd18.selcdn.net/i/webp/ae/2c80468dba726b4abd8de3d5ff6f03.webp" style="width: 16; margin-bottom: -4">

2) Перейдите в папку frontend:
```cmd
cd frontend
```

3) Установите зависимости:
```cmd
npm install
```
- `cd ..` чтобы выйти в основную директорию

4) Перейдите в папку backend:
```cmd
cd backend
```

5) Установите зависимости:
```cmd
pip install -r requirements.txt
```

6) Установите PostgreSQL с официального сайта и создайте базу данных с именем `people_app`

7) Создайте .env файл:
```
DATABASE_URL=postgresql+asyncpg://YOUR_DB_USER:USER_PASSWORD@YOUR_DB_IP:YOUR_DB_PORT/people_app
SECRET_KEY=your-super-secret-key-change-in-production-min-32-chars-long
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=120
REFRESH_TOKEN_EXPIRE_DAYS=7
FRONTEND_URL=http://localhost:3000
```
- Данные по типу `YOUR_DB_USER`/`USER_PASSWORD` и тд. вставлять свои данные
- База данных работает на основе сервера PostgreSQL

8) Запустите API-сервер:
```cmd
uvicorn app.main:app --reload
```
- Документацию к API можно посмотреть [тут](http://localhost:8000/redoc) (прямая ссылка: http://localhost:8000/redoc)

9) **Создайте новый терминал** и перейдите в папку frontend:
```cmd
cd frontend
```

10) Запустите веб-приложение:
```cmd
npm run dev --host
```
- ссылки для подключения к сайту появятся в том же терминале

<br>
<hr>
<br>

<div style="justify-self: center; font-family: 'Arial Black'; font-size: 50px">
Слава sourcecraft.dev! <img src="https://46f32a42-e4ff-489b-8e03-b52e4d70fd18.selcdn.net/i/webp/ae/2c80468dba726b4abd8de3d5ff6f03.webp" style="width: 56; margin-bottom: -8">
</div>
