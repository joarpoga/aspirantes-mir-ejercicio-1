pwd
mkdir ejercicios
cd ejercicios
code .
git config --global user.email joarpoga@gmail.com
git init .
git add .
git commit -m "Version Inicial"
git add .
git commit -m "Agrega solución primer ejercicio"
git branch -M main
git remote add origin https://github.com/joarpoga/aspirantes-mir-ejercicio-1.git
git push -u origin main
