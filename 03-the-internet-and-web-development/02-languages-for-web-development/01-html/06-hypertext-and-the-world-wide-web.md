# Hyertext and the World Wide Web

The H and T in HTML stands for hypertext.  Hypertext is a text that is linked to other text.  the diagram shown in the right panel of [this lesson](https://www.codecademy.com/paths/front-end-engineer-career-path/tracks/fecp-22-overview-of-web-development/modules/wdcp-22-the-internet-and-web-development/lessons/web-dev-lang/exercises/hypertext-www) shows different websites that are connected to each other through links, which are represented by arrows.  

## Whats so Hyper about Hypertext?

The prefix *hyper* indicates that the text expands beyond the traditional constraints of the written word.  Instead of reading documents from beginning to end, like I would read a book, someone going through hypertext can *browse*.  By clicking on links from one document to another, the user can navigate to whatever page they find the most interesting and varve their own unique path through the web.

Many modern websites provide rich user experiences, with features like embedded videos, animations, and interactivity, so it doesnt necessarily feel like you are just navigating from one HTML page to the next.  But despite all of the advances that have taken place with the growth of the web, at its core the web is still just a collection of hyperlinked documents.  

# Questions

**(Q):**  What other things can HTML links be set to?

**(A):**  Links in HTML can be set to several different things.

As covered in the exercise, links are mainly used to connect a webpage with other webpages. This can be done by setting the link to go to the URL of a specified site, like

```html
<a href="www.codecademy.com">Codecademy</a>
```

Links can also be set to link to documents and files, such as text, audio, video and image files. For example,

```html
<a href="www.example.com/image.svg">Image</a>
```

HTML links can also be set to a specific part of the same webpage, such as a section header. This can be done using the id attribute of an element, and using that id value preceded by a # as the value of the href attribute. For example, in the following code, clicking the “Main” text would make the browser jump to the section with the corresponding id value of "main".

```html
<a href="#main">Main</a>

<div id="main">
</div>
```

## Community Forums 

It is possible to find more questions and answers on this topic on the [Codecademy Community Forums](https://discuss.codecademy.com/t/faq-languages-for-web-development-hypertext-and-the-world-wide-web/372110) for this lesson.