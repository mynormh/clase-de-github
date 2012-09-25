clase-de-github
===============

Este es un ejemplo de GitHub para la comunidad de mejorando.la

Una vez instalas GIT, debes configurarlo:

git config --global user.name "Mynor"
git config --global user.mail "xxxx@xxxxx.com"

Generando tu public key:

ssh-keygen

Leyendo tu llave para copiarla a Github:

cat ~/.ssh/id_rsa.pub

Arrancando tu proyecto:

git init

touch README

git add README

git commit -m "tu primer commit"

git push origin master