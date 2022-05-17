## O passo a passo   de como rodar os testes

1° abrir o terminal e instalar O npm que  é o Gerenciador de Pacotes do Node "npm install" ou "yarn install"  vai depender do seu gerenciador.

2° Vai instalar também o mocha com com o seguinte comando no terminal npm install --save-dev mocha.
O Mocha é um framework de testes unitários simples e bastante prático. 

3° Vai instalar também o chai com com o seguinte comando no terminal npm install chai.
Torna os testes muito mais fáceis, oferecendo muitas asserções que você pode executar em seu código. 

4° Rode npm run  test
ou
5° acesse package.json e rode o script na seta depurar
->Depurar
  "scripts": {
    "test": "mocha --timeout 2000 --exit"
  },

