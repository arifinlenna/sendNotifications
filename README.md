## Step 1: Make Configuration

-   .env

MAIL_DRIVER=smtp
MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USERNAME=mygoogle@gmail.com
MAIL_PASSWORD=rrnnucvnqlbsl
MAIL_ENCRYPTION=tls
MAIL_FROM_ADDRESS=mygoogle@gmail.com
MAIL_FROM_NAME="${APP_NAME}"

## Step 2: Create Mail

-   php artisan make:mail MyTestMail

_big thanks information by_ :
*https://www.itsolutionstuff.com/post/laravel-8-mail-laravel-8-send-email-tutorialexample.html*
