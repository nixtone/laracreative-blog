## Laravel creative blog  

[Плейлист](https://www.youtube.com/watch?v=UqlVcp21X7c&list=PLd2_Os8Cj3t8StX6GztbdMIUXmgPuingB&index=1)

Стоп: [3. Подгружаем фронт страницы блога. Список постов](https://www.youtube.com/watch?v=ShuXAn2FAxw&list=PLd2_Os8Cj3t8StX6GztbdMIUXmgPuingB&index=4)

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

### 3.  
```sh  
php artisan make:controller Main/IndexController  
```  