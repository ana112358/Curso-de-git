# Resumo sobre o git

- Repositório para aprender a utilizar o git e o GitHub. Curso da Udemy com o professor Jamilton Damasceno . 

## O que é controle de versão/fonte?

> Explicar o que é o controle de versão
- É uma prática de rastrear e gerenciar as auterações em um código de um software. Os sistemas de controle de versão são ferramentas que permitem rastrear as auterações no código ao longo do tempo e por desenvolvedores diferentes.

> Explicar para que ele surgiu 
- Com a evolução de softwares que se tornam cada vez mais complexos, os sistemas de versionamento permite que desenvolvedores de diferentes locais, possam acessar e modificar os códigos de um mesmo projeto.

> Explicar com um exemplo prático de uso como o projeto do Facebook
- Além disso, se você tem um projeto grande, tipo o Facebook, que tem inúmeras funcionalidades, podemos criar ramos para desenvolver alguma ideia que temos, como a criação de um chat para o facebook, evitando interrupções de outros desenvolvedores que estão implementando outras funcionalidades e de corromper todo o projeto por erros na criação do chat, por exemplo.

## Tipos de controle de versão
> Explicar os tipos de controle de versão e como ele funcionam
### Centralizado
- É um modelo baseado em cliente-servidor, ou seja, as máquinas da equipe do projeto precisam estar conectadas a um servidor central que contém o sistema de controle de versão com os arquivos versionados do projeto.

- Só possui um repositório que é o que está no servidor

- Apenas um servidor principal tem uma cópia local para cada contriibuidor. Logo, a única forma de comunicação delas é peo servidor principal.

- Caso o sevidor central fique fora do ar, não será possível trabalhar com o seu time ou gerar novas versões . 

