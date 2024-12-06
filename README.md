# Zurich R User Group - New Website

## Installation

To get started, you can clone this repository and install the dependencies.

### 1. Navigate to your project folder & clone the repository
```bash
git clone https://github.com/minnaheim/zrug_trial_website.git
```

### 2. Install Dependencies & start the development server

```bash
cd zrug_trial_website # navigate to the project folder
npm install
npm run dev
```

## Project Structure

Inside the folder `zrug_trial_website`, you'll see the following folders and files:

```
/
├── public/
│   └── ...
├── src/
│   ├── components/
│   │   └── ...
│   ├── layouts/
│   │   └── ...
│   └── pages/
│       └── ...
└── package.json
```

The different webpages, i.e. the main page can be found under `src/pages/`. Currently only the pages `about.astro`, `blog.astro` and `host.astro`. The `index.astro` just combines all components which can be found on the main page. The layout of the pages can be found under `src/layouts/`. The components used in the pages can be found under `src/components/`.
