# Getting Start
<p>You Can Use in css file.</p>


## Insert `<link>` tag in your `<head>` element
```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/MASTER0811/button-var-css/main.css">
```
#### OR
Use [Git Clone](https://git-scm.com/)
```git
git clone https://github.com/MASTER0811/simple-var-css.git
```

## Create a new css file or add `<style>` tag
Exp in css file add `:root`:
```css
:root{

}
```
### OR
Exp in `<style>` tag:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exp File</title>
</head>
<style>
    :root{
        
    }
</style>
<body>
    
</body>
</html>
```
###  add `button` tag
##### Notice：Only Can Add `button` tag
```html
<!-- add button class ws-btn -->
<button class="ws-btn">The Button</button>
```

## What we can use those `var`?
| style | In var |
|-------|--------|
| padding | `--this-padding` |
| margin |`--this-margin`|
| border-radius |`--this-border-radius`|
| font-family |`--this-font-family`|
| font-size |`--this-font-size`|
| font-weight |`--this-font-weight`|
| background |`--this-background`|
| color |`--this-color`|
| border |`--this-border`|
| outline |`--this-outline`|
| cursor |`--this-cursor`|
| transition |`--this-transition`|
| position |`--this-position`|
| transform |`--this-transform`|
| box-shadow |`--this-box-shadow`|

In `hover`
| style | In var |
|-------|--------|
| box-shadow |`--this-hover-box-shadow`|
| transform |`--this-hover-transform`|

In `active`
| style | In var |
|-------|--------|
| background |`--this-background`|
| opacity | `--this-active-opacity`|

## You Can Use Like that
Exp:
#### index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exp File</title>
    <link rel="stylesheet" href="./style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/MASTER0811/button-var-css/main.css">
</head>
<body>
  <button class="ws-btn">The Button</button>
</body>
</html>
```
#### style.css
```css
:root{
    --this-background: #4285f4;
    --this-color:#fff;
    --this-padding: 0.5em 1.4em;
    --this-border: 0;
    --this-outline: none;
    --this-border-radius: 3px;
    --this-font-size: 15px;
    --this-font-weight:600;
    --this-font-family: 'Poppins', sans-serif;
    --this-cursor: pointer;
    --this-transition: .5s ease-in-out;
    --this-position: relative;
    --this-box-shadow: rgba(100, 100, 111, 0.25) 0px 7px 29px 0px;

    --this-hover-transform: translateY(-1.5px);
    --this-hover-box-shadow:rgba(100, 100, 111, 0.6) 0px 7px 29px 0px;

    --this-active-background:#4286f4e7;
    --this-active-opacity: .8;
}
```








