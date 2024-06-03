# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/main/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.


--- 
## The Steps I Followed ...

❯ npm create cloudflare@latest llsc-app -- --framework=svelte
Need to install the following packages:
create-cloudflare@2.21.4
Ok to proceed? (y) y


> npx
> create-cloudflare llsc-app --framework=svelte


using create-cloudflare version 2.21.4

╭ Create an application with Cloudflare Step 1 of 3
│
├ In which directory do you want to create your application?
│ dir ./llsc-app
│
├ What type of application do you want to create?
│ type Website or web app
│
├ Which development framework do you want to use?
│ framework Svelte
│
├ Continue with Svelte via `npx create-svelte@6.1.2 llsc-app`
│

Need to install the following packages:
create-svelte@6.1.2
Ok to proceed? (y)


create-svelte version 6.1.2

┌  Welcome to SvelteKit!
│
◇  Which Svelte app template?
│  SvelteKit demo app
│
◇  Add type checking with TypeScript?
│  Yes, using TypeScript syntax
│
◇  Select additional options (use arrow keys/space bar)
│  Add ESLint for code linting, Add Prettier for code formatting, Add Playwright for browser testing, Add Vitest for unit testing
│
└  Your project is ready!

✔ Typescript
Inside Svelte components, use <script lang="ts">

✔ ESLint
https://github.com/sveltejs/eslint-plugin-svelte

✔ Prettier
https://prettier.io/docs/en/options.html
https://github.com/sveltejs/prettier-plugin-svelte#options

✔ Playwright
https://playwright.dev

✔ Vitest
https://vitest.dev

Install community-maintained integrations:
https://github.com/svelte-add/svelte-add

Next steps:
1: cd llsc-app
2: npm install
3: git init && git add -A && git commit -m "Initial commit" (optional)
4: npm run dev -- --open

To close the dev server, hit Ctrl-C

Stuck? Visit us at https://svelte.dev/chat

├ Copying template files
│ files copied to project directory
│
├ Installing dependencies
│ installed via `npm install`
│
╰ Application created

╭ Configuring your application for Cloudflare Step 2 of 3
│
├ Installing wrangler A command line tool for building Cloudflare Workers
│ installed via `npm install wrangler --save-dev`
│
├ Installing @cloudflare/workers-types
│ installed via npm
│
├ Adding latest types to `tsconfig.json`
│ added @cloudflare/workers-types/2023-07-01
│
├ Retrieving current workerd compatibility date
│ compatibility date 2024-05-29
│
├ Adding the Cloudflare Pages adapter
│ installed @sveltejs/adapter-cloudflare
│
├ Changing adapter in svelte.config.js
│
├ Updating global type definitions in app.d.ts
│
├ Adding Wrangler files to the .gitignore file
│ updated .gitignore file
│
├ Updating `package.json` scripts
│ updated `package.json`
│
├ Do you want to use git for version control?
│ yes git
│
├ Initializing git repo
│ initialized git
│
├ Committing new files
│ git commit
│
╰ Application configured

╭ Deploy with Cloudflare Step 3 of 3
│
├ Do you want to deploy your application?
│ yes deploy via `npm run deploy`
│
├ npx wrangler whoami
│  ⛅️ wrangler 3.58.0
-------------------
Getting User settings...

✘ [ERROR] Not logged in.


🪵  Logs were written to "/Users/ortons/.wrangler/logs/wrangler-2024-06-03_11-18-24_790.log"

│
├ Logging into Cloudflare checking authentication status
│ not logged in
│
├ Logging into Cloudflare This will open a browser window
│ allowed via `wrangler login`
│
├ Selecting Cloudflare account retrieving accounts
│ account Sam.orton@gmail.com's Account
│
├ Creating Pages project
│ created via `npx wrangler pages project create llsc-app --production-branch main`
│
├ Verifying Pages project
│ verified project is ready for deployment
│
├ Deploying your application
│ deployed via `npm run deploy`
│
├  SUCCESS  View your deployed application at https://llsc-app.pages.dev
│
│ Navigate to the new directory cd llsc-app
│ Run the development server npm run dev
│ Preview your application npm run preview
│ Deploy your application npm run deploy
│ Read the documentation https://developers.cloudflare.com/pages
│ Stuck? Join us at https://discord.cloudflare.com
│
├ Waiting for DNS to propagate
│ DNS propagation complete.
│
├ Waiting for deployment to become available
│ deployment is ready at: https://llsc-app.pages.dev
│
├ Opening browser
│
╰ See you again soon!

❯ webstorm .
❯ nslokup llsc-app.pages
zsh: command not found: nslokup
❯ nslookup llsc-app.pages
Server:		172.23.128.197
Address:	172.23.128.197#53

** server can't find llsc-app.pages: NXDOMAIN

