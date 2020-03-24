online-order-api

#Membuat project dan install modul

Buka terminal lalu ketik command di bawah ini untuk install express-generator dan touch-cli
```sh
npm i –s -g express-generator touch-cli
```

Lalu buatlah project menggunakan express-generator dengan nama project online-order-api
```sh
express online-order-api --view=ejs
```

Selanjutnya masuk ke folder project dan install modul yang diperlukan
```sh
cd online-order-api/ && npm i
```

#Konfigurasi Sequelize

Pertama install Sequelize-cli
```sh
npm i -s -g sequelize-cli
```

Lalu instal modul Sequelize
```sh
npm i -s sequelize
```
Kemudian install modul database PostgreSql
```sh
npm i -s pg pg-hstore
```
