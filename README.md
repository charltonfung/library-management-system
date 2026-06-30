1. 在目錄下執行生成 API TOKEN
```
node generateToken.js
```

2. 在目錄下新增.env檔
```
DB_HOST=
DB_USER=
DB_PASSWORD=
DB_NAME=library
API_TOKEN=(套用 API TOKEN)
```

3. 執行./config/library.sql內容建立3個talbe
4. 執行npm install
5. 執行nodemon app.js
