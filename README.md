# snippet.js

Hey! This is a light weight library for making, well, code snippets! It's easy, we promise!

Before we start, make sure you have these two files ready to go:

`index.html`\
`index.js`



## Javascript Import


```<script src=""https://raw.githubusercontent.com/RoboSapiens2021/snippet.js/main/highlight.js></script>```
Put this script tag into your body tag. This script handles the text highlighting. So far, it only works with html. Further testing has to be done to figure out the javascript portion. This script came from w3 schools. The colors are edited. 

## CSS Import
`<link rel="stylesheet" href="https://raw.githubusercontent.com/RoboSapiens2021/snippet.js/main/style.css.css">`

Put this into the head section of your html file
This handles backgrounds, layout etc.

## How to use it

#### Great! You have the files imported! Now what?

In your `index.html` file put:

` <div id="code" class="code code-wrapper">
      </div>`
    
You can change the id if you want, it does not matter. 
Because of the way html works, you cannot just put your html code inside of the div. 
You need to use html entities. [This](https://dev.w3.org/html5/html-author/charref) is a list of all the entities. 
If that sounds like to much work, you can look up html entity encoder. Paste that in the div. Wrapping the div with h1, h2, h3, h4, h5, h6, or p tags 
can help with sizing

##### Example

    
```html
<div id="code" class="code code-wrapper">
      &lt;!DOCTYPE html&gt;<br />
      &lt;html&gt;<br />
      &lt;body&gt;<br />
      <br />
      &lt;h1&gt;Testing an HTML Syntax Highlighter&lt;/h2&gt;<br />
      &lt;p&gt;Hello world!&lt;/p&gt;<br />
      &lt;a href="https://www.w3schools.com"&gt;Back to School&lt;/a&gt;<br />
      <br />
      &lt;script src = ""&gt;<br />
     
      &lt;/script&gt;<br />

      &lt;/body&gt;<br />
      &lt;/html&gt;
    </div>
    ```
 # fr
    
