# template-site
Personal GitHub Pages site template built with Astro + TypeScript. Your repositories, profile README, and links are fetched at build time using the GitHub API.

Making it yours: clone the repo, edit `src/config.ts`, push. That's the whole setup.

## Configuring
In `src/config.ts` you can configure everything needed to make it tailored to you.
You can:
- Set your username to make it fetch your github projects + readme on build.
- Set your socials to display.

## Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

