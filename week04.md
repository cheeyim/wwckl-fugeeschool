# Week 4

## Recap

## More html styling

### let's create a todo list

1. Create a list of tasks
  * using ordered and unordered list [https://www.freecodecamp.com/challenges/create-an-ordered-list](https://www.freecodecamp.com/challenges/create-an-ordered-list)

```
<ol>
  <li>learn coding</li>
    <ul>
      <li>html</li>
      <li>css</li>
      <li>javascript</li>
    </ul>
  <li>wash clothes</li>
  <li>read harry potter</li>
  <li>meet with Ali</li>
</ol>
```

  * insert checkbox in each tasks [https://www.freecodecamp.com/challenges/create-a-set-of-checkboxes](https://www.freecodecamp.com/challenges/create-a-set-of-checkboxes)

```
<body>
  <ol>
    <li>
      learn coding<input type="checkbox"/>
    </li>
      <ul>
        <li>html</li>
        <li>css</li>
        <li>javascript</li>
      </ul>
    <li>
      wash clothes<input type="checkbox"/>
    </li>
    <li>
      read harry potter<input type="checkbox"/>
    </li>
    <li>
      meet with Ali<input type="checkbox"/>
    </li>
  </ol>
</body>
```

2. Usually add a nice background image will immediately improve your website appearance!!!

```
<body style="background-image:url(http://www.millionglitters.com/background/thumb/hearts/heart-pattern-067.jpg)">
</body>
```

3. let's emphasize important task and keywords
  * We can change the text style, for example, size and **weight**. [http://www.w3schools.com/cssref/pr_font_font.asp](http://www.w3schools.com/cssref/pr_font_font.asp)

```
<ol>
  ...
    <ul>
      <li>html</li>
      <li style="font-weight:bold;font-size:24px">css</li>
      <li style="font-style:italic;">javascript</li>
    </ul>
  ...
</ol>
```
  * Give more decoration to the text for example, line through and underline. Please notice that we can set the default value of checkbox as "checked". [http://www.w3schools.com/cssref/pr_text_text-decoration.asp](http://www.w3schools.com/cssref/pr_text_text-decoration.asp)

```
...
  <li style="text-decoration:line-through">
    wash clothes<input type="checkbox" checked="checked"/>
  </li>
...
```

## Why we want to use CSS?
  * Helps avoid duplication
  * Makes maintenance easier
  * Allows you to make a site-wide change in one place
  * [https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_started/Why_use_CSS](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_started/Why_use_CSS)

### What is CSS id, class, and element

#### Id Selector
The id selector uses the id attribute of an HTML element to select a specific element.
The id of an element should be unique within a page, so the id selector is used to select one unique element!
To select an element with a specific id, write a hash (#) character, followed by the id of the element.

```
#special-task {
    font-weight:bold;
    font-size:24px;
    color: red;
}
```

#### Class Selector
The class selector selects elements with a specific class attribute.
To select elements with a specific class, write a period (.) character, followed by the name of the class.

```
.done {
  text-decoration:line-through
}
```

#### Element Selector
The element selector selects elements based on the element name.

```
body {
  background-image: url("http://www.millionglitters.com/background/thumb/hearts/heart-pattern-067.jpg");
}
ul {
    list-style: none;
}
```

[http://www.w3schools.com/css/css_syntax.asp](http://www.w3schools.com/css/css_syntax.asp)
Let's replace our inline styling with CSS Class and Id

```
<body>
  <ol>
    <li>
      learn coding<input type="checkbox"/>
    </li>
      <ul>
        <li>html</li>
        <li id="special-task">css</li>
        <li style="font-style:italic;">javascript</li>
      </ul>
    <li class="done">
      wash clothes<input type="checkbox" checked="checked"/>
    </li>
    <li class="done">
      read harry potter<input type="checkbox" checked="checked"/>
    </li>
    <li>
      meet with Ali<input type="checkbox"/>
    </li>
  </ol>
</body>
```

## We can do more styling with CSS
### Learn more about css pseudo class like "hover"
  * [http://www.w3schools.com/css/css_pseudo_classes.asp](http://www.w3schools.com/css/css_pseudo_classes.asp)

```
li:hover {
  color: red;
  background-color: gray;
}
```

### Learn more about css pseudo element like "before"
  * [http://www.w3schools.com/css/css_pseudo_elements.asp](http://www.w3schools.com/css/css_pseudo_elements.asp)

```
ul li:before
{
    content: '\2713';
    margin: 0 0.5em;
}
```

### Learn more about layout position(homework)
  * http://learnlayout.com/position-example.html

