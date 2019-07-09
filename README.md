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

1. Modifique seu app anterior para fazer com que, caso a soma de todos os contadores seja maior que `10`, seja emitido um alerta.

## CSS e DOM

- CSS
- Inputs
- Refs / Manipulação de DOM
- Usando os componentes do Bold

Exercício: (TODO) pegar valores de um input e colocar numa lista

## Integrando com APIs

- useEffect
- HTTP Requests

Exercício: (TODO) consumir recursos a partir de uma API JSON pública

## Avançado

- Valores de Forms (final-form, useFormState?)
- Render props / High order components / extração para hooks
- Context API

Exercício: (TODO)

# Dia 2 - GraphQL (Apollo) e frontend do PEC

## GraphQL / Apollo

- Apollo
- GraphiQL PEC
- Configuração do client do Apollo
- Queries
- Mutations

Exercício: (TODO)

## PEC

- Estrutura de arquivos
- Roteamento (com react-router)
- Criando funcionalidades no PEC

Exerício: (TODO)

# Referências / Material de estudo

- Site oficial React: https://facebook.github.io/react/
- Tutorial: Intro to React (https://reactjs.org/tutorial/tutorial.html)
- Curso (Vídeo) - The Beginner's Guide to React: https://egghead.io/courses/the-beginner-s-guide-to-react
