---
sidebar_position: 2
---

# Track

The `track` API call is how you record any actions your users perform, along with any properties that describe the action.

Its API is identical to the equivalent Segment [track](https://segment.com/docs/connections/spec/track/) function.

`````javascript
analytics.track('Item purchased', {
  item: 'Chair-4624',
  price: 39.99
});
`````
