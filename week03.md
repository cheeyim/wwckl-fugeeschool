# Week 3rd

## 3.1 Image on Your Team Website

### Introduction

You can add images to your website by using the `img` element, and point to a specific image's URL using the src attribute.

An example of this would be:

```
<img
 src="https://www.your-image-source.com/your-image.jpg"
 alt="I love to learn"
 title="I love to learn">
```

All `img` elements must have an `alt` attribute. The text inside an `alt` attribute is used for screen readers to improve accessibility and is displayed if the image fails to load.

### Tutorial

#### 3.1.1 Tutorial - Show `image` on HTML page

1. Login into http://codepen.io/jecelyn/
2. Open your respective team HTML project
3. Copy any of the following codes

```
<img src="http://goo.gl/ilfhkZ">
OR
<img src="http://goo.gl/1IZvy3">
OR
<img src="http://goo.gl/Giz7D2">
OR
<img src="http://goo.gl/XT1OUi">
OR
<img src="http://goo.gl/KZ2vnS">
```

4. In the **HTML** box, paste your copied codes at the end of codes
5. Observe the change on your team HTML page
6. What did you see?
   * Each team to tell the class on the result

### 3.1.2 Tutorial - Explain your team `image`

1. In the **HTML** box, find back the existing `<img...>`
2. Add the new attributes `alt` & `title` into the `<img...>` as below

```
<img
 src="http://...."
 alt="Type in your team explanation from previous tutorial"
 title="Type in your team explanation from previous tutorial">
```

3. Move computer's (mouse) cursor on to the image
4. Observe anything that will appear on computer's (mouse) cursor
5. What did you see?

## 3.2 Image as `Home Address` (Website Link)

### Introduction

You can make elements into links by nesting them within an a element.

Nest your image within an a element. Here's an example:

```
<a href="http://www.website.com">
<img
 src="http://goo.gl/ilfhkZ"
 alt="I love to learn"
 title="I love to learn">
</a>
```

### Tutorial

#### 3.2.1 Tutorial - Image as `Home Address` (Website Link)

1. In the **HTML** box, find back the existing `<img...>`
2. Copy any of the following codes

```
<a href="http://www.google.com">
OR
<a href="http://www.yahoo.com">
```
3. Paste your copied codes before the `<img...>` as below

```
<a href="http://www.google.com">
<img
 src="http://...."
 alt="Type in your team explanation from previous tutorial"
 title="Type in your team explanation from previous tutorial">
```

4. Copy the following codes

```
</a>
```

5. Paste your copied codes after the `<img...>` as below

```
<a href="http://www.google.com">
<img
 src="http://...."
 alt="Type in your team explanation from previous tutorial"
 title="Type in your team explanation from previous tutorial">
</a>
```

6. Move computer's (mouse) cursor on to the image
7. Observe anything that will appear on computer's (mouse) cursor
8. What did you see?
9. Click on the image
10. What did you see?

## 3.3 Style Your Team Image

### Introduction

You can use the style attribute to specify the `width` and `height` of an image.

The values are specified in pixels (use px after the value):

```
<img
 src="http://goo.gl/ilfhkZ"
 alt="I love to learn"
 title="I love to learn"
 style="width:128px;height:128px;">
```

### Tutorial

#### 3.3.1 Tutorial - Resize your team image

1. In the **HTML** box, find back the existing `<img...>`
2. Copy the following codes (`attribute`)

```
 style="width: 500px; height: 50px"
```

3. Paste the copied codes into the `<img...>` as below

```
<img
 src="http://...."
 alt="Type in your team explanation from previous tutorial"
 title="Type in your team explanation from previous tutorial"
 style="width: 500px; height: 50px">
```

3. Move computer's (mouse) cursor on to the image
4. Observe the change on your team HTML page
5. What did you see?

## 3.4 Organize Your Team HTML Page Information

### Introduction

An HTML table is defined with the `<table>` tag.

Each table row is defined with the `<tr>` tag. A column header is defined with the `<th>` tag. By default, table headings are bold and centered. A table data/cell is defined with the `<td>` tag.

### Tutorial

#### 3.4.1 Tutorial - 3x2 table

1. Copy the following codes

```
<table>
<tr>
  <td>CELL1</td>
  <td>CELL2</td>
  <td>CELL3</td>
</tr>
<tr>
  <td>CELL4</td>
  <td>CELL5</td>
  <td>CELL6</td>
</tr>
</table>
```

2. In the **HTML** box, paste the copied codes at the end of codes
3. Observe the change on your team HTML page
4. What did you see?

#### 3.4.2 Tutorial - Reorganize your team HTML Page information into 3x2 `table`

1. In the **HTML** box, find back the existing `<table>`
2. Reorganize the information into any of the cells `CELL1`, `CELL2`, or ...
3. Observe the change on your team HTML page
4. What did you see?

#### 3.4.3 Tutorial - Explain your team `table`

1. In the **HTML** box, find back the existing `<table>`
2. Copy the following codes

```
<caption>Type in your team table explanation here</caption>
```

