# Información sobre Odoo.
Repositorio para dejar accesible info sobre odoo. En un futuro se verá si es necesario hacerlo privado y/o pasarlo a una cuenta *Organización*

## Descarga y ejecución

Todos estos ejemplos utilizan el release de prueba v0.0.2-no-estable el cual contiene comprimido un repositorio con el/los scripts. Dentro de este archivo tar.gz se genera una estructura de directorios <nombre repo>-<tag-release> en nuestro caso el repo se llama odoo_info_public y el tag del release es v0.0.2-no-estable por lo que la estructura será:

 ```
 /odoo_info_public-0.0.2-no-estable
     |
     +--README.md
     +--script_instalacion_odoo.sh
     +--script_instalacion_odoo_pro.sh
 ``` 
1. Descargar release:
    
```
wget https://github.com/rolandoaliare/odoo_info_public/archive/refs/tags/v0.0.2-no-estable.tar.gz
```
2. Extraer archivos:
```
tar -xf v0.0.2-no-estable.tar.gz 
```

3. Hacer ejecutable el script:
```
cd odoo_info_public-0.0.2-no-estable
chmod a+x script_instalacion_odoo_pro.sh
```

4. Ejecutar y armarse de paciencia:
```
./script_instalacion_odoo_pro.sh
```

5. Copiar y resguardar la información de la instalación que se muestra al final. Ejemplo:
 ```
-----------------------------------------------------------
Done! The Odoo server is up and running. Specifications:
Port: 8069
User service: odoo
Configuraton file location: /etc/odoo-server.conf
Logfile location: /var/log/odoo
User PostgreSQL: odoo
Code location: odoo
Addons folder: odoo/odoo-server/addons/
Password superadmin (database): vqYdiJuAMZsnxob0
Start Odoo service: sudo service odoo-server start
Stop Odoo service: sudo service odoo-server stop
Restart Odoo service: sudo service odoo-server restart
Nginx configuration file: /etc/nginx/sites-available/_
-----------------------------------------------------------
```
 
 *todo*: agregar otra info a este repositorio.
