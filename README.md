# dash.acmcsuf.com

## Developing

This project uses NodeJS. Install the latest LTS version [here](https://nodejs.org/en/download).  

Install deps with `npm i`.  

Start dev server:

```sh
npm run dev

# or start the server and open the app in a new browser tab
npm run dev --open
```

## Building and Previewing

To create a production version of your app:

```sh
npm run build
```

You can now preview the production build:

```sh
npm run preview
```

> Using the preview after making changes is important because vite uses the NodeJS runtime but the app uses the Workers runtime in production.

