---
title: JSMinders
slug: JSMinders
---

# JSMinders: reminders for JS #

## Loops ##

### Foreach (for .. of) ###
Standard foreach loop in JS is:
```
for(var obj of [{},3,[9,0]])
{
    if(typeof(obj)=="number") console.log(obj)
}
```

### For .. in ###
**Only** if you need to know the property names (let's call them propert**in**s for mnemonics' sake) of an _object_ you are looping over.

## Always use === unless you have to use == ##
One example of when you might need == is checking for null/undefined at the same time: `myVar == null`
