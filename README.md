    npm install typescript -D

    npx tsc --init

*
    Dentro do tsconfig.json

    target - "es2016" *Geralmente esse ja vem configurado

    outdir - aqui é colocada a pasta onde sera transpilado o codigo de typescript para javascript

    rootdir - Aqui é onde fica o codigo de distribuição

    sourceMap - Deixar como true isso vai ajudar a debugar o codigo

    npx tsc - vai buildar o projeto


*  
     Outra forma de executar o codigo typescript no terminal 

    npm i -D sucrase

    npx sucrase-node src/index.ts

*
    Configurações para executar o typescript mais rapidamente, utilizando o sucrase dentro do code runner, dentro da pasta .vscode

    Comando tsc --watch, monitora em tempo real tudo que está sendo feito no typescript e compila imediamente para javascript

            tsc --watch
