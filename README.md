# Desafio 4 - Conceitos de React Native
O objetivo do desafio é completar a aplicação para treinar os conhecimentos aprendidos sobre React Native.

## Sobre
Deve-se completar a aplicação para comunicar com a api do desafio de Node.js, que permita listar e curtir repositórios.

### Funcionalidades da aplicação

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na sua API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.

### Específicação dos testes

- **`should add a like to the like counter of the repository`**: Para que esse teste passe, sua aplicação deve permitir ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.

## Tecnologia
Este projeto foi desenvolvido utilizando as seguintes tecnologias:

- [React Native](https://reactnative.dev/)
- [Jest](https://jestjs.io/)

## Instalação e Execução
1. Faça a instalações dos pacotes executando o comando: 
```bash 
yarn
```

2. Execute os testes com o Jest utilizando o comando: 
```bash
yarn test
```

## Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/AleixoGJunior/desafio-conceitos-react-native/blob/master/LICENSE) para mais detalhes.


