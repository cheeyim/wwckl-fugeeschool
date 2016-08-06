# Day One

## Say Hello to HTML Elements

Open a text editor in the computer. Write the following :-

```
<h1>Hello</h1>
```

Save the file as `hello.html`. Open the file in the web browser by clicking it in the File Explorer.

What do you see? This is called heading in HTML. `<h1>` is the heading tag. All tags in html must have a closing tag, in this case its `</h1>`. The number in the heading tag refers to the heading level.

Now append World beside `Hello` like so:-

```
<h1>Hello World</h1>
```

Reload the file again. Okay, not try a few other variation :-

```
<h1>
   Hello World
</h1>
```

```
<h1>
   Hello 
   World
</h1>
```

Based on the result that you see, what can you tell?

Lets try something else :-

* If you use Chrome Browser, right click on the page and select `Inspect`.
* If you use Mozilla Firefox, right click on the page and select `Inspect Element`.



## Playing with headers

Lets create a new file, name it `headings.html`.

In the file, create a heading level from 1 to 6 with the text `One`, `Two`, `Three`, `Four`, `Five` and `Six` respectively.

This time, create the file properly with `<html>` and `<body>` tags.

## Stories needs paragraphs, poem needs them too

Lets write out the following poem in an HTML file and name it `ants.html` :-

```
The Tiny Little Ant - Poem by Roger Horsch

There once was a tiny little ant
that was so, so very small
To him, every other single ant
was great big, huge and tall

He tried to help the best he could
as they all lived in their nest
The other ants would push him aside
and say, ' Why don't you take a rest '

There's nothing here that you can do
said, the ants that were passing by
He knew that he was way too small
yet, he knew that he should try

...

```

By now you should know how to set the title as a header.

Does the poem looks like the way you intend them to display?

Let's add `<p>` tag at the beginning of the paragraph and end it at the end of paragraph.

Is it somewhat better?

Let's add `<br>` tag at the end of every line. This tag stands for "break", hence it's breaking the line.

`<br>` is also one of the tag that doesn't need to have an ending tag.


## There is such a thing as a comment

Now time to make things disappear. Lets try to hiding the second paragraph of the poem by commenting them. Comment is started with `<!--` and ends with `-->`. Edit the `ants.html` file to remove the second paragraph.

What purpose do you think a comment serve in an HTML document?


## Placeholder o placeholder!

```
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tenent mordicus. Duo Reges: constructio interrete. Nihil enim iam habes, quod ad corpus referas; Nam et complectitur verbis, quod vult, et dicit plane, quod intellegam; Qua igitur re ab deo vincitur, si aeternitate non vincitur? Aliter enim explicari, quod quaeritur, non potest.

Quod autem ratione actum est, id officium appellamus. Ut scias me intellegere, primum idem esse dico voluptatem, quod ille don. Pauca mutat vel plura sane; Quem Tiberina descensio festo illo die tanto gaudio affecit, quanto L. Eiuro, inquit adridens, iniquum, hac quidem de re; Qui convenit? Semper enim ex eo, quod maximas partes continet latissimeque funditur, tota res appellatur.

Itaque hic ipse iam pridem est reiectus; Quod cum accidisset ut alter alterum necopinato videremus, surrexit statim. Hoc non est positum in nostra actione. Neminem videbis ita laudatum, ut artifex callidus comparandarum voluptatum diceretur. Vitiosum est enim in dividendo partem in genere numerare. Quod ea non occurrentia fingunt, vincunt Aristonem;

Qua ex cognitione facilior facta est investigatio rerum occultissimarum. An tu me de L. Quae sequuntur igitur? Facillimum id quidem est, inquam. Scrupulum, inquam, abeunti; Hoc est non dividere, sed frangere. Theophrastus mediocriterne delectat, cum tractat locos ab Aristotele ante tractatos? Quid ad utilitatem tantae pecuniae?

Maximus dolor, inquit, brevis est. Haec quo modo conveniant, non sane intellego. Huius ego nunc auctoritatem sequens idem faciam. Esse enim, nisi eris, non potes.
```


## Let's go wild with colors

Write down the place holder text presented in the previous section in a file called `placeholder.html`.

Add colors to the paragraph tag by adding a style attribute, like `<p style="color: blue">`. The word `style` is an HTML attribute that can be applied to any HTML tags. This style of styling HTML is called inline styling.

Certain attributes in HTML have very specific meaning and the browser will interpret them accordingly. You can however, add any different attributes, but it won't have any effects by default.

Now, color each paragraph differently. Go wild!!

p/s: please note the spelling, it has to be the American version of the word color, instead of the British colours

p/s: take a guess what colors does the browser understand!


## Selectors to select

This time we are going to use CSS to select the paragraph to color. To start this, remove the style attributes that you have put in `placeholder.html`. 

Next create a `<head>` tag section before the body and put the following :-

```
<style>
	p {
    	color: red;
    }
</style>
```

Save the file and then keep trying with different colors of your choosing. Notice how this affects everything instead of individual paragraphs.

p/s : can we put the style tag in the `<body>` tag instead of the `<head>` tag? Why or why not?


## Identify yourself

We will now try to color the paragraph differently using CSS selection. Using the same `paragraph.html` file, in each paragraph add an `id` attribute with a specific name, like so :-

```
<p id="one">
```

Give all the paragraph different names for the `id`.

In the `<head>` tag, change the style to be the following :-

```
<style>
	#one {
    	color: red;
    }
    #two {
    	color: blue;
    }
</style>
```

Repeat the styling until you cover every paragraph. Color the paragraph with the color of your choosing.


## Stay classy

We have colored the different paragraphs with different colors with `id` and it worked. Let's try with class now instead.

Remove all the `id` attributes in all the paragraphs. Add another attributes called `class` like so to odd and even paragraph respectively :-

```
<p class="odd"> .....
<p class="even"> .....
```

Replace the style to be the following :-

```
<style>
	#odd {
    	color: red;
    }
    #even {
    	color: blue;
    }
</style>
```

Experiment until you found your favorite alternating colors.

## Indentity crisis

When do you think we should use `class` and `id`? Are both identical? What do you think?


## Size of the title

In the `paragraph.html` document, lets add the following title before the paragraphs :-

```
<h1>Negat enim summo bono afferre incrementum diem</h1>
```

Save the document. Right now, lets make the heading a bit smaller. Add the following in your style :-

```
h1 {
	font-size: 24px;
}
```

Do you like that size? Let's change it until you find the size that you like.

p/s: how do you think the browser knows how to make size it was originally?
