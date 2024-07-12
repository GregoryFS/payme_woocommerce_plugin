# Payme woocommerce plugin

## Установка

#### GitHub

Загрузите плагин в WordPress

Шаг 1.

![Step 1](images/1.jpg)

Шаг 2.

![Step 2](images/2.jpg)

Шаг 3.

![Step 3](images/3.jpg)

Шаг 4.

![Step 4](images/4.jpg)

Шаг 5.

![Step 5](images/5.jpg)

Шаг 6.

![Step 6](images/6.jpg)

Шаг 7.

![Step 7](images/7.jpg)

Шаг 8.

![Step 8](images/8.jpg)

Шаг 9.

![Step 9](images/9.jpg)

Шаг 10.

![Step 10](images/10.jpg)

Шаг 11.

![Step 11](images/11.jpg)

Шаг 12.

![Step 12](images/12.jpg)

Шаг 13.

![Step 13](images/13.png)

Итог 

![Finish](images/14.png)


Примечание:

#### Что бы Apache не игнорировал заголовок `Authorization` надо загрузить файл `.htaccess` со следующем содержанием:

```
RewriteEngine On
RewriteCond %{HTTP:Authorization} ^(.*)
RewriteRule .* - [e=HTTP_AUTHORIZATION:%1]
```