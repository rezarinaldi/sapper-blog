# 🧩 Sapper blog example

Example markdown-style blog using Sapper.

## Links

- DEV article
  - [Create a Blog With Markdown Sapper by joshnuss](https://dev.to/joshnuss)
- YouTube screencast:
  - [Svelte Videos](https://www.youtube.com/channel/UCbrjw7dgB90XozlKUnJibug)

## Getting started

Clone the repo

```
npx degit joshnuss/sample-blog my-blog
```

### Running the project

Install dependencies and run the project in development mode with:

```bash
cd my-blog
npm install # or yarn
npm run dev
```

Open up [localhost:3000](http://localhost:3000) and start clicking around.

Consult [sapper.svelte.dev](https://sapper.svelte.dev) for help getting started.

## Structure

Posts are stored in the `posts` folder and pages are in the `src/routes` folder

## Production mode and deployment

To start a production version of your app, run `npm run build && npm start`. This will disable live reloading, and activate the appropriate bundler plugins.

You can deploy your application to any environment that supports Node 10 or above. As an example, to deploy to [Vercel Now](https://vercel.com) when using `sapper export`, run these commands:

```bash
npm install -g vercel
vercel
```

## Source

[![sample-blog](https://github-readme-stats.vercel.app/api/pin?username=joshnuss&repo=blog-template&title_color=fff&icon_color=f9f9f9&text_color=f9f9f9&bg_color=159497)](https://github.com/joshnuss/blog-template)
