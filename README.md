# Redis

## Intro

Redis est une base‑de‑données clé‑valeur en mémoire, open‑source et optimisée pour des opérations ultra‑rapides (cache, broker de messages et stockage léger).

Ce dépôt contient des slides d'introduction et un mini‑TP pour se familiariser avec Redis.

[Slides PDF](./redis_slides.pdf)

## Tuto E-commerce

Tutoriel pour prendre en main Redis. Pour cela, nous utiliserons un notebook Jupyter. Pour simplifier l'installation, nous utiliserons Docker et Docker Compose.

Lancement des services avec Docker Compose:

```bash
docker compose up
```

Cette commande lance **Redis** sur le port `6379` et **Jupyter Lab** sur le port `8888`. La suite se passe dans le notebook Jupyter `redis_tutorial.ipynb`.

Attention !! : Il faut s'assure que le kernel Python du Notebook soit celui lancé par Docker (sur vscode ou intellIJ)
Ou sinon utilisez le front-end jupyter : http://localhost:8888/lab/tree/work/redis_tutorial.ipynb