![18333fig0102-tn](https://github.com/ana112358/Curso-de-git/assets/130050929/2456af85-2c5c-4ba3-a538-8175a3e0d049)

> Explicar mostrando a ideia da imagem também 

###  Descentralizado/distribuído

- Não depende de um servidor central, isso significa que o desenvolvedor terá um repositório na área de trabalho com toda a base de dados , podendo percorrer outros banches, gerar ou reverter versões do código-fonte, trabalhar em versões de teste etc.

- Devido a essa liverdade do controle descentralizado, é necessário um controle para com os contribuidores, a fim de evitar a quebra da aplicação ou a sua possíve exclusão.
  
![18333fig0103-tn](https://github.com/ana112358/Curso-de-git/assets/130050929/5546a560-a425-4c49-9fb7-dbf80cb5a0c8)

> Eplicar mostrando a ideia da imagem


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
> Explicar que quando se utiliza deste comando é criada uma pasta oculta chamada ".git", que vai  ter as configurações necessárias para o monitoramento do git naquele diretório.

> criar arquivo no boco de notas e salvar no diretório.
 
> utilizar o git status e explicar que ele serve basicamente para saber o estado atual do diretório em relação ao git, como quais arquivos estão sendo trackeados ou quais foram modificados.

> explicar o que é o git add . e o git add <nome do arquivo> : que é quando adicionamos uma ou mais mudanças que será confirmada com o próximo commit feito.

> Expicar o que é o git commit -m "mensagem" : quando salvamos aquela modifição, se não for feito o commit podemos perder todas as modificações que fizemos.

> Aqui podemos falar sobre a brincadeira que fazem sobre nunca esquecer de fazer o commit , um meme por exemplo.

## Comandos do git

### git commit
- O commit registra alterações em um ou mais arquivos  na sua branch.

git commit  -m "Aqui vc coloca a mensagem falando o que foi alterado" 

- Quando fazemos o commit, criamos uma nova versão do código e caso queiramos voltar atrás das modificações é possível, pois o o arquivo está sendo rastreado pelo git.

- Nunca esqueça de commitarrrrrr!!!

### git add

- O git add adiciona uma mudança qualquer, seja ela alterar ou remover um conteúdo de um arquivo local , que terá a sua mudança confirmada através do commit.

### git status 

- Exibe as condições do diretório de trabalho e da área de stanging
- o que é stanging? é onde adicionamento os arquivos para a árvore do git.
- O git status nos permite ver quais alterações foram despreparadas , quais não foram e quais arquivos estão sendo monitorados(tracked) pelo git.


## O que é o Github?
- O GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores e usuários cadastrados contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo. O GitHub é utilizado para gerir projetos, permitindo a colaboração entre uma grande comunidade de desenvolvedores

### O que é a chave SSH
- O secure Shell Protocoll é um protocolo de rede criptográfica para operar serviços de rede com segurança em uma rede não segura.
- Na prática quando vc estiver utiizando a chave, sempre que vc for fazer comandos que transfiram dados entre os repositórios remoto e local, a senha que você criou para sua chave será soicitada.
#### Qual a finalidade da chave SSH?
- Têm a função de criptografar o tráfego entre servidor e cliente. Na prática, isso quer dizer que se alguém resolver espionar esse tráfego, não conseguirá descriptografar os dados de modo apropriado.
  
> Curiosidade :  A ideia do funcionamento da Chave SSH envolve ideias que vemos em teoria dos números. Matemática é útil!!!

> 1. Aqui vamos mostrar na prática a criação de uma chave SSH
> 2. ....
> 3. ....
> 4. ....
 


## Clonando projetos com o git

### Qual a diferença entre subir um projeto e clonar um projeto
#### Clonar o projeto ou parte do projeto
- Esse é o processo que geralmente se faz quando se chega em uma empresa , Criamos uma cópia de parte do projeto ou do projeto inteiro para se trabalhar nele.

##### Comando 
- git clone <link da chave ssh>

#### Subir um projeto 
- Quando criamos o projeto no repositório local/no computador e subimos para o gitHub.

> Passo a passo

>1. Criar um repositório remoto vazio
>2. Passo a passo no doc do github
>3. ...

## Subindo Auterações
- Com o git push (empurrar) você consegue subir alterações do seu computador para o Github.

# Sincronizar projeto com o GitHub 
## Baixando alterações com Git pull
- Com o git pull(puxar) você consgue baixar alterações que podem ter acontecido no projeto, para que você trabalhe com o projeto atualizado.
- Este comando incorpora as alterações de um repositório remoto para o repositório local.


> Hora de mostrar na prática utilizando bloco de notas

> Criar no repositório vazio que criamos um doc coom o nome primeiro_doc

> e escrevemos uma modificação nele, fazemos os commits e o push na prática

> Depois podemos fazer uma modificação direto no github , fazemos git status para ver o estado atual

> Depois fazemos o git pull  


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

> obs.: Quando se entra em uma empresa, geralmente já existe um repositório. Temos que fazer o git clone para criar um repositório local e você fazer as alterações, que quando forem aprovadas, será feito o merge para colocar essas auterações na branch main.

> Antes de mostrar na prática mesmo, acho que seria interessante mostrar pelo simulador do site <https://learngitbranching.js.org/>

> Dar um tempo para o pessoal treinar (10 min)

> Mostrar na prática a criação /  troca de branch / como ver todas as branchs

### O que é pull request(requisição de pull)?
- Uma pull request é uma proposta para mesclar as alterações de um branch em outro. Em uma pull request, os colaboradores podem revisar e discutir o conjunto de alterações proposto antes de integrá-las à base de código principal.

- É a partir da Branch main que fazemos o Pull Request.
- 
## Como proteger uma branch

> Mostrar na prática como funciona a proteção de uma branch através de uma conta criada e um novo repositório

> como convidar colaboradores e as opções que aparecem na tela
> 
### Code Review (Revisão de Código) - Como é feito?
- É um processo essencial no desenvolvimento de software, onde um ou mais colegas de equipe revisam o código-fonte escrito por outro desenvolvedor que mandou o pull request.

  > Nessa parte precisamos ter duas contas logadas para simular o code review e o outro o desenvolvedor que vai fazer um pull request.
  
  > Precisamos mostrar como funciona os comentários e a solicitação de revisão de código.
  
  > Por fim, a aprovação e o marge pelo code review


  ## O que É o Fork?

  - Quando pegamos projetos já existentes e praticamente garfamos 





