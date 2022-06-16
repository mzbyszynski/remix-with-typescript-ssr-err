# Remix example

## To Reproduce Rendering Error:

1. Start App in a docker container:
    ```sh
    docker build -t remix-with-typescript-ssr-err .
    docker run -it -p 3000 remix-with-typescript-ssr-err
    ```
1. Open in browser: http://localhost:3000/

1. You should see an error like this in the dev console:

    > react-dom.development.js:86 Warning: Prop `className` did not match. Server: "MuiTypography-root MuiTypography-h4 MuiTypography-gutterBottom css-gtvj52" Client: "MuiTypography-root MuiTypography-h4 MuiTypography-gutterBottom css-1vw6mcs-MuiTypography-root"

----------
## How to use

Download the example [or clone the repo](https://github.com/mui/material-ui):

<!-- #default-branch-switch -->

```sh
curl https://codeload.github.com/mui/material-ui/tar.gz/master | tar -xz --strip=2  material-ui-master/examples/remix-with-typescript
cd remix-with-typescript
```

Install it and run:

```sh
npm install
npm run dev
```

or:

<!-- #default-branch-switch -->

[![Edit on StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/mui/material-ui/tree/master/examples/remix-with-typescript)

[![Edit on CodeSandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/mui/material-ui/tree/master/examples/remix-with-typescript)

## The idea behind the example

The project uses [Remix](https://remix.run/), which is a full stack web framework that lets you focus on the user interface and work back through web fundamentals to deliver a fast, slick, and resilient user experience.
It includes `@mui/material` and its peer dependencies, including `emotion`, the default style engine in MUI v5.
If you prefer, you can [use styled-components instead](https://mui.com/material-ui/guides/interoperability/#styled-components).

## What's next?

<!-- #default-branch-switch -->

You now have a working example project.
You can head back to the documentation, continuing browsing it from the [templates](https://mui.com/material-ui/getting-started/templates/) section.
