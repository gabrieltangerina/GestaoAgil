Comandos referentes a aula de Gestão Ágil sobre Git

Para fazer um commit:

git init<br> 
git config user.nome 'Gabriel'<br>
git config user.nome 'gabriel@example.com'<br>
git add .<br>
git commit -m 'Mensagem do commit'<br>
git branch -M main<br>
git remote add origin (url do repositorio)<br>
git push -u origin main<br>

Exemplo de commit:

mkdir GestaoAgil<br>
cd GestaoAgil<br>
git init<br>
git config user.nome "Gabriel"<br>
git config user.email "gabriel@example.com"<br>
vim arquivo.txt<br>
git add .<br>
git commit -m 'Criacao do arquivo.txt'<br>
git branch -M main<br>
git remote add origin (url do repositorio)<br>
git push -u origin main<br>
