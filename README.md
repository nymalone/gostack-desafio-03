![Screen Shot 2020-06-24 at 14 40 26](https://user-images.githubusercontent.com/54912285/85605620-b59af580-b628-11ea-9c7a-f318a42dbba3.png)
<h1 align="center">
  🚀 Conceitos ReactJS 🚀
</h1>
  
#### If you need support with the content, go to my [Notion notes](https://www.notion.so/S01-Front-end-com-ReactJS-74930914ada4478c99da7d733795e90a)

## 🚀 Desafio 02

O objetivo deste desafio é colocar em prática os principais conceitos de ReactJS. 

##  🤓 Conceitos importantes
### Componentes

Conceito que deu vida ao react

Dividir pedaços da aplicação em componentes! Conjunto isolado de html, css, js que consegue ser **reaproveitado** quantas vezes quisermos dentro da aplicação.

Tudo dentro do React é um compenent. 

- **JSX →** HTML dentro do Javascript (Javascript XML)

### Propriedades

Informações que podem ser passadas de um componente para outro.

### Estado

O estado de um componente React tem uma função muito simples e específica. Ele é uma propriedade do componente onde colocamos dados que, quando mudados, devem causar uma nova renderização.

### Imutabilidade

Conceito para garantir performance. Ser imutável quer dizer o seguinte: não podemos mutar variáveis, alterar o seu formato (adicionar, deletar...) de maneira direta, nós precisamos sempre reacriar aquela informação com as informações que queremos. 
É esse conceito que levamos para o estado, pois não conseguimos alterar da maneira tradicional como era feito no javascript antigamente, apenas conseguimos alterar com o método useState.

## Funcionalidades da aplicação

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista com o campo **title** de todos os repositórios que estão cadastrados na sua API.

- **`Adicionar um repositório a sua API`**: Deve ser capaz de adicionar um novo item na sua API através de um botão com o texto **Adicionar** e, após a criação, deve ser capaz de exibir o nome dele após o cadastro.

- **`Remover um repositório da sua API`**: Para cada item da sua lista, deve possuir um botão com o texto **Remover** que, ao clicar, irá chamar uma função para remover esse item da lista do seu frontend e da sua API.

## Específicação dos testes

Para esse desafio temos os seguintes testes:

- **`should be able to add new repository`**: Para que esse teste passe, sua aplicação deve permitir que um repositório seja adicionado ao seu backend e listado no seu frontend dentro de uma `LI`.

- **`should be able to remove repository`**: Para que esse teste passe, sua aplicação deve permitir que ao clicar no botão de remover que vai estar dentro da `LI` do repositório adicionado, o item seja removido da listagem.
***

<h4 align="center">
    Made with :coffee: and 💜 by <a href="https://www.linkedin.com/in/nykollemalone/" target="_blank">Nykolle Malone</a>
</h4>

