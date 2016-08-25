# Week 4 - More html styling

## Last Week Recap

1. Display image on our web page
2. Change image into a clickable link
3. Structure our web page layout by using table

## Let's create a Todo List
Everyday we will have a list of tasks that we need to accomplish. We can write down all the tasks on our notebook or **we can code it out in our web page!!!**

We can create list by using ordered `<ol>` and unordered list `ul` element tags.

Reference link: http://www.w3schools.com/html/html_lists.asp

```
<body>
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
</body>
```

Do you notice we can nest list in a list?

After we have accomplish a task, we want to make it as done, so let's insert checkbox in each tasks.
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
Do you know, other than `checkbox` we have plenty of different `input` types in HTML. You can know more by referring to this website, http://www.w3schools.com/html/html_form_input_types.asp

Usually add a **nice background image** will immediately improve your website appearance!!!

```
<body style="background-image:url(http://www.millionglitters.com/background/thumb/hearts/heart-pattern-067.jpg)">
</body>
```

Sometime we have one or two very important tasks that we must accomplish, so let's emphasize the important tasks in our list.

We can change the text style, for example, size and weight.

Reference: http://www.w3schools.com/cssref/pr_font_font.asp

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

Changing the size, style, and weight are not enough. We can give more decoration to the text, for example, line through and underline.

Reference: http://www.w3schools.com/cssref/pr_text_text-decoration.asp

_Tips: we can set the default value of checkbox as "checked"._

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
  * Reference: https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_started/Why_use_CSS

## What is CSS Id, Class, and Element

#### Id Selector
The id selector uses the id attribute of an HTML element to select a specific element.
The id of an element should be unique within a page, so the id selector is used to select one unique element!
To select an element with a specific id, write a hash (`#`) character, followed by the id of the element.

```
#special-task {
    font-weight:bold;
    font-size:24px;
    color: red;
}
```

#### Class Selector
The class selector selects elements with a specific class attribute.
To select elements with a specific class, write a period (`.`) character, followed by the name of the class.

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

Reference: http://www.w3schools.com/css/css_syntax.asp

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
### Learn more about CSS pseudo class

A pseudo-class is used to define a special state of an element.

For example, it can be used to:

* Style an element when a user mouses over it, `hover`
* Style visited and unvisited links differently, `visited`
* Style an element when it gets focus, `focus`

Reference: http://www.w3schools.com/css/css_pseudo_classes.asp

```
li:hover {
  color: red;
  background-color: gray;
}
```

### Learn more about CSS pseudo element
A CSS pseudo-element is used to style specified parts of an element.

For example, it can be used to:

* Style the first letter, or line, of an element
* Insert content before, or after, the content of an element

Reference: http://www.w3schools.com/css/css_pseudo_elements.asp

```
ul li:before
{
    content: '\2713';
    margin: 0 0.5em;
}
```

### Learn more about layout position (homework)
  * http://learnlayout.com/position-example.html
### More Challenges (homework)
  * https://www.freecodecamp.com/challenges/create-a-set-of-checkboxes
  * https://www.freecodecamp.com/challenges/create-an-ordered-list

