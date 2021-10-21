
Para poder trabajar con este proyecto usted deberá instalar los requerimientos:

    pip install -r requirements.txt

Haga sus cambios en el archivo [docs/index.md](https://github.com/iKonoChat/changelog-ikonochat/blob/main/docs/index.md)

Vea sus cambios en su local utilizando:

     mkdocs serve
Cuando termine la edición y quiera subir los cambios haga:

Para construir el proyecto:

    mkdocs build

Subalos al repositorio:

    git add -A

    git commit -m "Comente sus cambios"

    git push

Despliegue el proyecto:

    mkdocs gh-deploy

**Nota:** Puede revisar la carpeta [help](https://github.com/iKonoChat/changelog-ikonochat/tree/main/help), aquí encontrara un PDF con ejemplos, tambien puede encontrar ejemplos en [mkdocs-material](https://squidfunk.github.io/mkdocs-material/)