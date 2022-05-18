### 1. Downloade FFMPEG
Downloade This Tools On Your Divece From Here
```bash
https://www.ffmpeg.org/

```

### 2. Install Laravel
```bash
Composer install
```
- Create a New .env File
- Could Copy From Existing .env.example, Update Relevant Settings (DB_DATABASE, DB_USERNAME,.....)

- Generate App Encryption Key
```bash
php artisan key:generate
```
```bash
php artisan migrate
```


- Downloade FFMPEG & Add Paht Package In ENV File
```bash
FFMPEG_BINARIES=YourPath\ffmpeg.exe
FFPROBE_BINARIES=YourPath\ffprobe.exe
```

## 3. Package & Tools Used

- **[Laravel FFMPEG ](https://github.com/protonemedia/laravel-ffmpeg)** [ v 7.5.11 ]

- **[Intervention Image" ](https://image.intervention.io/v2/introduction/installation)** [ v 2.7.1 ]

- **[Laravel Ffmpeg" ](https://github.com/protonemedia/laravel-ffmpeg)** [ v 7.7.2 ]

