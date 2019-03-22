start docker-compose up --build
# copies files

cancel and docker-compose down
# cancel and shut down

add
```
define('WP_HOME', '/blog');
define('WP_SITEURL', '/blog');
$_SERVER['REQUEST_URI'] = str_replace("/", "/blog/",  $_SERVER['REQUEST_URI']);
```
at the beginning of wp-config.php

docker-compose up --build

make installation

docker-compose down

remove 3 lines added to wp-config.php

docker-compose up --build

in the settings change to permalink
settings -> permalink -> choose whatever

https://zihao.me/post/hosting-static-website-with-kubernetes-and-google-cloud-storage/
https://github.com/zzh8829/zihao/tree/master/deploy

https://zihao.me/post/hosting-static-website-with-kubernetes-and-google-cloud-storage/


# serve root page from google storage
https://stackoverflow.com/questions/51156523/nginx-proxy-pass-to-google-storage-bucket-does-not-use-the-index-directive
