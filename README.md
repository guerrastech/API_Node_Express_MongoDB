# Projeto Node.js Express e MongoDB

Este é um projeto simples que visa aprimorar meu aprendizado na area de criação de API'S utilizando-se do Node.js Express comm interação com o MongoDB.Este projeto fornece as opções de CRUD(CREATE, RELEASE , UPDATE , DELETE),para gerenciar livros.

## Funcionalidades Principais:

- Cadastro de Livros: Adicione facilmente novos livros à sua lista, incluindo título, autor, gênero e data de leitura.
- Visualização da Lista: Veja todos os livros que você já leu..
- Busca Avançada: Encontre livros específicos em sua lista com rapidez e facilidade.
- Exclua Livros: Exclua os livros que ja não lhe entereçam mais.

## Como Usar:

1. **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/meu-leitor-de-livros.git

2. **Instale as Dependências:**
    npm install

3. **Configure o MongoDB:**
    Certifique-se de ter o MongoDB instalado e configurado corretamente atualizando a URL no arquivo index.js.
    
4. **Inicie o Servidor:**
    npm start

5. **Uso:**
    Após iniciar o servidor, você pode usar ferramentas como Postman ou Insomnia para interagir com os endpoints da API. Aqui estão alguns exemplos de solicitações:
    - Para mostrar todos os livros: GET http://localhost:3000/api/Livros
    - Para mostrar um livros: GET http://localhost:3000/api/Livros/:id
    - Para criar um novo livros: POST http://localhost:3000/api/Livros {"title" : "xxxx", "author" : "xx", "lancamento" : "xx", "sinopse" : "xx", "img_url" : "xx" }
    - Para atualizar um livros: PUT http://localhost:3000/api/Livros/:id {"title" : "xxxx", "author" : "xx", "lancamento" : "xx", "sinopse" : "xx", "img_url" : "xx" }
    - Para excluir um livros: DELETE http://localhost:3000/api/Livros/:id


## Autor:
[https://github.com/guerrastech](Gabriel Guerra)

## Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.