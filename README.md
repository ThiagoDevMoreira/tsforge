# Fullstack Multiplatafoma

## Typescript

| **Camada**                           | **Tecnologia**                                  | **Descrição**                                                                                                                                         |
| ------------------------------------ | ----------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Frontend Web**                     | React, Chakra UI                                | **React** para construção de interfaces web com **Chakra UI** como biblioteca de componentes minimalistas, proporcionando rapidez e simplicidade.     |
| **Frontend Desktop**                 | Tauri                                           | Utiliza **Tauri** (leve, com WebView nativo) para adaptar o frontend para aplicações desktop, aproveitando o desempenho e baixo consumo de memória.   |
| **Frontend Mobile**                  | React Native                                    | Framework que permite usar componentes React para desenvolver aplicações móveis nativas (iOS e Android) com alto grau de reutilização de código.      |
| **Gerenciamento de Estado**          | Zustand                                         | Biblioteca leve e minimalista para gerenciamento de estado, adequada para aplicações React que buscam simplicidade e flexibilidade em estados locais. |
| **Sistema de Design e Prototipagem** | Storybook                                       | **Storybook** para desenvolvimento isolado de componentes e prototipagem de UI, com documentação visual e testes de usabilidade.                      |
| **Backend API**                      | NestJS com GraphQL                              | Framework backend modular com **NestJS**, usando **GraphQL** para fornecer uma API flexível e fortemente tipada para consumo pelo frontend.           |
| **Banco de Dados e ORM**             | Prisma ORM, PostgreSQL, SQLite                  | **Prisma ORM** para mapeamento de banco de dados com TypeScript, usando **PostgreSQL** para produção e **SQLite** para armazenamento local/offline.   |
| **Sincronização de Dados**           | Apollo Client                                   | **Apollo Client** com GraphQL para gerenciamento de cache e sincronização de dados entre o frontend e a API, com suporte a operação offline.          |
| **Autenticação e Sessões**           | Auth0                                           | **Auth0** para autenticação segura e gerenciamento de sessões, oferecendo integração com login social e suporte multiplataforma.                      |
| **Comunicação em Tempo Real**        | Socket.IO                                       | **Socket.IO** para comunicação bidirecional em tempo real, facilitando a troca de dados em tempo real entre clientes e o backend.                    |
| **Testes Unitários e de Integração** | Jest, React Testing Library                     | Ferramentas para garantir qualidade com **Jest** (testes unitários), **React Testing Library** (testes de componentes) e **Cypress** (testes E2E).    |
| **Formatadores e Linters**           | ESLint e Prettier                               | **ESLint** para linting e **Prettier** para formatação automática, assegurando padrão de código limpo e organizado para todo o projeto.               |
| **Monorepo e Build**                 | Nx                                              | Estrutura **monorepo** robusta e altamente configurável, ideal para projetos grandes e com múltiplas dependências compartilhadas.                     |
| **CI/CD e Deploy**                   | GitHub Actions, Docker, Vercel                  | **GitHub Actions** para CI/CD automatizado, **Docker** para contêineres backend e **Vercel** para deploy do front-end, integrado com Turborepo.       |
| **Documentação da API**              | Stoplight                                       | **Stoplight** para design e documentação colaborativa de APIs, com suporte ao OpenAPI e interface intuitiva para edição e validação em equipe.       |



# Tsforge

✨ Your new, shiny [Nx workspace](https://nx.dev) is almost ready ✨.

Run `npx nx graph` to visually explore what got created. Now, let's get you up to speed!

## Finish your CI setup

[Click here to finish setting up your workspace!](https://cloud.nx.app/connect/lZMkHtjA4A)


## Run tasks

To run tasks with Nx use:

```sh
npx nx <target> <project-name>
```

For example:

```sh
npx nx build myproject
```

These targets are either [inferred automatically](https://nx.dev/concepts/inferred-tasks?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) or defined in the `project.json` or `package.json` files.

[More about running tasks in the docs &raquo;](https://nx.dev/features/run-tasks?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)

## Add new projects

While you could add new projects to your workspace manually, you might want to leverage [Nx plugins](https://nx.dev/concepts/nx-plugins?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) and their [code generation](https://nx.dev/features/generate-code?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) feature.

To install a new plugin you can use the `nx add` command. Here's an example of adding the React plugin:
```sh
npx nx add @nx/react
```

Use the plugin's generator to create new projects. For example, to create a new React app or library:

```sh
# Genenerate an app
npx nx g @nx/react:app demo

# Generate a library
npx nx g @nx/react:lib some-lib
```

You can use `npx nx list` to get a list of installed plugins. Then, run `npx nx list <plugin-name>` to learn about more specific capabilities of a particular plugin. Alternatively, [install Nx Console](https://nx.dev/getting-started/editor-setup?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) to browse plugins and generators in your IDE.

[Learn more about Nx plugins &raquo;](https://nx.dev/concepts/nx-plugins?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) | [Browse the plugin registry &raquo;](https://nx.dev/plugin-registry?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)


[Learn more about Nx on CI](https://nx.dev/ci/intro/ci-with-nx#ready-get-started-with-your-provider?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)

## Install Nx Console

Nx Console is an editor extension that enriches your developer experience. It lets you run tasks, generate code, and improves code autocompletion in your IDE. It is available for VSCode and IntelliJ.

[Install Nx Console &raquo;](https://nx.dev/getting-started/editor-setup?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)

## Useful links

Learn more:

- [Learn about Nx on CI](https://nx.dev/ci/intro/ci-with-nx?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)
- [Releasing Packages with Nx release](https://nx.dev/features/manage-releases?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)
- [What are Nx plugins?](https://nx.dev/concepts/nx-plugins?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)

And join the Nx community:
- [Discord](https://go.nx.dev/community)
- [Follow us on X](https://twitter.com/nxdevtools) or [LinkedIn](https://www.linkedin.com/company/nrwl)
- [Our Youtube channel](https://www.youtube.com/@nxdevtools)
- [Our blog](https://nx.dev/blog?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects)
