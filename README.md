# Laravel 8 - Now UI Dashboard

## Comenzando 🚀

_Sigue las siguientes instruscciones para clonar este repositorio en tu máquina local y poder trabajar con Laravel 8 Now UI Dashboard._

### Pre-requisitos 📋

Para clonar este repositorio, debes tener instalado un servidor Apache, PHP y MSQL (Wamp, Xampp, Mamp o Lamp) y los gerenciadores de dependencias para PHP (Composer).

Antes de comenzar verifica si tienes composer con cualquiera de los siguientes comandos en tu terminal.
```
composer --version 
composer -v
```
Si no lo tienes instalado lo pueden instalar siguiendo la documentación oficial en:  
https://getcomposer.org/doc/00-intro.md


Verifica las versiones de cada uno de ellos

Versión PHP - 7.4.2  
Versión Mysql - 5.7.26  
Versión Composer - 1.10.1  

### Instalación 🔧

_Sigue las siguientes instrucciones para clonar el repositorio_

_Clone el repositorio_

```
git clone https://github.com/jorgehernandezch/Laravel-8-Now-UI-Dashboard.git
```

_Instale todas las dependencias del Proyecto con_

```
composer install
```

_Instale todas las dependencias JS con_

```
npm install
```

_Copie el Archivo .env.example en un archivo nuevo .env con_

```
cp .env.example .env
```
_Configure la base de datos y las demas variables de entorno en el archivo .env_

_Genere una nueva Key para el protecto con_

```
php artisan key:generate
```

_Corra las migraciones del proyecto con_

```
php artisan migrate
```

_Corra los seeder del proyecto con_

```
php artisan db:seed
```
_Corra el proyecto con_

```
php artisan serve
```

_Si todo está correcto puede acceder al proyecto en la dirección http://localhost:8000, ingrese usuario y contraseña que está por defecto en el formulario de login._

---
[Jorge Edo. Hernández](https://github.com/jorgehernandezch)  
_Ingeniero y Desarrollador Web_
