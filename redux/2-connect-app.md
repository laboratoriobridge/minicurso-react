# 2 - Conectando a aplicação com o store

[![Edit 2 - Conectando a aplicação com o store](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/k3k2z4rnjr)

- connect
- mapStateToProps
- mapDispatchToProps

## Exercício 

1. Criar uma função chamada mapStateToProps que retorne um objeto contendo um atributo items. Esse atributo conterá os items armazenados no state da aplicação e que serão inseridos na tabela;
2. Criar uma função chamada mapDispatchToProps que retorne um objeto contendo como atributo uma função adicionarItem. A função adicionarItem deve receber por parâmetro o item a ser adicionado e deve disparar uma action;
A action disparada deve ser a ADD_ITEM que deverá atualizar o state da aplicação com o item inserido.;
3. Passar ambas as funções criadas para o connect;
4. Instanciar o componente Table passando a ele uma prop items que deverá receber os items do state;
5. Testar a aplicação.


## Referências

- http://redux.js.org/docs/basics/Actions.html
- http://redux.js.org/docs/basics/Reducers.html
- http://redux.js.org/docs/basics/Store.html
- https://github.com/reactjs/react-redux
