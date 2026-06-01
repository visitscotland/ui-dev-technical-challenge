# VisitScotland guidance
This is a technical challenge for candidates for the UI Developer role at VisitScotland. Please fork or clone this template to use as a starter project for your work as some shortcuts and tools have already been set up to assist with the challenge. See below for instructions on setting up and running the Nuxt element of the project.<br>

Please spend a maximum of 3 hours on this challenge and be prepared to share and discuss your solution in your interview. Your code should be available on a public Github repository for review after the interview.

## The Brief
Using Vue 3 and VisitScotland’s component library, create a grid or carousel of cards showing different cities and towns in Scotland. Each card should have the same layout and information on it and include an option to add the item to a favourites list. <br><br>
Below this section, display users’ favourited items when they click on any item. There should also be an option to remove any of these items from the favourites section. It is anticipated that this will only persist until the page is refreshed or the window/tab is closed.<br><br>
You may use hard-coded mock data, no API integration is required. 
Please consider accessibility, responsiveness, and semantic HTML in your solution.

## Useful links and advice
-	VisitScotland component library Github repo: [visitscotland/vs-component-library](https://github.com/visitscotland/vs-component-library)
-	VisitScotland component library npm package name: @visitscotland/component-library
-	VisitScotland component library Storybook docs: [https://visitscotland.github.io/vs-component-library/?path=/docs/introduction--docs](https://visitscotland.github.io/vs-component-library/?path=/docs/introduction--docs)
-	Pinea store documentation: [https://pinia.vuejs.org/](https://pinia.vuejs.org/)
-	Our design system includes additional internal guidance covering content, accessibility, and usage recommendations. This documentation is not currently publicly available, so for the purposes of this exercise please use the components based on the information available in Storybook.
-	Whilst we acknowledge that the use of AI coding agents is commonplace in all modern development teams, we encourage applicants to create as much code themselves as possible. This will be beneficial in presenting your solution and answering follow up questions during the interview.  
    
<br>
<br>


# Nuxt Minimal Starter

Look at the [Nuxt documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm dev

# yarn
yarn dev

# bun
bun run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm build

# yarn
yarn build

# bun
bun run build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm preview

# yarn
yarn preview

# bun
bun run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
