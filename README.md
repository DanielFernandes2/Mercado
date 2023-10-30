# Carrinho/Mercado

# Para rodar esse projeto faça esse passo a passo

1. Abra o Visual Studio Code

2. No terminal cole esse codigo 
```
npm i
```
3. Depois da instalação cole esse codigo
```
npx expo start
```
4. Depois clique na letra W do seu teclado para abrir a versão web do projeto

5. Em outro terminal cole esse codigo
```
npm install -g json-server
```
6. Depois de baixar tudo você ira precisar liberar a pasta para abrir o servidor, cole esse codigo
```
Set-ExecutionPolicy Unrestricted
```
7. Agora é só abrir o servidor da API com esse codigo
```
json-server --watch api.json
```
Nesse ultimo codigo caso você tenha renomeado os arquivos não esqueça de trocar o nome no final do codigo por exemplo  "json-server --watch api.json" em vez de ser api.json você coloca o nome do arquivo no lugar "json-server --watch NOME_DO_ARQUIVO.json"

Para ter seu login é só ir no arquivo api.json e colocar seu email e senha em usuarios

Se você for colocar esse projeto num Vercel por exemplo ele não pegara o login nem os produtos, porque infelizmente a API desse projeto é falsa, não tem um servidor, então só pega quando você rodar pelo Visual Studio Code

Aproveite =D



Projeto feito junto com [leobianor](https://github.com/leobianor).
