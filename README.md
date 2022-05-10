# Instructions d'installation

- Construction du conteneur :
```
docker build -t debian-lamp .
```
- Lancer le service :
```
docker run -p 8000:80 -p 5000:3306 debian-lamp
```
