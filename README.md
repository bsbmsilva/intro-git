# intro-git

## Andamentos do curso de git

Para baixar um repositório disponível online:
-Copiar o link do repositório
-No domínio local desejado abrir o VSCode ou o terminal e utilizar o comando:
--git https... #irá baixar a pasta

Para subir um repositório criado localmente:
-No domínio local desejado abrir o VSCode ou o terminal e utilizar o comando
--git init #irá transformar essa pasta em um repositório git

## Modificando arquivos

Arquivos modificados serão marcados como M: Modified
-Para verificar o status do arquivo:
--git status

-Para transferir o arquivo modificado para a área de Stage
--git add 'nome_arquivo'

-Para verificar o que foi modificado em um arquivo
--git diff

-Para realizar um commit dos arquivos em staged
--git commit -m "descrição sucinta"