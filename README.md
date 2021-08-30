# projeto-node2ap

### Iniciar um projeto node no gitHub

Criar um repositório (private ou public)
Escolher a tecnologia (.gitignore), caso disponível
Escolher a opção README.md

### Clonar o projeto para o computador local

Escolher a pasta correspondente aos seus projetos
Escolher um editor eficiente (VsCode, Atom, SublimeText, NetBeans, WebStorm ...)

Tendo acesso ao prompt de comando 

->     git clone  "endereço do projeto no git hub"

### Iniciar o arquivo de configuração package.json

->     npm init -y

### instalação de dependencias e manipulação git "NA ESCOLA"
    ### antes de instalar qualquer dependencia (basta 1 vez)

    npm set strict-ssl false
    npm config set registry https://registry.npmjs.org/

    ### antes de enviar para o GitHub(basta 1 vez)

    git config --global http.sslVerify false


### Instalação de dependencias

Sempre pesquisar a tecnologia no site que contém a documentação oficial
exemplo (npm, yarn )
Exemplo:

->     npm install express
->     yarn add express

Obs:  A pasta node_modules contém todas as tecnologias (dependencias) de terceiros

### Desinstalando uma dependencia

Não excluir qualquer pasta dentro de node_modules

-> npm uninstall express     (por exemplo)

### Instalação como devdependencies
( São tecnologias utilizadas apenas durante o desenvolvimento do projeto em específico )
npm install nodemon -D     (por exemplo)

### Iniciando tecnologias ou scripts utilizando atalhos
No package.json

"scripts": {
    "morango": "nodemon server.js"
  }

No prompt vc executa:
npm run morango

### Token de autenticação 

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









