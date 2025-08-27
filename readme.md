# Comandos Git  
Neste arquivo será apresentados os comandos git para uso futuro

## No primeiro uso em um computador
Para que o GIT avise e saiba quem fez as alterações é necessário configurar o usuário
nas configurações globais do git.

```bash

git config --global user.name "nome"
git config --global user.email "e-mail"

```

## Explicação de cada comando do git:
Dentro da pasta atual, com o "git init" você cria um repositório Git, permitindo versionar os arquivos daquele diretório.

Com o code "./comandos.md" você abre ou cria o arquivo comandos.md no VS Code, pronto para edição.

Usando "git status" você verifica o estado dos arquivos, vendo quais foram modificados ou estão prontos para commit.

Com o "git add" você coloca arquivos na área de staging, preparando-os para serem salvos no histórico.

Com o "git commit -m "Msg" você registra as alterações no histórico do repositório, deixando uma mensagem que descreve o que foi feito.


PULL baixa todas as atualizações que o repositório tem no Github que não está no seu pc.
````bash
git pull
````
