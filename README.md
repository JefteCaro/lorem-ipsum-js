# lorem-ipsum-js
Lorem Ipsum generator - HTML Plugin

## How to use

Put the script at the end of **body** tag
```html
<script src="js/lipsum-holder.min.js"></script>
```
Add **`<lipsum/>`** tag inside your DOM Element
```html
<div class="your-class">
```
```
  <lipsum/>
```
```html
</div>
```

```html
<span class="span-class">
```
```
  <lipsum/>
```
```html
</span>
```


## How it works?

The script will look for the `<lipsum/>` tag and replace it with the Lorem Ipsum Standard Paragraph:
>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur soccaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


## Format & Count

**format** attribute only accepts **word**, **sentence**, and **paragraph**.

use the **count** attribute to specify unit count

```
<lipsum format="word" count="10"/>

<lipsum format="sentence" count="5"/>

<lipsum format="paragraph" count="1"/>
```
