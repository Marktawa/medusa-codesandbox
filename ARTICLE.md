# How to run Medusa with CodeSandbox

## Introduction

This tutorial showcases how you can run your Medusa projects online using CodeSandbox, an online cloud development environment.

## What is Medusa?

[Medusa](https://medusajs.com/readme/) is a composable commerce engine for building bespoke ecommerce applications. It packages its ecommerce features as Commerce Modules fit for any business use case. 

Medusa is one of the few entirely free and open-source ecommerce packages with a ton full of features. You can customize your app however you like and host it on any platform.

Under the hood, Medusa is a Node.js application built with Express and other tools on top for added functionality like caching, event handling and so on.

![Ecommerce Building Blocks](https://res.cloudinary.com/dza7lstvk/image/upload/fl_lossy/f_auto/r_16/ar_16:9,c_pad/v1/Medusa%20Docs/Diagrams/ecommerce-building-blocks_llgnn2.jpg?_a=ATAPpAA0)

Some of the features of Medusa include:
- Optimized Shopping and Fulfillment Experience: This includes order and inventory management as well as cart and checkout
- Advanced Product Configurations and Management: Features like product management, gift cards, price lists and discounts
- Ready Configurations for International Selling: This includes sales channels, taxes, and multi-region support

You can read more on [Medusa's features here](https://docs.medusajs.com/modules/overview).

## What is CodeSandbox?

[CodeSandbox](https://codesandbox.io/features) is a cloud-based development environment for developing, building, testing, and sharing projects. It can be accessed in your browser. No set up is required.

Its features include:
- Live Collaboration
- GitHub Committing/Forking/PRing
- VS Code Integration
- Container Sandboxes
- Dashboard & Teams
- Beginner Friendly
- Deployable Sandboxes

Read more on [CodeSandbox's features here](https://codesandbox.io/blog/whats-unique-about-codesandbox)

## Why CodeSandbox?

CodeSandbox is fast, flexible and full-featured. It provides an adequate set of tools to prototype any Medusa ecommerce project. The fact that it can be done online with no set up required on my local machine enables any developer to quickly work and collaborate with others. Faster setup means more time spent working with the actual code of the project.

CodeSandbox also offers a generous free tier with very reasonable limits. This enables any developer including beginners to tinker with as many projects without having to spend a dime.

CodeSandbox also has extensive documentation which can help you quickly set up any project you like without cracking your brain.

## Prerequisites

For this tutorial you will need:
- [GitHub account](https://github.com/signup) 
- [CodeSandbox account](https://codesandbox.io/signin) *You can sign in using your GitHub account*
- Web browser.

## Step 1: Launch CodeSandbox

In your browser, log in to your GitHub account, create a repository, and name it `medusa-sandbox`.

![Create repo]()

Take note of the URL of this repo. You will import this repo into CodeSandbox. 

Sign in to CodeSandbox and visit the [dashboard](https://codesandbox.io/dashboard). 

In the dashboard, click on the `+ Create` button in the top right corner. In the modal that appears select `Import repository`. Paste in the GitHub URL to the `medusa-sandbox` repo and click `Import`.

![Import repository]()

CodeSandbox will automatically create a workspace with a MicroVM to host and test your repo.

![CodeSandbox workspace]()

## Step 2: Set up Medusa

We will set up Medusa following the [Install Medusa with create-medusa-app guide](https://docs.medusajs.com/create-medusa-app) in Medusa's documentation.

In your CodeSandbox terminal, test if node is installed:

```bash
node -v
```

The version you should get should be `>= 16` as Medusa supports Node version 16 and above.

Start the medusa project creation process by running the following command:

```bash
yarn create medusa-app
```

After running this command you will be prompted for options for your Medusa project.

For this tutorial, we will use the default options provided by Medusa as follows:

- Project Directory Name: `my-medusa-store`
- Medusa Backend Starter: `medusa-starter-default`
- Storefront Starter: `Next.js Starter`

After providing your responses the installation script will install the Medusa backend and the Next.js storefront in the project directory named my-medusa-store.






