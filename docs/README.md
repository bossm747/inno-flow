# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

### Deployment to Vercel

To deploy this website to Vercel, follow these steps:

1. **Sign up for Vercel**: If you don't have a Vercel account, sign up at [vercel.com](https://vercel.com/).

2. **Install Vercel CLI**: Install the Vercel CLI globally on your machine.

   ```sh
   npm install -g vercel
   ```

3. **Login to Vercel**: Log in to your Vercel account using the CLI.

   ```sh
   vercel login
   ```

4. **Deploy the site**: Run the following command in the root directory of your project.

   ```sh
   vercel
   ```

   Follow the prompts to set up and deploy your project. Vercel will provide you with a deployment URL once the process is complete.

5. **Configure Vercel settings**: You can configure additional settings for your deployment in the Vercel dashboard, such as custom domains, environment variables, and more.

For more detailed information, refer to the [Vercel documentation](https://vercel.com/docs).
