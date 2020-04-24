# nuget-on-linux
Перед стартом скачать docker-compose
Исправить следующие поля:
 ``` NUGET_API_KEY: "112233" ``` - вставить свой API_KEY
 ``` SERVER_NAME: "nuget.example.com ``` - поменять на свое
 
 по умолчанию порт ``` 8080 ```
 Для старта зайти, используя docker, в директорию, в которой располжен docker-compose и выполнить команду:
 ```
 docker-compose up
 ```
 если ни чего не менять то сервер по умаолчанию доступен в localhost
 
 файлы загружать командой ``` nuget push имяфайла.nupkg -source SERVER_NAME -apikey NUGET_API_KEY ```
 выгружать командой ``` nuget install имяфайла -source SERVER_NAME -packagesavemode nupkg ```
