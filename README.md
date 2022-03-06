# ubuntu_nginx_timezone

### Update Ubuntu -更新 Ubuntu
`apt-get update`

### Set Timezone - 設定 Ubuntu 時區
1. `timedatectl list-timezones` 顯示時區
2. `timedatectl set-timezone Asia/Taipei` 設定時區為台灣台北

### Install Nginx -安裝 Nginx

`apt-get install nginx`

### Set domain for Nginx -Nginx 指定網域
1. `nano /etc/nginx/sites-available/default`
2. find `server_name _` . and replace `_` with `yoururl.tw`. _ 取代為你的網址
3. `ctrl + o` to save file 存檔
4. `service nginx reload`
5. `service nginx restart`
