# tuto
comandos:
git init
git branch -M main
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
copy con .gitignore //pones los archivos que no quieres subir
git add .
git commit -m "first commit"
git remote add origin git@github.com:alexadrian32/q.git
git push -u origin main

para hacer una clave privada ssh:
ssh-keygen -t ed25519 -C aasimionesei32@gmail.com
ssh-add ./"clave ssh"

y ya puedes hacer un push

