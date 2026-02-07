# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src
│   ├── assets
│   │   └── astro.svg
│   ├── components
│   │   └── Welcome.astro
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 🏗 Website Structure

### Core Pages
* **Home (`/`)**: Hero section, service highlights, and primary Call to Action (CTA).
* **About (`/about`)**: Company history, licensing, insurance info, and team bios.
* **Services (`/services`)**: Detailed breakdown of offerings (e.g., Residential, Commercial, Renovation).
* **Contact (`/contact`)**: Quote request form and service area map.

### Portfolio (Content Collections)
The portfolio is managed via **Content Collections** located in `src/content/projects/`. This allows for easy management of project galleries using Markdown or JSON.
* **Project Gallery (`/projects`)**: A grid view of completed works.
* **Project Details (`/projects/[slug]`)**: Individual pages for deep dives into specific builds, featuring "Before & After" imagery.