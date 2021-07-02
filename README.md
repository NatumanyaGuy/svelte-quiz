/* CSS HEX */
--black-coffee: #2e1f27ff;
--russet: #854d27ff;
--chocolate-web: #dd7230ff;
--maize-crayola: #f4c95dff;
--green-yellow-crayola: #e7e393ff;

/* CSS HSL */
--black-coffee: hsla(328, 19%, 15%, 1);
--russet: hsla(24, 55%, 34%, 1);
--chocolate-web: hsla(23, 72%, 53%, 1);
--maize-crayola: hsla(43, 87%, 66%, 1);
--green-yellow-crayola: hsla(57, 64%, 74%, 1);

/* SCSS HEX */
$black-coffee: #2e1f27ff;
$russet: #854d27ff;
$chocolate-web: #dd7230ff;
$maize-crayola: #f4c95dff;
$green-yellow-crayola: #e7e393ff;

/* SCSS HSL */
$black-coffee: hsla(328, 19%, 15%, 1);
$russet: hsla(24, 55%, 34%, 1);
$chocolate-web: hsla(23, 72%, 53%, 1);
$maize-crayola: hsla(43, 87%, 66%, 1);
$green-yellow-crayola: hsla(57, 64%, 74%, 1);

/* SCSS RGB */
$black-coffee: rgba(46, 31, 39, 1);
$russet: rgba(133, 77, 39, 1);
$chocolate-web: rgba(221, 114, 48, 1);
$maize-crayola: rgba(244, 201, 93, 1);
$green-yellow-crayola: rgba(231, 227, 147, 1);

/* SCSS Gradient */
$gradient-top: linear-gradient(0deg, #2e1f27ff, #854d27ff, #dd7230ff, #f4c95dff, #e7e393ff);
$gradient-right: linear-gradient(90deg, #2e1f27ff, #854d27ff, #dd7230ff, #f4c95dff, #e7e393ff);
$gradient-bottom: linear-gradient(180deg, #2e1f27ff, #854d27ff, #dd7230ff, #f4c95dff, #e7e393ff);
$gradient-left: linear-gradient(270deg, #2e1f27ff, #854d27ff, #dd7230ff, #f4c95dff, #e7e393ff);
$gradient-top-right: linear-gradient(45deg, #2e1f27ff, #854d27ff, #dd7230ff, #f4c95dff, #e7e393ff);
$gradient-bottom-right: linear-gradient(135deg, #2e1f27ff, #854d27ff, #dd7230ff, #f4c95dff, #e7e393ff);
$gradient-top-left: linear-gradient(225deg, #2e1f27ff, #854d27ff, #dd7230ff, #f4c95dff, #e7e393ff);
$gradient-bottom-left: linear-gradient(315deg, #2e1f27ff, #854d27ff, #dd7230ff, #f4c95dff, #e7e393ff);
$gradient-radial: radial-gradient(#2e1f27ff, #854d27ff, #dd7230ff, #f4c95dff, #e7e393ff);



*Looking for a shareable component template? Go here --> [sveltejs/component-template](https://github.com/sveltejs/component-template)*

---

# svelte app

This is a project template for [Svelte](https://svelte.dev) apps. It lives at https://github.com/sveltejs/template.

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit sveltejs/template svelte-app
cd svelte-app
```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*


## Get started

Install the dependencies...

```bash
cd svelte-app
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

By default, the server will only respond to requests from localhost. To allow connections from other computers, edit the `sirv` commands in package.json to include the option `--host 0.0.0.0`.

If you're using [Visual Studio Code](https://code.visualstudio.com/) we recommend installing the official extension [Svelte for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode). If you are using other editors you may need to install a plugin in order to get syntax highlighting and intellisense.

## Building and running in production mode

To create an optimised version of the app:

```bash
npm run build
```

You can run the newly built app with `npm run start`. This uses [sirv](https://github.com/lukeed/sirv), which is included in your package.json's `dependencies` so that the app will work when you deploy to platforms like [Heroku](https://heroku.com).


## Single-page app mode

By default, sirv will only respond to requests that match files in `public`. This is to maximise compatibility with static fileservers, allowing you to deploy your app anywhere.

If you're building a single-page app (SPA) with multiple routes, sirv needs to be able to respond to requests for *any* path. You can make it so by editing the `"start"` command in package.json:

```js
"start": "sirv public --single"
```

## Using TypeScript

This template comes with a script to set up a TypeScript development environment, you can run it immediately after cloning the template with:

```bash
node scripts/setupTypeScript.js
```

Or remove the script via:

```bash
rm scripts/setupTypeScript.js
```

## Deploying to the web

### With [Vercel](https://vercel.com)

Install `vercel` if you haven't already:

```bash
npm install -g vercel
```

Then, from within your project folder:

```bash
cd public
vercel deploy --name my-project
```

### With [surge](https://surge.sh/)

Install `surge` if you haven't already:

```bash
npm install -g surge
```

Then, from within your project folder:

```bash
npm run build
surge public my-project.surge.sh
```
