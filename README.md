# Docker console шпаргалка

Здесь собраны самые важные Docker-команды, как для новичка так и для продвинутого Docker-владельца. 
_(А если честно, то просто писал для себя, чтобы не юзать интернеты и не тупить)_


## 🔄 Работа с docker-compose
`docker-compose up` – [Поднимаем/роняем контейнера](#docker-compose-up) <br/>
`docker-compose down` – [Роняем контейнера](#docker-compose-down) <br/>
`docker exec` – [Заходим в контейнер](#docker-exec) <br/>

#
 
<br/><br/>
## 📝 Подробное описание команд
<br/>

### docker-compose up
`docker-compose up` – запускает контейнера прописанные в файле docker-compose.yml
```
docker-compose up -d  # поднимаем докер композ, -d = --detach (запуск в фоне)
```
<br />

### docker-compose down
`docker-compose down` – отключает контейнера
```
docker-compose down  # роняем докер композ
```
<br />

### docker exec
`docker exec` – позволяет выполнять команды внутри уже запущенного контейнера Docker без необходимости входить в него интерактивно или перезапускать контейнер.
```
docker exec -it <имя контейнера> bash    # заходим в контейнер
docker exec <имя контейнера> -s reload   # перезагружаем настройки контейнера
```
<br />










[Пошли наверх](#docker-console-шпаргалка) <br/>