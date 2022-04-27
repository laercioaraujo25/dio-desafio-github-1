# GIT
## CMD

- cd: entrar nas pastas
- cd / : vai para pasta raiz do SO no caso C:
- del deleta arquivos não pastas
- rmdir (nome) /S /Q - remove pasta e todo o conteúdo dentro
- dir: listar os diretórios na pasta atual
  mkdir criar pasta
- Gerar chave ssh para integrar github
  ssh-keygen -t ed25519 -C laercioaraujo25@gmail.com
  /c/Users/LAERCIO PC/.ssh

- pwd mostra o caminho 

Comando para ver a chave: cat id_ed25519.pub Chave Publica GIT

- eval $(ssh-agent -s)
- ssh-add id_ed25519 Habilitar chave privada

## Iniciando Versionamento

- git init
- git config --global user.email "laercioaraujo25@gmail.com"
- git config --global user.name Laercio
- git config --global --sunset user.name (Remove a configuração referente)

## Iniciando um projeto

- git status (mostra as alerações feitas)
- git add * (aprovando alterações)
- git commit -m "commit inicial" (mandando para o git as alterações)
- git push origin master  (Mandando alterações para o Github) 
- git push origin master --force (Forçado)
- git pull origin master (Baixar versão mais recente)