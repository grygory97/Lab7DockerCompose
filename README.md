# Lab7DockerCompose

Projekt pozwalajcy stworzy serwer na usludze LAMP

## Sklad projektu
* Apache
* PHP 7.4
* MySQL

### Budowa projektu

Aby zbudowac projekt nalezy wydac polecenie 

```bash
docker-compose build
```
Uruchomienie

```bash
docker-compose up
```
Podgląd działania 

```bash
curl localhost:6666/ 
```

Podgląd html

```bash
curl localhot:6666/index.html
```

### docker-compose-viz

Wizualizacja pliku docker compose 

```bash
docker run --rm -it --name dcv -v $(pwd):/input pmsipilot/docker-compose-viz render -m image docker-compose.yml
```
