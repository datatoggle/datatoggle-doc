---
sidebar_position: 2
slug: /quick-start
---

# Quick Start

## Add your first destination

After having created your account and chosen your project name at **[app.datatoggle.com](https://app.datatoggle.com)**, 
Add a first 
destination with button `New 
Destination`.

On this documentation, select the chosen destination in the left panel (`Destinations` category) to see how to 
configure it. Most of the time, you just have to indicate an API key provided by your destination.

Once configured, click on `Enabled` then `Save Settings`.

## Install Datatoggle SDK on your website

1. For now, Datatoggle is only available as a npm package, install it with

```shell
npm install @datatoggle/datatoggle-sdk
```

2. On your website, initialize the datatoggle sdk using

````javascript
import datatoggle from '@datatoggle/datatoggle-sdk'

//...

datatoggle.init("DATATOGGLE_API_KEY")
````

You will find your `API KEY` on the `Project Overview` section of **[app.datatoggle.com](https://app.datatoggle.com)**

## Track your first event



-------------------

## Getting Started

Get started by **creating a new site**.

Or **try Docusaurus immediately** with **[docusaurus.new](https://docusaurus.new)**.

## Generate a new site

Generate a new Docusaurus site using the **classic template**:

```shell
npm init docusaurus@latest my-website classic
```

## Start your site

Run the development server:

```shell
cd my-website

npx docusaurus start
```

Your site starts at `http://localhost:3000`.

Open `docs/intro.md` and edit some lines: the site **reloads automatically** and display your changes.
