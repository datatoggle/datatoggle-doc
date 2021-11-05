---
sidebar_position: 2
slug: /quick-start
---

# Quick Start


## Step 1: Create an account and add your first destination

After having created your account and chosen your project name at **[app.datatoggle.com](https://app.datatoggle.com)
**, click `New 
Destination` to create your first destination.

On this documentation, select the chosen destination in the left panel (`Destinations` category) to see how to 
configure it. Most of the time, you just have to indicate an API key provided by your destination.

Once configured, enable your destination by clicking on `Enabled` then `Save Settings`.

## Step 2: Install Datatoggle SDK on your website

1. Datatoggle is available as a npm package, install it with

```shell
npm install @datatoggle/datatoggle-sdk
```

2. On your website, initialize the datatoggle sdk using

````javascript
import datatoggle from '@datatoggle/datatoggle-sdk'

datatoggle.init('DATATOGGLE_API_KEY')
````

You will find your `API KEY` on the `Project Overview` section of **[app.datatoggle.com](https://app.datatoggle.com)**

## Step 3: Identify users

The `identify` method is how you tell Datatoggle who the current user is. It includes a unique User ID, and any 
optional traits you know about them.

`````javascript
datatoggle.identify('5v2h4d5tyhv24', {
    name: 'Jon Thompson',
    email: 'jthompson@gmail.com'
})
`````

## Step 4: Track actions

The `track` method is how you tell Datatoggle about the actions your users are performing on your site. Every action 
triggers what we call an “event”, which can also have associated properties.

`````javascript
analytics.track('Item purchased', {
  item: 'Chair-4624',
  price: 39.99
});
`````

You are now ready to collect data and send it to your destinations
