# ubuntu_nginx_timezone

### Update Ubuntu -更新 Ubuntu
`apt-get update`

### Set Timezone - 設定 Ubuntu 時區
`timedatectl list-timezones`

### Install Nginx -安裝 Nginx

`apt-get install nginx`

### Set domain for Nginx -Nginx 指定網域
1. `nano /etc/nginx/sites-available/default`
2. find `server_name _` . and replace `_` with `yoururl.tw`. _ 取代為你的網址
3. `ctrl + o` to save file 存檔
4. `service nginx reload`
5. `service nginx restart`
