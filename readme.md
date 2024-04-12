# HACKATHON API
API en php pour gerer les photos et l'authentification

## Fonctionnalité principales
- API RESTFul du portefolio

## Configuration requise
- docker
- git

## Instruction d'installation

### Via docker 

- cloner le dépot : `git clone https://github.com/Vivien-Parsis/hackathon`
- creer un fichier .env dans le répértoire avec comme contenu : `DB_URI={your_db_url}`
- pour le lancer l'api : `docker build -t hackathon . && docker run --rm -p 3000:80 --env-file .env --name hackathon hackathon`

## Adresse

`http://localhost:3000`

## Route

[route disponible](/src/router/router.md)

## Auteur

- [Vivien PARSIS](https://github.com/Vivien-Parsis)
- [Adam MALEK](https://github.com/Beuhnnyto)
- [Adam DAUVE](https://github.com/Karlamilyi)
- [Tanguy MERCIER](https://github.com/MercierTanguy)
- [Aris ABROUS](https://github.com/Zongotripledozo)