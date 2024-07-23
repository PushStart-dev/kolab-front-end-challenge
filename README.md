## Kolab - Desafio Técnico Frontend

### Objetivo

Construir um feed de posts utilizando React e Typescript.
Utilizar a api [https://jsonplaceholder.typicode.com/guide/](https://jsonplaceholder.typicode.com/guide/) para listar usuários, posts e comentários. 

### Funcionalidades Requeridas

1. **Feed de Posts**
   
   A home page da aplicação deve listar posts dos usuários em um feed, contendo:
     - Conteúdo do post
     - Autor do post
     - Comentários do post (a relação entre comentários e usuários pode ser aleatorizada, já que a API não fornece essa informação).
    - Deve ser possível criar, editar ou remover um comentário de um post

2. **Posts de um usuário**

   Clicar em um usuário deve levar a uma página que mostra os posts do usuário

3. **Criação de posts**

   Deve haver uma forma na aplicação de criar, editar e remover os posts feitos por mim

4. **Perfil**

   Deve existir uma página para visualizar e editar os dados do usuário atual.
	   - Não precisa fazer um mecanismo de autenticação. Pode assumir que o usuário já temos um usuário autenticado ao acessar a aplicação.
	   -  

5. **Gerenciamento de Posts**

   Deve ser possível criar, editar e excluir posts.

### Critérios de Avaliação

1. **Funcionalidade**
   
   A aplicação atende a todos os requisitos descritos acima.

2. **Código**
   
   Clareza, organização, boas práticas e performance da aplicação.

4. **Usabilidade**
   
   Facilidade de uso e experiência do usuário.

5. **Responsividade**

   A aplicação deve funcionar em diferentes tamanhos de tela


### Bônus

- Adicionar imagens aos posts
- Adicionar avatar aos usuários
- Implementar busca de usuários por nome
- Testes automatizados (unitários e/ou end-to-end).
- Gerenciamento de erros
- Storybook
- Implementar localização (i18n)

### Observações

- Como não possuímos API para criação, edição e remoção dos posts, essas alterações podem ser persistidas apenas em um estado local. (Não é necessário persistir as alterações caso a página seja recarregada)

### Restrições

- A aplicação deve ser um SPA (Single Page Application)
- Utilizar React e Typescript

   Fora isso, o desenvolvedor tem liberdade para utilizar bibliotecas e frameworks adicionais. Caso esteja em dúvida ou não possua uma preferência, a stack que utilizamos hoje consiste predominantemente em:
   - React Router
   - ChakraUI
   - Tanstack Query

### Entrega

- O desafio pode ser compartilhado como um repositório no GitHub ou enviado em um arquivo compactado.
- Inclua um arquivo README com instruções de como rodar a aplicação.
