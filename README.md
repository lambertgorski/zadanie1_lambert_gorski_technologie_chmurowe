# zadanie1_lambert_gorski_technologie_chmurowe
Zadanie1 z technologi chmurowych

Polecenia:
a. zbudowanie obrazu
```bash 
docker build -t zadanie1:1.0  . 
```

b. uruchomienie kontenera
```bash docker run -d --name zadanie1 -p 8000:8000 -e API_KEY="OpenWeatherAPI_KEY" zadanie1:1.0
```

c. wyśiwetlenie logów
```bash 
docker logs zadanie1
```
d. sprawdzenie ilości warstw i ich rozmiaru
```bash
docker history zadanie1
```