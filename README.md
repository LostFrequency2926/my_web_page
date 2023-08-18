# my_web_page
Manejo de Git

#create sshkey
ssh-keygen -t rsa -b 4096 -C "dafemure.180@gmail.com"
$ eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
$ cat ~/.ssh/id_rsa.pub

#Clonar repo
git clone git@github.com:tu_usuario/my_web_page.git

#Creacion de la nueva branch
git checkout -b new_features

#Primer commit

luego de crear el aboutme.html

git add aboutme.html
git commit -m "Agregado archivo aboutme.html con contenido de aboutme.html"
