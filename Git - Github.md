# Git / Github

## Git Bash

### Comandos básicos

- SHA1 ➡️ modelo de encriptação utilizado pelo git, importante para controle de versões de código

- mkdir ➡️ comando para criar uma nova pasta

- ls ➡️ listar arquivos disponiveis na pasta

- ls -a ➡️ listar arquivos ocultos na pasta

- cd ➡️ navegar entre pastas

- cd .. ➡️ voltasr para a pasta anterior

- CTRL + L ➡️ limpar a tela

- mv ➡️ mover arquivos entre pastas "./nome-da-pasta"



### Criar arquivos

- git init ➡️ Iniciar repositório no git

- git config --global user.email "xxx@xxx.com" ➡️ adicionar o email do autor do código

- git config --globaluser.name "xxxxxxx" ➡️ adicionar o nome do autor do código
  
  - Importante lembrar que tanto o e-mail quanto o nome do autor devem ser os mesmos já cadastrados no github

- git config --global --unset user.email ➡️ alterar email do autor do código

- git config --global --unset user.name➡️ alterar nome do autor do código

- git add * ➡️ mover arquivo untracked para staged "colocar arquivos alterados prontos para o commit"

- git commit -m "comentário a respeito do commit" ➡️ commitar arquivos

- git status ➡️ verificar se arquivos já foram commitados

- git config --list ➡️ ver configurações aplicadas ao git



### Comandos para enviar arquivos  - git ➡️ github

- git remote add _origin link_ ➡️ enviar repositórios ao github
  
  - origin ➡️ alias / variavel aplicada por padrão
  
  - link ➡️ link do repositório já criado no github

- git remote -v ➡️ lista de repositórios remotos associados ao git

- git push origin _master / main_ ➡️ "empurar" arquivos do git para o github

- git pull origin _master / main_ ➡️ substituir arquivos do computador por arquivos que estão armazenados no github

- git clone _link_ ➡️ Baixar repositórios do github
  
  - link ➡️ link do repositório já criado no github
