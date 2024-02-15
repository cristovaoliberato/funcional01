# Implementando Funções para Processamento de Dados com Programação Funcional e Estruturada em JS

Este é um projeto [Node.js](http://nodejs.org), que usa JavaScript no backeend. 
O projeto fornece a estrutura básica para você implementar a soma do dobro de um conjunto de números pares
em duas implementações diferentes: uma funcional e uma estruturada (procedural).

O projeto está estruturado da seguinte forma:

- [src/math.js](src/math.js): fornece a estrutura das 2 funções descritas acima, que você precisa implementar.
  Você **NÃO** deve alterar nomes de funções nem parâmetros neste arquivo.
  Deve única e excluisivamente inserir o seu código dentro do protótipo das funções fornecidas no arquivo,
  não alterando nada mais no arquivo.
- [src/index.js](src/index.js): arquivo principal para chamar as funções existentes.
  Você pode alterar o arquivo como desejar, alterando os valores do vetor, chamando
  as funções múltiplas vezes com vetores distintos, ou qualquer outra coisa que queira.
- [test/math-test.js](test/math-test.js): arquivo com testes unitários para verificar se suas implementações estão minimamente funcionando como esperado. Você não precisa se preocupar com o código de tal arquivo.

## Pré-requisitos para rodar o projeto

Você precisa da uma versão atual do Node.js (20+).
No linux, basta instalar com:

```bash
sudo apt update
sudo apt install nodejs npm -y
```

No windows, pode baixar o instalador em http://nodejs.org.

## Rodando o projeto

Para rodar o projeto, basta abrir um terminal na pasta raiz e digitar:

```bash
npm start
```

Assim, o arquivo index.js será executado e você poderá ver o resultado à medida que for implementando as funções em [src/math.js](src/math.js).

## Testando sua implementação das funções

Para verificar se suas implementações da soma do dobro dos números pares está funcionando minimamente, execute:

```bash
npm test
```

Se não aparecer nenhum erro nem mensagem em vermelho, seu código tá pronto.
