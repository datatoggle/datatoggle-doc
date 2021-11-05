---
sidebar_position: 1
---

# Mixpanel

## Quick Start

To send data to [Mixpanel](https://mixpanel.com):

1. On tab `Project overview`, click on `New Destination`->`Mixpanel`, then select the newly created destination
2. Enter your Mixpanel [Project token](https://help.mixpanel.com/hc/en-us/articles/115004502806-Find-Project-Token-)
3. Click on `Enabled` and then `Save Settings`

You are now ready to send data to Mixpanel

## Configuration

### Config

You can configure Mixpanel with the `config` settings, referring to the second argument of the [init](https://developer.
mixpanel.com/docs/javascript-full-api-reference#mixpanelinit) function.

For example, to [set Data Residency in EU](https://help.mixpanel.com/hc/en-us/articles/360039135652-Data-Residency-in-EU), add the following entry to `config`
* `key`: api_host
* `value`: https://api-eu.mixpanel.com

which is equivalent to [this config](https://developer.mixpanel.com/docs/javascript#eu-data-residency) in Mixpanel API.
