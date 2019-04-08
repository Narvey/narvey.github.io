---
title: JSMinders
slug: JSMinders
---

# JSMinders: reminders for JS #

## Loops ##

### Foreach (for .. of) ###
Standard foreach loop in JS is:
```
for(var obj of [{},3,5.3,[9,0],2])
{
    if(typeof(obj)==="number") console.log(obj)
}
```
OR:
```
[{},3,5.3,[9,0],2].forEach(obj=>
{
    if(typeof(obj)==="number") console.log(obj)
})
```

### For .. in ###
Completely unnecessary now that we have `Object.keys({"key":"val"}).foreach`

## Always use === unless you have to use == ##
One example of when you might need == is checking for null/undefined at the same time: `myVar == null`
See [This Table](https://dorey.github.io/JavaScript-Equality-Table/)
