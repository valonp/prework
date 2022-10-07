![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709394-2cabee80-571f-11eb-9518-ea6a794e558e.png)


> In the directory with the exercise you will find a file named `index.html`. Open it in a web browser (just click on it twice).  
> Also, open the files prepared for this exercise in a code editor of your choice (WebStorm, Visual Studio Code).

## Content styling

There are 2 strips at the top and bottom of the page, which are set at 80% width. Between them there is a `.content` element, which is the content of the page on a white background.

Set styling for this element:
* maximum width (max-width) of **80%**,
* internal distance from the edge of the element of **50px** on each side.

As you can see, after applying the above properties the element is slightly wider than the lower and upper strip. What does this result from? Try to apply it with the **box-sizing** property.


## Button styling

The content of the page contains a `.btn` element.

Style it in the following way:
* set internal distance from the edge of the element to `20px 40px`,
* bottom margin `20px`.

As you can see, the element does not quite display well. This is due to the fact that it is a styled link and the links have the default `inline` display. What are the features of this kind of display? Change it to the appropriate one.


## Gallery

At the very bottom of the page there is a gallery with `.gallery` class. Inside the gallery there is a list of photos with `.gallery-content` class. The photos are arranged horizontally. Unfortunately, they do not fit horizontally, and the client does not want them to take up more space vertically (so they cannot wrap to a new line). Use the appropriate property to make a horizontal scroll bar appear in the `.gallery-content`.
