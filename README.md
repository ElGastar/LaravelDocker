# LaravelDocker
Commit 39170de - базовая настройка php+nginx

Commit 221f710 - Установка Laravel,что бы обойти ошибку UnexpectedValueException ,заходим контейнер php, в папке где находиться storgae запускаес следующие комманды 
 - chgrp -R www-data storage bootstrap/cache
 - chmod -R ug+rwx storage bootstrap/cache
