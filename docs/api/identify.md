---
sidebar_position: 1
---

# Identify

The Datatoggle `Identify` call lets you tie a user to their actions and record traits about them. It includes a unique 
User ID and any optional traits you know about the user, like their email, name, etc.

Its API is identical to the equivalent Segment [identify](https://segment.com/docs/connections/spec/identify/) function.

`````javascript
datatoggle.identify('5v2h4d5tyhv24', {
    name: 'Jon Thompson',
    email: 'jthompson@gmail.com'
})
`````
