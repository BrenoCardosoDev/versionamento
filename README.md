# Versionamento com Git e GitHub[^3]

## Definições
  * Versionamento: Gerenciamento de versões de algo (Ex.: código, script, documento etc.).
  * Git: Sistema de controle de versões distribuído.
  * GitHub: Plataforma de hospedagem de código-fonte e arquivos que utiliza o Git como base.

## Objetivos
  * Controlar o histórico das versões;
  * Recuperar uma versão específica;
  * Organizar, controlar e assegurar versões de algo.

## Termos básicos
  * Repositório: onde armazena os arquivos.
  * Repositório local: quando armazena na máquina local.
  * Repositório remoto: quando armazena na plataforma em nuvem.
  * Commit: cópia instantânea da versão atual.
  * Hash: identificador do commit.
  * Branch: ramificação do projeto.
  * Origin: nome padrão do repositório remoto que está vinculado ao repositório local.

## Download do Git
  * Windows: https://git-scm.com/download/win

    _Obs.: Na instalação, deixe as opções "Git Bash Here" e “Git GUI Here” marcadas, em "Select Components"._
  * Linux: https://git-scm.com/download/linux
  * MacOS: https://git-scm.com/download/mac

## Configurando o Git
``` Python 
git config --list
```
``` Python 
git config --global user.name "Nome Sobrenome"
```
``` Python
git config --global user.email seuemail@email.com
```
``` Python
git config --global init.defaultBranch main
```

## Repositório Git

### Criando repositório local
``` Python
git init
```

### Conectando o repositório local com o repositório remoto
```
git remote add origin https://github.com/username/nome-do-repositorio.git
```

### Clonando repositório remoto
``` Python
git clone https://github.com/username/nome-do-repositorio
```

