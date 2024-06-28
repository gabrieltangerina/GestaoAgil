Comandos referentes a aula de Gestão Ágil sobre Git

Para fazer um commit:

git init<br> 
git config user.nome 'Gabriel'<br>
git config user.nome 'gabriel@example.com'<br>
git add .<br>
git commit -m 'Mensagem do commit'<br>
git branch -M main
git remote add origin (url do repositorio)
git push -u origin main

Exemplo de commit:

mkdir GestaoAgil
cd GestaoAgil
git init
git config user.nome "Gabriel"
git config user.email "gabriel@example.com"
vim arquivo.txt
git add .
git commit -m 'Criacao do arquivo.txt'
git branch -M main
git remote add origin (url do repositorio)
git push -u origin main
