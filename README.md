# intro-git

## Andamentos do curso de git

Para baixar um repositório disponível online:
-Copiar o link do repositório
-No domínio local desejado abrir o VSCode ou o terminal e utilizar o comando:
--git https... #irá baixar a pasta

Para criar um repositório localmente:
-No domínio local desejado abrir o VSCode ou o terminal e utilizar o comando
--git init #irá transformar essa pasta em um repositório git

## Modificando arquivos

Arquivos modificados serão marcados como M: Modified
-Para verificar o status do arquivo:
--git status

-Para transferir o arquivo modificado para a área de Stage
--git add 'nome_arquivo'

-Para verificar o que foi modificado em um arquivo
--git diff 'nome_arquivo'

-Para realizar um commit dos arquivos em staged
--git commit -m "descrição sucinta"

## Controle

-Para verificar todos os commits que já foram feitos
--git log

-Para retornar o arquivo à forma como estava antes das modificações
--git restore 'nome_arquivo'

## Conexão com repositório remoto

-git remote

-Para enviar para o diretório remoto
--git push origin master/main

-Para atualizar o arquivo com as mudanças efetuadas remotamente
-- git pull #Cuidado com esse comando, pois ele fará um merge com seu arquivo local

## Trabalhando com Branschs

-Para criar uma nova branch
--git branch 'nome_nova_branch'

-Para trocar para outra branch
--git checkout 'nome da branch que quer ir' #No caso do VScode ele informa a branch atual no canto inferior esquerdo

