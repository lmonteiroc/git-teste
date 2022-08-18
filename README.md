# git-teste

Para realizar o compartilhamento dos arquivos pelo git realizar os seguintes passos

---Primeiro criar um repositório vazio no github, esse repositório gerará um link que vai receber seus arquivos salvos na
pasta do seu computador.

--Segundo instalar o git em sua máquina.

1- selecionar a pasta que será enviada ao gihub com o botão direito e clicar em git bash.

2- digitar o comando git init, Isso criará alguns arquivos próprios do git, entre eles o mais
importante é o gitignore, pois nele está tudo o que se deve ignorar ao realizar o commit. 

3- digitar git status, isso mostrará os arquivos que serão commitados, nessa etapa é possivel escolher quais arquivos serão 
enviados

4- digitar git add . Esse comando fará com que todos os arquivos fiquem prontos para o Github, por isso ele é indispensável. 
É importante observar que usei o git add . porque quero adicionar todos os arquivos do projeto, mas caso você queira adicionar
apenas algum arquivo específico, basta usar git add <nome_do_arquivo>.

5- git commit -m "meu primeiro commit" entre as "" pode se escrever o que preferir para identifacar seu commit

6- git branch -M main para criar a branch main, que é a principal branch do repositório

7- git remote add origin <link_para_o_seu_repositorio> o link que é add aqui  é o link criado no repositório vazio mencionado 
no item primeiro

8- git push -u origin main  para enviar o projeto 
FIM
