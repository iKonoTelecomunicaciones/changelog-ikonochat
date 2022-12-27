## Pasos para actualizar el changelog

- Crear (o ingresar al) entorno virtual:
```bash
    mkvirtualenv changelog
    workon changelog
```

- Instalar los requerimientos:
```bash
    pip install -r requirements.txt
```

- Hacer los cambios requeridos en [docs/index.md](https://github.com/iKonoChat/changelog-ikonochat/blob/main/docs/index.md) y en
```bash
    vim docs/index.md
    vim docs/changelog.md
```

- Ver los cambios locales:
```bash
     mkdocs serve
```

- Construir el proyecto:
```bash
    mkdocs build
```

- Subir cambios al repositorio:
```bash
    git commit -am "Comente sus cambios"
    git push origin main
```

- Desplegar el proyecto:
```bash
    mkdocs gh-deploy
```

- Verificar que no se haya borrado el dominio yendo a la siguiente ruta dentro del repositorio del changelog en Github:
```
    Settings -> Pages -> Custom domain -> https://changelog.ikono.net.co
```

**Nota:** Puedes revisar la carpeta [help](https://github.com/iKonoChat/changelog-ikonochat/tree/main/help), aquí encontrarás un PDF con ejemplos. También puedes encontrar ejemplos en [mkdocs-material](https://squidfunk.github.io/mkdocs-material/)