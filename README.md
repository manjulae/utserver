# utserver
Dockerized Utorrent Server

`docker pull mcraft/utserver`

`docker run -d -p 127.0.0.1:8080:8080 --restart=unless-stopped -v ~/Torrents:/opt/downloads utserver`

`http://127.0.0.1:8080/gui/`

Default User: Admin

Default Password: No Password

Go to Settings -> Directories -> Put new downloads in: `/opt/downloads` -> Move completed downloads to: `/opt/downloads`

Enjoy
