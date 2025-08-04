# The Practiced Leader
Website for The Practiced Leader.

## Demo
You can view a [live demo](https://ericyork.github.io/tpl-site) of the website.

## To use
1. Download or clone the repository
2. In the terminal: `npm install` to download the dependencies
3. Then: `npm run dev` to build and start the dev server 
4. Visit [http://localhost:8080](http://localhost:8080) to view the site
5. To stop the server (in order to change configurations or recompile tailwind, for example) just press `control + C`, then `npm run dev` again to rebuild.

## Notes
This is a fairly standard implementation with only a few customizations. Below are some important notes.
+ Files are read from `/src` and built to `/dist`
+ The `src/assets` directory is passed through to `dist`
+ Tailwind input file is `/src/styles/index.css` and outputs to `/dist/styles/index.css`
+ Templating is done with nunjucks `.njk` by default
+ Base template is `/src/_includes/layouts/default.njk`
+ Content pages are in markdown `.md` (with native HTML)
+ Google fonts have been set up, but commented out
+ Nav and footer components
+ Theme toggle