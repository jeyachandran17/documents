## CSS Documents

### what is CSS ?

1. CSS stands for `Cascading style sheet`
2. CSS describes `how HTML elements are to be displayed on screen`
3. External stylesheets are stored in CSS files

<hr>

### CSS comments

1. Comments are not displayed in the browser.
2. Comments are used to explain the source code, and may help when you edit the source code
3. This comment is placed inside the `<style>` element, and starts with `/*` and ends with `*/`
4. Example :
```
/* This is a comment line */
```
<hr>

### CSS variable

1. To declared in `--` front of the variable name
2. The `var()` function is used to insert the value of a CSS variable.
- Example
```
:root{
    --variable_name: red;
}

p{
    color: var(--variable_name);
}


```

<hr>

### CSS Box model

1. In CSS, the term `box model` is used when talking about design and layout.

2. The CSS box model is essentially a box that wraps around every HTML element. 
3. It consists of: `margins, borders, padding, and the actual content`.
    - `Content` --> The content of the box, where text and images appear
    - `Padding` --> Clears an area around the content. The padding is transparent
    - `Border` --> A border that goes around the padding and content
    - `Margin` --> Clears an area outside the border. The margin is transparent

<hr>

### CSS Color 

1. The CSS color uses color values to specify a color.

2. Typically, these are used to set a color either for the foreground of an element (i.e., its text) or else for the background of the element.

3. They can also be used to affect the color of borders and other decorative effects.

4. CSS Colors are specified using predefined colors color
    - Names of color
    - RGB values
    - HEX values
    - HSL values
    - RGBA values
    - HSLA values.

- #### Name of color
    - In CSS, a color can be specified by using a predefined color name. like,
<div style="display:flex;gap:10px;">
    <h3 style="padding:10px;background-color:Tomato;">Tomato</h3>
    <h3 style="padding:10px;background-color:Orange;">Orange</h3>
    <h3 style="padding:10px;background-color:DodgerBlue;">DodgerBlue</h3>
    <h3 style="padding:10px;background-color:MediumSeaGreen;">MediumSeaGreen</h3>
    <h3 style="padding:10px;background-color:Gray;">Gray</h3>
    <h3 style="padding:10px;background-color:SlateBlue;">SlateBlue</h3>
    <h3 style="padding:10px;background-color:Violet;">Violet</h3>
    <h3 style="padding:10px;background-color:LightGray;">LightGray</h3>
</div>
<hr>