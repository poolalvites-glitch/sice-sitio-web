
# sice-sitio-web

Repositorio listo para subir a GitHub (Pool Alvites).

Instrucciones para publicar:
1. Crea un repo vacío en GitHub llamado `sice-sitio-web`.
2. Descomprime este ZIP y en la carpeta del proyecto ejecuta:

   git init
   git branch -M main
   git remote add origin https://github.com/poolalvites-glitch/sice-sitio-web.git
   git add .
   git commit -m "Versión inicial del sitio SICE SAC"
   git push -u origin main

3. En Netlify: New site from Git -> conecta GitHub -> selecciona repo
   Build command: npm run build
   Publish directory: dist
   Site name: sicesac
