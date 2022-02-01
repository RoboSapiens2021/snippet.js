# snippet.js

Hey! This is a light weight library for making, well, code snippets! It's easy, we promise!

Before we start, make sure you have these two files ready to go:

`index.html`\
`index.js`\
`style.css`


## Javascript Import


```<script src="https://cdn.jsdelivr.net/gh/RoboSapiens2021/snippet.js/dist/highlight.js"></script>```
Put this script tag into your body tag. This script handles the text highlighting. So far, it only works with html. Further testing has to be done to figure out the javascript portion. This script came from w3 schools. The colors are edited. 



## How to use it

#### Great! You have the file imported! Now what?

In your `index.html` file put:

` <div id="code" class="code code-wrapper">
      </div>`
    
You can change the id if you want, it does not matter. 
Because of the way html works, you cannot just put your html code inside of the div. 
You need to use html entities. [This](https://dev.w3.org/html5/html-author/charref) is a list of all the entities. 
If that sounds like to much work, you can look up html entity encoder. Paste that in the div. Wrapping the div with h1, h2, h3, h4, h5, h6, or p tags 
can help with sizing

        
 ## Enabling in highlighting!
 
 After doing that, you should see the code snippet but with no highlighting. If that's want you want, then you are done. But in my opinion, it looks pretty plain. Let's fix that!
 In your `index.js` file, add 
 ```javascript
var elements = document.getElementsByClassName("code");
highlighter(elements[0]);
highlighter(elements[1]);
highlighter(elements[2]);
```

Doing it this way allows you to have certain snippets that are not syntax highlighted. Just add a 

```javascript
highlighter(elements[0]);

```

The number in the array corresponds to your div. If you have two snippets and you want bot of them to be highlighted, you would do:

```javascript
var elements = document.getElementsByClassName("code");
highlighter(elements[0]);
highlighter(elements[1]);
```

Make sure to define elements!


## Custom CSS styling

You can easily style your code boxes! Declare a `.code` in your css file. After doing that, you can mess around with different\
properties. 

### Example

```css
.code-wrapper {
  color: rgb(0, 128, 117);
  border: solid 1px black;
}

```

# Thanks for reading!



 
    
