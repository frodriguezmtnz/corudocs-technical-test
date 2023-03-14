---
date: 2023-03-14T14:07:10+00:00
title: Installation
pre: "<b>2.3 </b>"
weight: 18
---

Open your favorite terminal, and place it in the Development (DEV) folder you usually use. We are going to install Stripe v4 locally in a new folder on our computer.

To do this, execute the following commands:

```bash
mkdir strapicorunet && cd strapicorunet
```

![imagen mkdir strapi folder](http://drive.google.com/uc?export=view&id=1a75-UvM96jlLamtZr2cBsyfyQ2nkAg4B)

```bash
npx create-strapi-app@latest strapi-corunet --quickstart
```

![imagen lastes strapi app](http://drive.google.com/uc?export=view&id=1-L1obMZslCSTBlub2VDPJR1KzUbl8Z0w)

{{% notice note %}}
'npx' runs a command from an npm package.

'create-strapi-app' is the Strapi package.

'@latest' indicates that the latest version of Strapi is used 'strapi-corunet' is the name of your Strapi project

--quickstart: Directly create the project in quickstart mode.
{{% /notice %}}

The script will ask us whether to install or configure by default certain features of Strapi, for the moment, we configure everything as "recommended" and click continue (yes/y).

Once the installation is finished, Strapi will be installed locally on your computer.

{{% notice tip %}}
💻 There are **several commands to make use of Strapi:**
{{% /notice %}}

| Command  | Description |
| -------  | ----------- |
| npm run develop   | Start Strapi in watch mode (changes in Strapi project files will trigger a server restart). |
| npm run start | Start Strapi without watch mode. |
| npm run build    | Build Strapi admin panel. |
| npm run strapi   | Display all avaible commands. |

![imagen strapi comandos list](http://drive.google.com/uc?export=view&id=1ZAT3yYAdFnOwxZgf6W6ow0k0g7UmssZ7)

In the next step, we'll learn ***how to launch Strapi in development mode*** 🚀.
