# Servidor Web Con Flask      
## Aplicación de Contactos
### Usando python 2.7 y virtualenv

Para correr el servidor gcloud uso el comando:
´$ dev_appserver.py .´

Restarting command:
  $ dev_appserver.py .

API server at: http://localhost:40589
module "default" running at: http://localhost:8080
admin server at: http://localhost:8000

Luego vamos a la direccion https://console.cloud.google.com/appengine/start?project=[nombredelproyecto]

* Seleccionamos el lenguaje y esperamos a que esté listo app engine
* Nos autenticamos en Google
´$ gcloud auth login
Your browser has been opened to visit:
´
* Para hacer deploy ejecutamos:
´
$gcloud app deploy --project [id-project]
´