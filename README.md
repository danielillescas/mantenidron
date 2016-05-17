Pasos para hacer cualquier cambio:

- Abre la consola y ejecuta (necesitas tener Ruby instalado) para instalar las dependencias:
```
bundle
```

- Accede a [http://localhost:4567](http://localhost:4567) para ver la app

- Para publicar los cambios corre:
```
rake build && rake publish
```

- Luego añádelos al repositorio y sube los cambios:
```
git add .
```
```
git push origin master
```
