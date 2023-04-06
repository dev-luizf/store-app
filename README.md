# Store App

Este projeto foi desenvolvido durante um desafio técnico, o objeto era desenvolver um projeto fullstack de uma loja com funcionalidades como listagem de produtos, página de detalhes do produto, filtros de busca e carrinho de compras.

O código do projeto está dividido em duas partes principais: o front-end e o back-end. Cada parte foi separada em um repositório específico para facilitar o desenvolvimento e a manutenção do código. O repositório do front-end pode ser acessado em [https://github.com/dev-luizf/store-ui](https://github.com/dev-luizf/store-ui), enquanto o repositório do back-end pode ser acessado em [https://github.com/dev-luizf/store-api](https://github.com/dev-luizf/store-api).

Dessa forma, cada equipe responsável pode trabalhar em sua parte do projeto de forma independente, realizando as implementações e correções necessárias sem afetar o trabalho da outra equipe. Além disso, essa divisão também permite que o processo de integração e deploy seja mais simples e rápido, pois cada parte pode ser testada e implantada separadamente.

## Tecnologias utilizadas

- [Nest.js](https://nestjs.com/) - Framework para desenvolvimento de aplicações em Node.js.
-  [Mongoose](https://mongoosejs.com/) - ODM para bancos de dados MongoDB.
- [Jest](https://jestjs.io/) - Biblioteca de testes em JavaScript.
- [Docker](https://www.docker.com/) - Plataforma para desenvolvimento, envio e execução de aplicações.
- [Swagger](https://swagger.io/) - Ferramenta para documentação de APIs.
- [Joi](https://joi.dev/) - Biblioteca para validação de dados.
-   [Vite](https://vitejs.dev/) - Build tool para projetos em JavaScript.
-   [Material UI](https://material-ui.com/) - Biblioteca de componentes para o React com base no Material Design da Google.
-   [TailwindCSS](https://tailwindcss.com/) - Framework de CSS utilitário para criação rápida de layouts.
-   [Axios](https://axios-http.com/) - Biblioteca para realizar requisições HTTP em JavaScript.
-   [React Router Dom](https://reactrouter.com/web/guides/quick-start) - Biblioteca para roteamento de aplicações React.

## Deploy

O deploy do projeto foi feito em duas etapas. O front-end foi hospedado na plataforma Vercel e está disponível em [https://store-ui.vercel.app/](https://store-ui.vercel.app/). Já o back-end foi hospedado na plataforma Railway e está disponível em [https://product-manager.up.railway.app/](https://product-manager.up.railway.app/). Ambas as plataformas oferecem uma maneira fácil e rápida de realizar o deploy de aplicações na nuvem.

## Contextualizando o backend

A API desenvolvida para este projeto conta com diversas funcionalidades importantes para garantir sua qualidade e eficiência. Entre elas, destacam-se os testes unitários, que foram desenvolvidos utilizando a biblioteca Jest integrada ao framework Nest. Esses testes têm como objetivo verificar o comportamento do código em diversas situações, garantindo que ele funcione corretamente e evitando problemas no futuro.

Além disso, a aplicação foi dockerizada, o que torna mais fácil sua distribuição e implementação em diferentes ambientes. Essa abordagem também ajuda a garantir a consistência e segurança da aplicação, já que o ambiente de produção é isolado do sistema operacional host.

Por fim, a backend também conta com uma documentação completa utilizando a ferramenta Swagger. Essa documentação facilita a compreensão das rotas, parâmetros e respostas da API, permitindo que desenvolvedores e usuários possam utilizá-la de forma eficiente e correta. Com isso, é possível reduzir erros e aumentar a qualidade do serviço oferecido.

## Contextualizando o frontend

O front-end deste projeto foi desenvolvido principalmente com a ajuda do framework CSS Tailwind. A escolha por essa tecnologia se deve ao fato de que ela oferece diversas classes prontas para estilização, o que torna o processo de desenvolvimento mais rápido e eficiente.

O foco principal do desenvolvimento foi simplicidade e responsividade. Para isso, foram utilizadas técnicas de design e layout que permitem a criação de uma interface fácil de usar, com visual limpo e organizado. Além disso, a aplicação foi desenvolvida de forma responsiva, ou seja, se adapta automaticamente a diferentes tamanhos de tela, proporcionando uma boa experiência de usuário tanto em desktops quanto em dispositivos móveis.

Com a ajuda do Tailwind e do foco em simplicidade e responsividade, foi possível criar uma interface intuitiva e agradável para os usuários, facilitando a navegação e a interação com os produtos e funcionalidades da loja virtual.
