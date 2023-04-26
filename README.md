## Laravel creative blog  

[Плейлист](https://www.youtube.com/watch?v=UqlVcp21X7c&list=PLd2_Os8Cj3t8StX6GztbdMIUXmgPuingB&index=1)

Стоп: [4. Ставим фронт админки, установка Admin Lte](https://www.youtube.com/watch?v=UUCrtd39MCE&list=PLd2_Os8Cj3t8StX6GztbdMIUXmgPuingB&index=9)

### 1. Подключаем bootstrap, auth и базу данных  
```sh  
composer require laravel/ui  
php artisan ui bootstrap  
php artisan ui:auth  
npm install && npm run dev  
```  

### 2. Первоначальный план и создаем миграции  
```sh  
php artisan make:model Post -m  
php artisan make:model Category -m  
php artisan make:model Tag -m  
php artisan make:model PostTag -m  
php artisan migrate  
```  

### 3. Подгружаем фронт страницы блога. Список постов  
```sh  
php artisan make:controller Main/IndexController  
```  

### 4. Ставим фронт админки, установка Admin Lte  
[AdminLTE](https://adminlte.io/)  