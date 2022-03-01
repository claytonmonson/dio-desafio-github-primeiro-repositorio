# Git/Hub


## Links úteis

[Download Git](https://git-scm.com/downloads)
[Documentação] (https://git-scm.com/doc)

## Comandos básicos

- git init
Comando que inicia um repositório git dentro de uma pasta. A partir do comando, tudo que acontece na pasta passa a ser gerenciado pelo git.

- git config —global user.name xxxxx e git config —global user.email “xxxxx@gmail.com”
Comandos para configuração inicial do git. Ao usar global, a configuração vale para todo o repositório

- git add *
Acrescenta os arquivos na lista do próximo commit do repositório

- git commit -m "primeiro commit"
Cria o commit incluindo a mensagem entre aspas

- git add remote origin xxxxxx
Adiciona o repositório a origem no github. Estabelece o vínculo entre o repositório local e o remoto. No caso, o repositório local recebeu o alias "origin"

- git remote -v
Traz a lista de repositórios relacionados

- git push origin master
Coloca no repositório remoto o conteúdo do repositório local

- git pull origin master
Copia do repositório remoto para o local