server {
    listen 80;
    listen [::]:80;
    server_name  anvelazquez.cse356.compas.cs.stonybrook.edu;

    root /var/www/anvelazquez.cse356.compas.cs.stonybrook.edu;
    index hw0.html;

    location / {
        try_files $uri $uri/ =404;
    }
}