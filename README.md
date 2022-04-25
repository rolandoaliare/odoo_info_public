# Información sobre Odoo.
Repositorio para dejar accesible info sobre odoo. En un futuro se verá si es necesario hacerlo privado y/o pasarlo a una cuenta *Organización*

## Descarga y ejecución

Todos estos ejemplos utilizan el release de prueba v0.0.1-no-estable el cual contiene un comprimido de un repositorio con el/los scripts. Destro de ese comprimido (tar) se genera una estructura de directorios <nombre repo>-<tag-release> en nuestro caso el repo se llama odoo_info_public y el tag del release es v0.0.1-no-estable por lo que la estructura sería

 ```
 /odoo_info_public-0.0.1-no-estable
     |
     +--README.md
     +--script_instalacion_odoo.sh
 ``` 
1. Descargar release:
    
    ```bash
    wget https://github.com/rolandoaliare/odoo_info_public/archive/refs/tags/v0.0.1-no-estable.tar.gz
    ```
2. Extraer archivos:
```
tar -xf v0.0.1-no-estable.tar.gz 
```

3. Hacer ejecutable el script:
```
cd odoo_info_public-0.0.1-no-estable
chmod a+x script_instalacion_odoo.sh
```

4. Ejecutar y armarse de paciencia:
```
./script_instalacion_odoo.sh
```

*todo*: agregar otra info a este repositorio.
