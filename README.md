# Dia 1 - React, Typescript e Bold

## Seu primeiro componente React

> A JavaScript library for building user interfaces

- React createElement API
  - Exemplos: https://reactjs.org/
- JSX
- node / webpack
- create-react-app (https://github.com/facebook/create-react-app)
- CodeSandbox (https://codesandbox.io/s/new)
- Props
- React com Typescript
- Render / Render condicional

Exercício:

1. Crie um novo react app no code sandbox (https://codesandbox.io/s/new)
2. Faça seu app renderizar na tela 3 linhas, cada uma contendo o texto "Olá, [nome de uma pessoa qualquer]".
3. Utilize componentes para evitar duplicação de código.
4. Inclua tipos nas props do componentes criado, utilizando typescript
5. Inclua outras props no componente (por exemplo, idade, cidade natal etc) e imprima essas informações
6. Inclua um _render condition_ em seu componente. Sugestão: se a cidade natal da pessoa for "Florianópolis", renderize toda a linha em _bold_ (você pode utilizar a tag HTML `<strong>` para isso)

## Component states

- State
- Class components / Lifecycle methods
- Eventos HTML

Exercício 1:

1. Crie um app em react no code sandbox que renderize três botões contadores
1. O conteúdo (texto) de cada botão é o valor atual de seu contador
1. Cada contador inicia com o valor `0`
1. O contador do botão é incrementado em `1` toda vez que o botão for clicado
1. Inclua uma label ao lado do botão que indique se o seu valor é ímpar ou par

Exercício 2:

1. Modifique seu app anterior para fazer com que, caso a soma de todos os contadores seja maior que `10`, seja emitido um alerta

## CSS e DOM

- CSS
- Inputs
- Refs / Manipulação de DOM

Exercício 1:

1. Estilize a label par/ímpar em verde/azul usando styles/css puro
1. Troque os botões por inputs e a cada alteração de valor, utilize o mesmo label pra indicicar se é par ou ímpar

## Formulários

- Usando os componentes do Bold
- Valores de Forms (`final-form`)

Exercício:

1. Realize o exercício a partir de: https://codesandbox.io/s/bold-with-fields-kdlth
1. Utilizando os componentes do Bold, implemente um formulário com um único campo de texto, um botão de submissão e uma lista inicalmente vazia
1. Ao submeter o formulário, adicione o valor na lista e limpe o campo.

## Integrando com APIs

- useEffect
- HTTP Requests
- Promises
- Async renders

Exercício:

1. Usando a api do [JSONPlaceholder](https://jsonplaceholder.typicode.com/) liste os posts em uma tabela com as colunas: `id`, `userId` e `title`
2. Você pode utilizar o método `fetch` nativo do browser para realizar a requisição

Exerício 2:

1. Crie uma coluna de `actions` e adicione um link de detalhes
1. Ao clicar no link de `detalhes` o usuário deve ser direcionado para uma outra tela de detalhes do post com: `id`, `userId`, `title` e `body`

# Dia 2 - GraphQL (Apollo) e frontend do PEC

## GraphQL / Apollo

- Apollo
- GraphiQL PEC: http://teste.pec.esusab.ufsc.br/graphiql
- Configuração do client do Apollo
- Queries
- Mutations

Exercício:

1. Crie uma aplicação a partir do sandbox: https://codesandbox.io/s/bold-with-apollo-2ig84
1. Liste os CBOs (apenas a primeira página), informando seu nome e se ele está disponível para lotação
1. Implemente a funcionalidade de disponibilizar/indisponibilizar o CBO para lotação através das mutations já existentes

## PEC

- Estrutura de arquivos
- Roteamento (com react-router)

# Referências / Material de estudo

- Site oficial React: https://facebook.github.io/react/
- Tutorial: Intro to React (https://reactjs.org/tutorial/tutorial.html)
- Curso (Vídeo) - The Beginner's Guide to React: https://egghead.io/courses/the-beginner-s-guide-to-react
