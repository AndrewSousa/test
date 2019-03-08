I'm enjoying it a lot.
Github is amazing!!!

/* COMANDOS GIT */ git config --global user.name "seu nome" git config --global user.email "seu email" git config --list

/* CRIAR UMA PASTA */ mkdir "nome-da-pasta/"

/* ENTRAR NA PASTA */ cd "nome-da-pasta/"

/SAIR DA PASTA/ cd ..

/LIMPAR TELA DE COMANDOS/ clear

/MOSTRAR STATUS ATUAL DO REPOSITÓRIO/ git status

/ADINIONAR ARQUIVOS/ git add

/ADICIONAR ARQUIVOS AO COMMITTED/ git commit -m "NOME PARA IDENTIFICAR A VERSÃO"

/OLHAR ALTERAÇÃO NO ARQUIVO ANTES DE COMITAR/ git diff(NÃO MOSTRARÁ SE JA ESTIVER ADDICIONADO)

/MOSTRAR SOMENTE O NOME DO ARQUIVO QUE FOI MODIFICADO/ git diff --name-only

/VER LOG DO AUTHOR/ git lot/git log --author="nome do autor(com letras maiusculas do jeito que foi configurado)"git shortlog(ver logs curtos)

/MOSTRA DETALHER DAS EDIÇÕES/ git show "codigo da alteração"

/Voutar a estado anterior do arquivo(so funciona antes de comitar)/ git checkout "nomedoarquivo.txt(sem aspas)"

/VOLTAR PARA ESTADO ANTES DE COMITAR, MAS CON TINUA COM ALTERAÇÃO/ git reset --soft "codigo do log anterior da comitação feita"

/VOLTA TUDAS AS ALTERAÇÕES FEITAS DE FORMA DRAMATICA/ git reset --hard "codigo do log"

/INTRODUÇÃO GERAL AO GIT RESET/ git reset --soft(volta ao estado antes de comitar)

git reset --mixed(volta ao estado antes de adicionar o arquivo para ser comitado)

git reset --hard(volta tudo de forma dramatica até o estado antes mesmo da alteração)

/CONEXÃPO REMOTA COM GITHUB/ git remote add origin https://github.com/AndrewSousa/test.git

/VER SE ESTOU CONECTADO REMOTAMENTE/ git remote -v

/ENVIAR ARQUIVOS REMOTAMENTE/ git push -u origin master

/CLONAR E BAIXAR ARQUIVOS DO GITHUB/ git clone https://github.com/AndrewSousa/milligram.git "NOME DA PASTA(SEM ASPAS)"
