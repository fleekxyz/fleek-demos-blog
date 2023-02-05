<p align="center">
  <img src="https://raw.githubusercontent.com/fleekxyz/fleek-demos-blog/f3ceabbd16af559fed4527299142a4b5c4ce8bd7/.github/nextra-blog.png" height="450" title="Fleek.xyz" alt="fleek-xyz logo">
</p>

# Fleek Demos Blog

This repo is part of [fleekxyz/templates](https://github.com/fleekxyz/templates) a collection of Collection of Boileplates & examples configured to easily deploy to Fleek.xyz with the pre-configured scrips.

## Getting started

Here is a summary of the available scripts and a description.

### Install dependencies
```
yarn
```

### Start development mode
This will start a server on http://localhost:3000 where you can check the changes made to the content.
```
yarn develop
```

### Build your site
This will use `next build & next export` creating a directory called `out` which contains the site that will be uploaded
```
yarn build
```

### Configure `fleek.json` using Fleek's CLI
You can configure this site using Fleek's CLI, to get started run:
```
fleek sites init
```
It will prompt you for the following inputs:
1. Site name: You can go ahead and create a new site
2. Specify dist directory: Use `out` which contains the site exported by next
3. Build command: You can specify the build command so fleek cli can build & deploy the site for you, you can use `npm run build`

After running this you'll be able to deploy the site using Fleek CLI

### Deploy using Fleek CLI
After configuring the `fleek.json` file using Fleek's CLI you can go ahead and deploy your site by running:
```
fleek sites deploy
```

Then it will output a message that contains you IPFS CID
```
Export successful. Files written to fleek-demos-blog/out
 
> Success! Deployed! IPFS CID: Qmb2psuVMkGfSdH3egfLEHc2di5VKtDVdTqtB8wqFNbK2h
```

## Contributing

Contributions are always welcome!

Please refer to each project's style and contribution guidelines for submitting patches and additions. In general, we follow the "fork-and-pull" Git workflow.

1. Fork the repo on GitHub
2. Clone the project to your own machine
3. Commit changes to your own branch
4. Push your work back up to your fork
5. Submit a Pull request so that we can review your changes

> NOTE: Be sure to merge the latest from "upstream" before making a pull request!
