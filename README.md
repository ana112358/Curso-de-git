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

- É uma ferramenta que trabalha com controle de versão e é a mais utilizada no mundo atualmente.
- Desenpenho: Operações otimizadas para ter alto desempenho . PQQQQ?
- Segurança: Todos os objetos do git são protegidos com criptografia.
- Código Aberto: É um projeto de Código aberto. PQQQ isso é uma vantagem?. Porque pode ser utilizado pelas empresas como um recurso sem depende de nada externo.

## Git e Github são a mesma coisa?
- Não, Github e similares como GitLab e Bitbucket, são provedores que utilizam o git, fornecendo uma interface visual, além de armazenamento na nuvem para os projetos.

## Como Trabalhar com o git?


### Vamos entender alguns conceitos 

- Repositório : É onde o código será armazenado, geralmente é associado a um projeto.
O github e o bitbucket oferecem armazenamento na nuvem.
Dentro do gitHub podemos ter repositórios abertos, onde outras pessoas podem visualizar, como recrutadores e também tem repositórios priivados.

- Branch : São ramificações para criar ramos de desenvolvimento, tipo versões. Nessas ramificações podemos criar diferentes recursos que depois serão mesclados.
![Captura de tela 2024-05-27 123350](https://github.com/ana112358/Curso-de-git/assets/130050929/b3966cc6-ea3d-4512-94be-7b7e014f7c64)
![Captura de tela 2024-05-27 123630](https://github.com/ana112358/Curso-de-git/assets/130050929/2eb608f8-a923-4ca5-8f1f-d1f63471febe)

## Criando meu primeiro Repositório Git
- Abrir o Git bash e ir até dentro da pasta onde está o projeto
- digitar o comando git init para inicializar o git no local dentro da pasta.

## Comandos do git
### git commit

- O commit registra alterações em um ou mais arquivos  na sua branch.

git commit  -m "Aqui vc coloca a mensagem falando o que foi auterado" 
- Quando fazemos o commit, criamos uma nova versão do código e caso queiramos voltar atrás das modificações é possível, pois o o arquivo está sendo rastreado pelo git.

- Nunca esqueça de commitarrrrrr!!!

### git add

- O git add adiciona uma mudança qualquer, seja ela auterar ou remover um conteúdo de um arquivo local , que terá a sua mudança confirmada através do commit.

### git status 

- Exibe as condições do diretório de trabalho e da área de stanging
- o que é stanging? é onde adicionamento os arquivos para a árvore do git.
- O git status nos permite ver quais alterações foram despreparadas , quais não foram e quais arquivos estão sendo monitorados(tracked) pelo git.

### git push

- Permite que enviemos os commits da nossa banch e repositório git local para o repositório remoto.
- obs.: Antes de fazer o push , temos que verificar se todas as alterações no repositório local foram feitas.

#### O que é o Github?
- O GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores e usuários cadastrados contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo. O GitHub é utilizado para gerir projetos, permitindo a colaboração entre uma grande comunidade de desenvolvedores

###### Configurando chave SSH
- O secure Shell Protocoll é um protocolo de rede criptográfica para operar serviços de rede com segurança em uma rede não segura.

- 1. abra o gitbaash
  2. ....
  3. ....
  4. ....
 


## Clonando projetos com o git

### Qual a diferença entre subir um projeto e clonar um projeto
#### Clonar o projeto ou parte do projeto
- Esse é o processo que geralmente se faz quando se chega em uma empresa , clonamos parte do projeto ou o projeto inteiro para se trabalhar nele.
### Comando 
- git clone <link da chave ssh>

#### Subir um projeto 
- Quando criamos o projeto no repositório local/no computador e subimos para o gitHub
### Comando
- Com o git push (empurrar) você consegue subir alterações do seu computador para o Github.

## Baixando alterações com Git pull
- Com o git pull(puxar) você consgue baixar alterações que podem ter acontecido no projeto, para que você trabalhe com o projeto atualizado.
- Este comando incorpora as alterações de um repositório remoto para o repositório local.


## Sincronizar projeto com o GitHub 
.........

## Trabalhando com branch

### O que é uma branch?
- São ramificações , em que podemos criar vários recursos e depois mescla-los.
- É uma boa prática criar funcionalidades diferentes em novas brunchs.


### Comandos para trabalhar com branch

#### Criar uma branch
- git branch <nome_branch>

### Saber quais branchs existem
- git branch

### Como trocar de branch
- git checkout <nome_destino>
- Comando para alternar a branch que está sendo trabalhada.

### Como criar uma branch?
- git checkout -b "nome da branch"

obs.: Quando se entra em uma empresa, geralmente já existe um repositório. Temos que fazer o git clone para criar um repositório local e vocÊ fazer as alterações, que quando for aprovada, será feito o merge para colocar essas auterações na branch main.

### O que é pull request(requisição de pull)?
- Uma pull request é uma proposta para mesclar as alterações de um branch em outro. Em uma pull request, os colaboradores podem revisar e discutir o conjunto de alterações proposto antes de integrá-las à base de código principal.

### Code Review (Revisão de Código)
- É um processo essencial no desenvolvimento de software, onde um ou mais colegas de equipe revisam o código-fonte escrito por outro desenvolvedor que mandou o pull request.