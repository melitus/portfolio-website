# # ReactJS Portfolio Template

![ReactJS Resume Website Template](portfolio.png?raw=true "ReactJS Resume Website Template")

## <a href="https://pensive-golick-762a4c.netlify.app" target="_blank">LIVE DEMO</a>

## Description
This is a ReactJS based personal resume website template for participants of The 6 Figure JavaScript ReactJS Challenge by Clever

## Make it Your Own!
#### PREREQUISITES:
- Sign up for a Netlify account <a href='https://www.netlify.com'>HERE</a>
- Install Node JS in your computer <a href='https://nodejs.org/en/'>HERE</a>
#### PROCEDURE:
- Download the zip folder from Github and unzip it
Here is the link to download zip 👉
<a href='https://github.com/CleverProgrammers/portfolio-react-cp/archive/master.zip'>HERE</a>
- Open the folder in VS Code
- Edit <code>src/portfolio.js</code> and add your personal details and projects
- Open terminal in VS Code
- RUN <code>npm init</code> , this command can be used to set up a new or existing npm package
- RUN <code>npm install</code> , this command pulls out all the require node modules
- RUN <code>npm run build</code>, this command will create a build folder for you
- DRAG AND DROP the BUILD folder on Netlify, your app is live now for the world to see


## Deployment
When you are done with the setup, you should host your website online.
We highly recommend to read through the [Deploying on Github Pages](https://create-react-app.dev/docs/deployment/#github-pages) docs for React.

#### Configuring GitHub Actions
- Using the Personal Access Token you placed in the `.env` file earlier create a [repository secret](https://docs.github.com/en/actions/configuring-and-managing-workflows/creating-and-storing-encrypted-secrets#creating-encrypted-secrets-for-a-repository) called `OPEN_SOURCE_TOKEN` where the value matches the token value from the `.env` file in your local workspace.
- When you are done with the configuration, we highly recommend to read through the [Github Actions Configuring a workflow](https://docs.github.com/en/actions/configuring-and-managing-workflows/configuring-a-workflow) docs.

#### Deploying to Github Pages

This section guides you to deploy your portfolio on Github pages.

- Navigate to `package.json` and enter your domain name instead of `https://xxxx.js.org/` in `homepage` variable. For example, if you want your site to be `https://<your-username>.github.io/portfolio-website`, add the same to the homepage section of `package.json`.

- In short you can also add `/portfolio-website` to `package.json` as both are exactly same. Upon doing so, you tell `create-react-app` to add the path assets accordingly.

- Optionally, configure the domain. You can configure a custom domain with GitHub Pages by adding a `CNAME` file to the `public/` folder.

- Follow through the guide to setup GitHub pages from the official CRA docs [here](https://create-react-app.dev/docs/deployment/#github-pages).

#### Deploying to Netlify

You could also host directly with Netlify by linking your own repository.

[![Deploy To Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/melitus/portfolio-website)

For more information, read [hosting on Netlify](https://create-react-app.dev/docs/deployment/#netlify).


## Technologies Used

- [React](https://reactjs.org/)
- [graphql](https://graphql.org/)
- [apollo-boost](https://www.apollographql.com/docs/react/get-started/)
- [react-twitter-embed](https://github.com/saurabhnemade/react-twitter-embed)
- [react-easy-emoji](https://github.com/appfigures/react-easy-emoji)
- [react-headroom](https://github.com/KyleAMathews/react-headroom)
- [color-thief](https://github.com/lokesh/color-thief)

## Illustrations
- [UnDraw](https://undraw.co/illustrations)
- [Lottie by Oblikweare](https://lottiefiles.com/oblikweare)


## Credits

#### Credits to Saad Pasta <a href='https://github.com/saadpasta/developerFolio'>Original Repo</a>
