##Introduction
**What is the meaning of browser?**<br>
A web browser (commonly referred to as a browser) is a software application for retrieving, presenting and traversing information resources on the World Wide Web. An information resource is identified by a Uniform Resource Identifier (URI/URL) and may be a web page, image, video or other piece of content.

The main function of a browser is to present the web resource you choose, by requesting it from the server and displaying it in the browser window. The resource is usually an HTML document, but may also be a PDF, image, or some other type of content. The location of the resource is specified by the user using a URI (Uniform Resource Identifier).

In this tutorial we will see what happens when you type google.com in the address bar until you see the Google page on the browser screen.

##Structure of Browsers
This contains the main components of a browser. They Include:<br>
1. _**The user interface:**_ This includes the address bar, back/forward button, bookmarking menu, etc. Every part of the browser display except the window where you see the requested page.
2. _**The browser engine:**_ Marshals actions between the UI and the rendering engine.
3. _**The rendering engine:**_ It is responsible for displaying requested content. For example if the requested content is HTML, the rendering engine parses HTML and CSS, and displays the parsed content on the screen.
4. _**Networking:**_ Used for network calls such as HTTP requests, using different implementations for different platform behind a platform-independent interface.
5. _**UI backend:**_ Used for drawing basic widgets like combo boxes and windows. This backend exposes a generic interface that is not platform specific. Underneath it uses operating system user interface methods.
6. _**JavaScript interpreter:**_ Used to parse and execute JavaScript code.
7. _**Data storage:**_ This is a persistence layer. The browser may need to save all sorts of data locally, such as cookies. Browsers also support storage mechanisms such as localStorage, IndexedDB, WebSQL and FileSystem.

<br>
    <br>
    <br>
    <br>
    <br>
    <br>
    

1. **The User Interface**
Browser user interfaces have a lot in common with each other. Among the common user interface elements are:
1. Address bar for inserting a URI
2. Back and forward buttons
3. Bookmarking options
4. Refresh and stop buttons for refreshing or stopping the loading of current documents
5. Home button that takes you to your home page

2. **The Browser Engine**

3. **The Rendering Engine**

4. **Networking**

5. **UI Backend**

6. **JavaScript Interpreter**

7. **Data storage**

##References
1. https://en.wikipedia.org/wiki/Web_browser
2. http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/
3. https://dzone.com/articles/how-browsers-work-behind
4. http://grosskurth.ca/papers/browser-refarch.pdf
