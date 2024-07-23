## Kolab - Desafio Técnico Frontend

### Objetivo

Construir um feed de posts utilizando React e Typescript.
Utilizar a api [https://jsonplaceholder.typicode.com/guide/](https://jsonplaceholder.typicode.com/guide/) para buscar os usuários, posts e comentários. 

### Funcionalidades Requeridas

1. **Feed de Posts**
   
   A home page da aplicação deve listar posts dos usuários em um feed, contendo:
     - Conteúdo do post
     - Autor do post
     - Comentários do post (a relação entre comentários e usuários pode ser aleatorizada, já que a API não fornece essa informação).
    - Deve ser possível criar, editar ou remover um comentário de um post

2. **Posts de um usuário**

   Clicar em um usuário deve levar a uma página que mostra os posts do usuário

3. **Gerenciamento de posts**

   O usuário deve conseguir cadastrar novos posts. Ele também deve conseguir editar e remover estes posts.

4. **Perfil**

   Deve existir uma página para visualizar e editar os dados do usuário atual.
	   - Não precisa implementar um mecanismo de autenticação. Pode assumir que já temos um usuário autenticado ao acessar a aplicação.

### Critérios de Avaliação

1. **Funcionalidade**
   
   A aplicação atende a todos os requisitos descritos acima.

2. **Código**
   
   Clareza, organização, boas práticas e performance da aplicação.

4. **Usabilidade**
   
   Acessibilidade, facilidade de uso e experiência do usuário.

5. **Responsividade**

   A aplicação deve funcionar em diferentes tamanhos de tela


### Bônus

Caso você tenha feito as funcionalidades requisitadas acima, já está bom, de verdade... Mas se quiser ir além, sinta-se a vontade para demostrar seu conhecimento ou aprender!

- Adicionar imagens aos posts.
- Adicionar avatar aos usuários.
- Busca de usuários por nome.
- Permitir que o usuário selecione e remova vários posts de uma só vez.
- Testes automatizados (unitários e/ou end-to-end).
- Gerenciamento de erros.
- Storybook.
- Localização (i18n).

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
- O prazo para realizar o desafio é de uma semana. Caso surja algum imprevisto e precise de mais tempo, por favor, nos avise.

Queremos incentivá-lo a enviar o teste mesmo que não esteja completo. O que mais valorizamos é a sua abordagem ao problema, o seu processo de pensamento e a qualidade do trabalho que você conseguiu completar. Isso nos dará uma excelente visão das suas habilidades e do seu potencial.

Estamos ansiosos para ver o seu trabalho e conhecer mais sobre sua forma de resolver problemas.
