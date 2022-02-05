# Getting Start
<p>You Can Use in css file.</p>


## Insert `<link>` tag in your `<head>` element
```html
  <link rel="stylesheet" href="">
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
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exp File</title>
    <link rel="stylesheet" href="./style.css">
    <link rel="stylesheet" href="./main.css">
</head>
<body>
  <button class="ws-btn">The Button</button>
</body>
</html>
```