3. Paste the copied codes between `<table>` and first `<tr>` as below

```
<table>
<caption>Type in your team table explanation here</caption>
<tr>
  <td>CELL1</td>
...
```

4. Observe the change on your team HTML page
5. What did you see?

#### 3.4.4 Tutorial - Explain your team `table column`

1. In the **HTML** box, find back the existing `<table>`
2. Copy the following codes

```
<tr>
  <th>COLUMN TITLE 1</th>
  <th>COLUMN TITLE 2</th>
  <th>COLUMN TITLE 3</th>
</tr>
```

3. Paste the copied codes between `</caption>` and first `<tr>` as below

```
<table>
<caption>Type in your team table explanation here</caption>
<tr>
  <th>COLUMN TITLE 1</th>
  <th>COLUMN TITLE 2</th>
  <th>COLUMN TITLE 3</th>
</tr>
<tr>
  <td>CELL1</td>
...
```

4. Observe the change on your team HTML page
5. What did you see?

#### 3.4.5 Tutorial - Merge `table column`

1. In the **HTML** box, find back the existing `<table>`
2. Assume that we want to merge `CELL5` and `CELL6`

<table>
<tr>
  <td>CELL1</td>
  <td>CELL2</td>
  <td>CELL3</td>
</tr>
<tr>
  <td>CELL4</td>
  <td colspan="2">CELL5 CELL6</td>
</tr>
</table>

3. Copy and paste the information from `CELL6` into `CELL5` as below

```
<table>
<tr>
  <td>CELL1</td>
  <td>CELL2</td>
  <td>CELL3</td>
</tr>
<tr>
  <td>CELL4</td>
  <td>CELL5 CELL6</td>
  <td></td>
</tr>
</table>
```

4. Now, delete `<td></td>`
5. Type in `colspan="2"` as `attribute` into `CELL5` as below

```
<table>
<tr>
  <td>CELL1</td>
  <td>CELL2</td>
  <td>CELL3</td>
</tr>
<tr>
  <td>CELL4</td>
  <td colspan="2">CELL5 CELL6</td>
</tr>
</table>
```

6. Observe the change on your team HTML page
7. What did you see?

#### 3.4.6 Tutorial - Merge `table row`

1. In the **HTML** box, find back the existing `<table>`
2. Assume that we want to merge `CELL1` and `CELL4` from previous tutorial

<table>
<tr>
  <td rowspan="2">CELL1 CELL4</td>
  <td>CELL2</td>
  <td>CELL3</td>
</tr>
<tr>
  <td colspan="2">CELL5 CELL6</td>
</tr>
</table>

3. Copy and paste the information from `CELL4` into `CELL1` as below

```
<table>
<tr>
  <td>CELL1 CELL4</td>
  <td>CELL2</td>
  <td>CELL3</td>
</tr>
<tr>
  <td></td>
  <td colspan="2">CELL5 CELL6</td>
</tr>
</table>
```

4. Now, delete `<td></td>`
5. Type in `rowspan="2"` as `attribute` into `CELL1` as below

```
<table>
<tr>
  <td rowspan="2">CELL1 CELL4</td>
  <td>CELL2</td>
  <td>CELL3</td>
</tr>
<tr>
  <td colspan="2">CELL5 CELL6</td>
</tr>
</table>
```

6. Observe the change on your team HTML page
7. What did you see?

#### 3.4.7 Tutorial - Show Separator (`Border`) in 3x2 `table`

1. In the **HTML** box, find back the existing `<table>`
2. Copy the following codes

```
border="1"
```

3. Paste the copied codes as `attribute` into `<table>` as below

```
<table border="1">
<tr>
...
```

4. Observe the change on your team HTML page
5. What did you see?

## 3.5 More Styling

### Introduction

You could format almost any element (`<p>`, `<img>`, `<a>`, `<table>`, `<tr>`, `<th>`, `<td>`, and more) within your HTML page such color, size, background color, and more.

### Tutorial

#### 3.5.1 Tutorial - Font size

1. In the **HTML** box, find back any existing `<p>`
2. Copy the following codes

```
style="font-size:200%;"
```

3. Paste the copied codes as `attribute` into `<p>`
4. Observe the change on your team HTML page
5. What did you see?

#### 3.5.2 Tutorial - Background color

1. In the **HTML** box, find back any existing element (`<p>`, `<a>`, `<table>`, `<tr>`, `<th>`, `<td>`)
2. Copy any of the following codes

```
style="background-color:rgb(255,0,0);"
OR
style="background-color:rgb(0,255,0);"
OR
style="background-color:rgb(0,0,255);"
OR
style="background-color:rgb(255,255,0);"
OR
style="background-color:rgb(255,0,255);"
OR
style="background-color:rgb(0,255,255);"
```

3. Paste the copied codes as `attribute` into `<p>`, `<a>`, `<table>`, `<tr>`, `<th>`, or `<td>`
4. Observe the change on your team HTML page
5. What did you see?

## Good luck<br>Happy Coding!