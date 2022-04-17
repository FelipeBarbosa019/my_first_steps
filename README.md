# my_first_steps
Exercícios: 

1. Após criado a sua conta no GitHub, crie um repositório remoto público chamado “my_first_steps” e cole o link aqui; 

https://github.com/FelipeBarbosa019/my_first_steps.git

2. Crie um diretório em sua máquina e o vincule ao seu repositório remoto “my_first_steps” utilizando os comandos git necessários para a realização desta tarefa. Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa. 

User@MOBABOX-M13 MINGW64 ~
$ echo "# my_first_steps" >> README.md

User@MOBABOX-M13 MINGW64 ~
$ git init
Initialized empty Git repository in C:/Users/User/.git/

User@MOBABOX-M13 MINGW64 ~ (master)
$ git add README.md
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

User@MOBABOX-M13 MINGW64 ~ (master)
$ git commit -m "meu primeiro commit"
[master (root-commit) 44939d8] meu primeiro commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

User@MOBABOX-M13 MINGW64 ~ (master)
$ git branch -M main

User@MOBABOX-M13 MINGW64 ~ (main)
$ git remote add origin https://github.com/FelipeBarbosa019/my_first_steps.git

User@MOBABOX-M13 MINGW64 ~ (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 236 bytes | 236.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/FelipeBarbosa019/my_first_steps.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.







3. Dentro do diretório em sua máquina, crie um arquivo chamado “ola_mundo.txt”, adicione algum texto da sua preferência e adicione-o ao seu repositório remoto utilizando os comandos git necessários para a realização desta tarefa. Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa. 

User@MOBABOX-M13 MINGW64 ~/Desktop/Projetos GIT (main)
$ git add .

User@MOBABOX-M13 MINGW64 ~/Desktop/Projetos GIT (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   ola_mundo.txt


User@MOBABOX-M13 MINGW64 ~/Desktop/Projetos GIT (main)
$ git commit -m "Inclusão do arquivo txt"
[main d3b4b11] Inclusão do arquivo txt
 1 file changed, 1 insertion(+)
 create mode 100644 ola_mundo.txt

User@MOBABOX-M13 MINGW64 ~/Desktop/Projetos GIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 366 bytes | 366.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/FelipeBarbosa019/my_first_steps
   6ede632..d3b4b11  main -> main



4. Se não existir em seu diretório, adicione ao seu diretório um arquivo com o nome de “.gitignore”. Em seguida, crie um arquivo chamado “serei_ignorado.txt” e adicione algum texto dentro dele. Adicione a instrução ao arquivo “.gitignore” para que as alterações realizadas no arquivo “serei_ignorado.txt” não seja controlado pelo git. Cole aqui o conteúdo que você utilizou no “.gitignore” para realizar esta tarefa. 

Inclui dentro do arquivo .gitignore o conteúdo “serei_ignorado.txt”.

