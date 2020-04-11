<h3 align="center">
  Desafio: Conceitos do ReactJS
</h3>

## Sobre o desafio

Nesse desafio, eu criei uma aplicação para teinar o que eu aprendi até agora no ReactJS!

É uma continuação do desenvolvimento da aplicação que irá armazenar repositórios do meu portfólio, que eu já desenvolvi o backend no último desafio utilizando o Node.js.

### Funcionalidades da aplicação

- **`Listar os repositórios da API`**: Deve ser capaz de criar uma lista com o campo **title** de todos os repositórios que estão cadastrados na API.

- **`Adicionar um repositório a API`**: Deve ser capaz de adicionar um novo item na API através de um botão com o texto **Adicionar** e, após a criação, deve ser capaz de exibir o nome dele após o cadastro.

- **`Remover um repositório da API`**: Para cada item da lista, deve possuir um botão com o texto **Remover** que, ao clicar, irá chamar uma função para remover esse item da lista do frontend e da API.

### Específicação dos testes

Para esse desafio temos os seguintes testes:

- **`should be able to add new repository`**: Para que esse teste passe, a aplicação deve permitir que um repositório seja adicionado ao backend e listado no frontend dentro de uma `li`.

- **`should be able to remove repository`**: Para que esse teste passe, a aplicação deve permitir que ao clicar no botão de remover que vai estar dentro da `li` do repositório adicionado, o item seja removido da listagem.