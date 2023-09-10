# FastAPI Website notes

FASTAPI est un framework python permettant de créer des API.
Toutefois, on peut l'utiliser aussi comme framework d'appli web.

## Lancer notre première instance fastapi avec uvicorn

On peut lancer fastapi directement depuis le code python avec la commande uvicorn
```
# on crée une instance de fastapi => fastapi.FastAPI() dans la variable 'app'
# puis on passe "app" à uvicorn
# main.py:

uvicorn.run(app)
```

Toutefois en production, on ne fait pas comme ça.

Il faut lancer uvicorn à l'extérieur du code

Par exemple dans le shell:

```dotnetcli
uvicorn main:app
`````

## Dynamic Template

Le code de cette section se trouvera dans le répertoire "chap4-dynamic-template"

### render basic HTML