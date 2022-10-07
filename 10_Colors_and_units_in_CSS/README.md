![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709394-2cabee80-571f-11eb-9518-ea6a794e558e.png)


> In the directory with the exercise you will find a file named `index.html`. Open it in a web browser (just click on it twice).  
> Also, open the files prepared for this exercise in a code editor of your choice (WebStorm, Visual Studio Code).


The sample page contains a description of Prague and a photo gallery. Your goal is to improve its appearance.


## Container with content

The first thing to improve is the content container. This is an element with the class `.container`.
Use the following styling for it:

* width: **680px**,
* maximum width (max-width property): **90%**,
* distance of the text from the edge of the container: **50px**,
* background color: **rgba(255, 255, 255, 0.95)**,
* font size: **15px**,
* the size of the line spacing: **1.5em**,
* text color: **rgba(0, 0, 0, 0.6)**.


## Headings

Another step will be the appearance of `h1` and `h2` headings.

Set them **common** text color: `#b4411e`.

Then give them the following style:
* font size: 
  * `h1`: `38px`
  * `h2`: `32px`
* the size of the line spacing: 
  * `h1`: `1.2em`
  * `h2`: `1em`


## Gallery

### Part 1

Move on to the gallery now. There are links with pictures in it, i.e. `.gallery a` elements.

Style them in the following way:
* max-width: **50%**,
* padding: **3px**.


### Part 2

Even when you set 50% width for the links, the pictures still don't fit in these links. This is because `img` graphics are displayed in their **original size** by default. Fix this.

For `.gallery img` elements, add the style:
* maximum width (max-width) of **100%**
