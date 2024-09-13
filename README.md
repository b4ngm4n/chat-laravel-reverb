## Simple Chat Apps Laravel 11 & React
Aplikasi chat ini dibangun menggunakan framework laravel 11 dan react js dengan mengacu pada pembelajaran pada laman berikut
https://www.freecodecamp.org/news/laravel-reverb-realtime-chat-app/

anda dapat belajar langsung disana. dan anda dapat melakukan clone project ini sebagai dasar atau starterkit

### Clone this project 
```bash
git clone https://github.com/b4ngm4n/chat-laravel-reverb.git
```

### Move to project
```bash
cd chat-laravel-reverb
```

### Configure

```bash
composer install
```

```bash
php artisan key:generate
```

If you using npn you can run this command
```bash
# npm install && npm run dev
```

### Setup Database

```bash
cp .env.example .env
```

```bash
nano .env
```

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=chat_reverb
DB_USERNAME=root
DB_PASSWORD=
```

```bash
php artisan migrate
```

