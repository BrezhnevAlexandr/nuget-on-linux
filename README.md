# nuget-on-linux
Перед стартом скачать docker-compose и dockerfile
 Для старта зайти, используя docker, в директорию, в которой располжен docker-compose и выполнить команду:
 ```
 docker-compose up
 ```
 если ни чего не менять то сервер по умаолчанию доступен в localhost
 
 Для публикации своих пакетов на сервер можно воспользоваться следующим синтаксисом утилиты nuget.exe: ``` nuget push {package file} -s http://localhost:[port]/ {apikey} ``

apikey  по умолчанию 112233
