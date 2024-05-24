# Resumo sobre o git

- Repositório para aprender a utilizar o git e o GitHub. Curso da Udemy com o professor Jamilton Damasceno . 

## O que é controle de versão/fonte?

- É uma prática de rastrear e gerenciar as auterações em um código de um software. Os sistemas de controle de versão são ferramentas que permitem rastrear as auterações no código ao longo do tempo e por desenvolvedores diferentes.
- Com a evolução de softwares que se tornam cada vez mais complexos, os sistemas de versionamento permite que desenvolvedores de diferentes locais, possam acessar e modificar os códigos de um mesmo projeto.
- Além disso, se você tem um projeto grande, tipo o Facebook, que tem inúmeras funcionalidades, podemos criar ramos para desenvolver alguma ideia que temos, como a criação de um chat para o facebook, evitando interrupções de outros desenvolvedores que estão implementando outras funcionalidades e de corromper todo o projeto por erros na criação do chat, por exemplo.

## Tipos de controle de versão
### Centralizado
- É um modelo baseado em cliente-servidor, ou seja, as máquinas da equipe do projeto precisam estar conectadas a um servidor central que contém o sistema de controle de versão com os arquivos versionados do projeto
-  ![centralizado](https://github.com/ana112358/Curso-de-git/assets/130050929/2648a775-6381-4afe-8654-720a35319ac4)

###  Descentralizado/distribuído
-


## O que é GIT ?

- É uma ferramenta que trabalha com controle de versão.

## Como Trabalhar com o git?

### Vamos entender alguns conceitos 

- Repositório : É onde o código será armazenado

- Branch : São ramificações para criar ramos de desenvolvimento, tipo versões. Nessas ramificações podemos criar diferentes recursos que depois serão mesclados.


## Comandos do git
### git commit

- O commit registra alterações em um ou mais arquivos  na sua branch

git commit  -m "meu primeiro comit com o git" 

### git status 

- Exibe as condições do diretório de trabalho e da área de stanging
- o que é stanging? é onde adicionamento os arquivos para a árvore do git.
- O git status nos permite ver quais alterações foram despreparadas , quais não foram e quais arquivos estão sendo monitorados(tracked) pelos git.

### git push

- Permite que enviemos os commits da nossa banch e repositório git local para o repositório remoto.
- obs.: Antes de fazer o push , temos que verificar se todas as alterações no repositório local foram feitas.

## Trabalhando com branch

### O que é uma branch?
- São ramificações , em que podemos criar vários recursos e depois mescla-los.

### Comandos para trabalhar com branch

#### Criar uma branch
- git branch <nome_branch>


### Saber quais branchs existem
- git branch

### Como trocar de branch
- git checkout <nome_destino>

### Como criar uma branch?
- git -b "nome da branch"


### O que é pull request?
- Uma pull request é uma proposta para mesclar as alterações de um branch em outro. Em uma pull request, os colaboradores podem revisar e discutir o conjunto de alterações proposto antes de integrá-las à base de código principal.
