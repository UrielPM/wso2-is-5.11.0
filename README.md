# Comando Utilizados
1. git init
2. git lfs install
3. git lfs track "NombreArchivo.zip"
4. git add .gitattributes
5. git add 307  DEV-QA.zip o git add .
6. git commit -m "Descripción del Commit"
7. git branch -M main
8. git remote add origin git@github.com:UrielPM/wso2-is-5.11.0.git
9. git push -u origin main

# Para descargar el proyecto
1. Se tiene que clonar el repositorio, porque si le das descargar el zip manda error cuando se descomprime el archivo
2. git lfs clone <URL_del_repositorio.git>

#Nota: 
Para crear la imagen se tiene que comentar la siguiente linea JAVA_HOME=/Library/WSO2/IdentityServer/5.11.0/jdk/jdk-11.0.7+7/Contents/Home
que se encuentra en la ruta bin/wso2server.sh, si no se comenta esta linea mandara error cuando OPC Ejecute la imagen 
