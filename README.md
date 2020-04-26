<h1 align="center">
  <img src=".assets/logo-gostack.svg" atl="GoStack Bootcamp" />
</h1>

<h3 align="center">
  Desafio 3: Conceitos do ReactJS
</h3>

<p align="center">
  Desafio desenvolvido durante o <a href="https://rocketseat.com.br/gostack">Bootcamp GoStack</a> da Rocketseat.
  <br />
  <br />
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#instalação-e-execução">Instalação e execução</a>
</p>

## Tecnologias

- [ReactJS](https://reactjs.org/)
- [Axios](https://github.com/axios/axios)
- [Axios Mock-Adapter](https://github.com/ctimmerm/axios-mock-adapter)

## Sobre o desafio

Nesse desafio, eu criei uma aplicação para teinar o que eu aprendi até agora no ReactJS!

É uma continuação do desenvolvimento da aplicação que irá armazenar repositórios do meu portfólio, que eu já desenvolvi o backend no último desafio utilizando o Node.js.

### Funcionalidades da aplicação

- **`Listar os repositórios da API`**: Deve ser capaz de criar uma lista com o campo **title** de todos os repositórios que estão cadastrados na API.

- **`Adicionar um repositório a API`**: Deve ser capaz de adicionar um novo item na API através de um botão com o texto **Adicionar** e, após a criação, deve exibir o nome dele na lista.

- **`Remover um repositório da API`**: Para cada item da lista, deve possuir um botão com o texto **Remover** que, ao clicar, irá chamar uma função para remover esse item da lista do frontend e da API.

### Específicação dos testes

Para esse desafio temos os seguintes testes:

- **`should be able to add new repository`**: Para que esse teste passe, a aplicação deve permitir que um repositório seja adicionado ao backend e listado no frontend dentro de uma `li`.

- **`should be able to remove repository`**: Para que esse teste passe, a aplicação deve permitir que ao clicar no botão de remover que vai estar dentro da `li` do repositório adicionado, o item seja removido da listagem.

## Instalação e execução

```bash
# Clone esse repositório
$ git clone https://github.com/adeonir/gostack-conceitos-reactjs conceitos-reactjs

# Entre no diretório
$ cd conceitos-reactjs

# Installe as dependências
$ yarn

# Rode a aplicação
$ yarn start

# Rode os testes
$ yarn test
```

## Licença

Esse projeto está sob a licença MIT.

---

Made with ♥️ by Adeonir Kohl