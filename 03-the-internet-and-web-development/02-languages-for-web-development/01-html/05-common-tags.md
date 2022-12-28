# Common Tags

Now that I have looked at an example of HTML elements, its time to start practicing using them by writing a few different tags myself.

```html
<h1>This is a heading, it emphasizes text.</h1>
 
<p>This is a paragraph, it is the most common tag for 
  larger chunks of text.</p>
 
<a>This is an anchor tag, used to specify the text 
  that is the "anchor" for a link.</a>
 
<button>This is a button.</button>
```

## Example

The HTML above shows a few common tags.  These tags can be seen in use in the sample HTML below. 

```html
<h1>Jetsetter Travel Agency</h1>
<p>With over 25 years of experience in concierge, high-end travel planning, 
  we'll provide you with the highest quality services. Every vacation is unique, 
  custom, and tailored to your tastes.
<button>Click here!</button></p>
```

It is possible to see the above HTML in action on the right panel of [this lesson](https://www.codecademy.com/paths/front-end-engineer-career-path/tracks/fecp-22-overview-of-web-development/modules/wdcp-22-the-internet-and-web-development/lessons/web-dev-lang/exercises/html-paragraph-tag) on the Codecademy website. 

# Questions

**(Q):**  What happens if we don't add a closing tag?

**(A):**  If you do not add a closing tag for an HTML element, you may end up with unexpected issues with your webpage. However, excluding a closing tag will not cause error messages or crashes, so they technically are not an absolute requirement. But, this does not mean you should exclude them.

One important reason to add a closing tag is that anything that follows an opening tag in the HTML code will become nested in that element. For example, say you meant to have two separate elements, such as a <div> and a <p> element. Like so,

```html
<body>
  <div>
  </div>
  <p>
  </p>
</body>
```

If you omit the closing tags of the elements, like so

```html
<body>
  <div>
  <p>
</body>
```

then the paragraph element is now nested inside the div element. This can cause many issues in terms of layout and design of a webpage.

Adding closing tags is also best practice, and should always be included. If you do that then errors will be avoided, and it will reduce confusion when other developers are working on the same code.

Some elements do not need a closing tag (known as “void” tags), such as <br>, <img>, and <link> tags, because they do not have content. But for other types of elements, you should always add a closing tag to them.

## Community Forums

More questions and answers can be found on the [Codecademy Community Forums](https://discuss.codecademy.com/t/faq-languages-for-web-development-common-tags/372094) for this lesson. 