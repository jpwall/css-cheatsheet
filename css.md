# CSS Cheatsheet

## Initial Stylings

Universal `box-sizing: border-box;`

```
html {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*, *:before, *:after {
  -webkit-box-sizing: inherit;
  -moz-box-sizing: inherit;
  box-sizing: inherit;
}
```

Font sizes at different media sizes for `rem` responsive sizing

```
html {
    font-size: 18px;
}

@media only screen and (min-width: 415px) {
    html {
        font-size: 20px;
    }
}

@media only screen and (min-width: 768px) {
    html {
        font-size: 21px;
    }
}

@media only screen and (min-width: 1100px) {
    html {
        font-size: 22px;
    }
}
```

## Other

* Remember: ID properties overwrite class properties
* Avoid inline styles
* Multiple classes can be used per HTML element with spaces in-between