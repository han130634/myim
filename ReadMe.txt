test im demo

1.Start chatting application by the command code .
php -q php-socket.php

2.Port used result image .
start.jpg

3.Chatting on the website, visit the url address .
http://127.0.0.1/myim/index.php

4.Chatting result images .
result.jpg

Other help information:

1.check port used : 8090
# lsof -i :8090

2.free 8090
# kill -9 $(lsof -t -i :8090)
