# Iniciar proyecto de git
git init

# Preparar archivos que se convertirán en commit
git add . 

## El punto es para agregar todo los archivos modificados

# Crear commit con su mensaje
git commit -m "Aquí va el mensaje"

# Agregar remoto "Sola la primera vez"
git remote add origin https://github.com/elissearias/santander-front.git

# Enviar commits al servidor 
git push origin -u origin master
