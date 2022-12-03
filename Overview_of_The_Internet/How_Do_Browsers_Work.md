# How Browsers Work

So far I have seen how a single request and response are handled between a client and a server.  Most of the time however, devices are not making a single request.  Every time someone loads a webpage, their device sends a request for each file that makes up that page.  So even when they are just loading one webpage, that page can make multiple requests in order to retrieve different pieces of content.  

## How Does The Process Work

All of the following steps hapen in a split second

1. When a user types a URL and presses enter, the server processes the request and sends the HTML file back to the client.  *HTML* files hold the content of the website and they also contain links to any additional assets or code that are needed to display the site properly.
2. The browser will begin to search for elements in the HTML file and it will start to make additional HTTP requests for any other external resource used by the HTML file.  This often includes:
		* One or more CSS Stylesheets
		* Other assets such as images and videos
		* One or more JavaScript files

In most modern browsers, these additional requests are made in parallel - meaning that these requests are inititated at the same time, and the browser does not wait to receive one resource before requesting another. 

All of the requested resources are typically displayed as soon as possible.  The HTML will be displayed even if some of the other assets have not been received by the browser

**Note**: This behaviour can cause some badly coded sites to appear jittery to the user, and provide a poor user experience. 

The whole process typically takes about a second or less, depending on the speed of the user's connection and the size of the website, and even the physical distance between the browser and the server. 

### Webpages Made With Different Languages

The graphic on the right of [this lesson](https://www.codecademy.com/paths/front-end-engineer-career-path/tracks/fecp-22-overview-of-web-development/modules/wdcp-22-the-internet-and-web-development/lessons/what-is-the-internet/exercises/how-browsers-work) shows a simple example of what is possibel for webpages built with different language combinations.  

### Community Forums

Further questions and answers can be found in the [community forums for this lesson.](https://discuss.codecademy.com/t/faq-overview-of-the-internet-how-do-browsers-work/372074)