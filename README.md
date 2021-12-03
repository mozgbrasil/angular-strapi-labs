[checkmark]: https://raw.githubusercontent.com/mozgbrasil/mozgbrasil.github.io/master/assets/images/logos/logo_32_32.png "MOZG"

![valid XHTML][checkmark]

# angular-strapi-labs 👉️

## Contribuição

Caso queira contribuir para melhoria da documentação de um Fork no repositório e envie um pull request ou edite no github

## Requerimentos

- https://www.docker.com/
- https://code.visualstudio.com/
- https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack

## Ambiente

```console
cd <directory>

yarn

yarn create strapi-app backend --quickstart --no-run
cd backend
yarn strapi install graphql
$(npm bin)/strapi dev


```

## Executando local

```
git clone ☝️

cd <directory>

code --new-window .
```

## Executando no container

## Referências

- https://strapi.io/integrations/angular-cms
- https://strapi.io/blog/build-a-blog-with-angular-js-strapi-and-apollo
- https://github.com/strapi/strapi-starter-angular-blog

#

# Strapi Starter Angular Blog

> **Warning :warning:**
>
> This starter relies on the **[strapi/strapi-legacy-blog](https://github.com/strapi/strapi-legacy-blog)** repository, which is deprecated.

Angular starter for creating a blog with Strapi.

This starter allows you to try Strapi with Angular with the example of a simple blog. It is fully customizable and due to the fact that it is open source, fully open to contributions. Do not hesitate to add new features etc ...

You may want to know how to develop such a starter by your own! This starter is actually the result of this [tutorial](https://strapi.io/blog/build-a-blog-with-angular-js-strapi-and-apollo)

![screenshot image](/screenshot.png)

## Features

- 2 Content types: Article, Category
- 2 Created articles
- 3 Created categories
- Permissions set to `true` for article and category
- Responsive design using UIkit

Pages:

- "/" display every articles
- "/article/:id" display one article
- "/category/:id" display articles depending on the category

## Getting started

**Backend**

See full instructions [here](https://github.com/strapi/strapi-legacy-blog)

**Frontend**

```bash
git clone https://github.com/strapi/strapi-starter-angular-blog.git
cd strapi-starter-angular-blog
```

#### Start the frontend server

```bash
# Using yarn
yarn install
yarn develop

# Using npm
npm install
npm run develop
```

Angular server is running here => [http://localhost:4200](http://localhost:4200)

Enjoy this starter!
