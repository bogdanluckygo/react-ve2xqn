
## Architecture

The project uses `styled-components` to provide component styling and has a custom build-in theme.

All the data is fetched over `GraphQL` and is centralized on the `Gatsby` configuration or through `Markdown` contents.

Static files that will reside at the site root, such as the search engine verification files, remain inside the `static` folder.

```
├── src
│   ├── components
│   ├── content
│   ├── images
│   ├── pages
│   └── themes
└── static
```

## Usage

Use [`yarn`](https://classic.yarnpkg.com/en/docs/install) as the package manager.

Install the dependencies:

```
yarn install
```

Format your code when needed:

```
yarn format
```

Start the development server using:

```
yarn start
```

## Copyright

**This is a public repository in order to others see how it is built. This is not intended to be a theme or copied directly.**

Copyright © 2020 Gabriel Giordano.
All Rights Reserved.
