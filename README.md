# Tech Talent South

## What is Markdown Language

## SASS

- Run Scout app to compile SASS

### Variables
`code snippets go in between these`

`variablename: lightblue;`

```
main{
  h1{
    color: blue;
  }
}
```

### Color Operators
```SCSS
h1{color: lighten(blue, 20%)}
h1{color: lighten(blue, 20%)}
```

### Notes on Column Size References in bootstrap
Bootstrap was made first for Mobile Phone first (by twitter developers) and then meant to expand to desktops and larger screens.  

Designing to go from desktop to mobile is much more difficult because of how the screen real estate compresses.

So what are the commands to design something for the different devices.  It is all based on the screen width not necessarily device

col-xs - mobile phone
col-sm - tablet portrait (768px)
col-md - tablet landscape (992px) (can also sometimes work for laptops depending on the size)
col-lg - (1200px)desktop screen size
