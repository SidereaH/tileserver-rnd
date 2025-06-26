## South Russia OpenMapTiles
To run:
```
wget https://hutornoyaa.fvds.ru/public/south_russia_z14.zip
unzip south_russia_z14.zip
docker run --rm -it -v $(pwd):/data -p 8080:8080 maptiler/tileserver-gl:latest
```

check on localhost:8080 with street style ty