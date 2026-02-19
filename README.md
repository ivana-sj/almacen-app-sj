# 1. Instalar Git desde https://git-scm.com

# 2. En tu computadora, abrir terminal en la carpeta de tu proyecto
cd "C:\Users\iorel\OneDrive\Desktop\power-b-ia\almacen.html"

# 3. Renombrar tu archivo a index.html
mv almacen.html index.html

# 4. Inicializar git
git init

# 5. Agregar archivo
git add index.html

# 6. Hacer commit (guardar cambios)
git commit -m "Primera versión de la app"

# 7. Conectar con GitHub (reemplaza ivana-sj)
git remote add origin https://github.com/ivana-sj/almacen.git

# 8. Subir archivo
git push -u origin main
