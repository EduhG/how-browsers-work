##Introduction
**What is the meaning of browser?**<br>

By the time you are reading this article, certainly you are already using a web browser which is presenting this article content in a rich text/graphical format on your computer or phone screen.

A web browser or frequently called as browser is an application software that is installed on a computer to provide access to the World Wide Web. It fetches the web pages from the server along with the necessary files like, images, flashes, videos etc, interprets them and then displays it on the screen. All you have to do is simply type the URL (Uniform Resource Locator) of a webpage in the address bar and the browser will bring the web page on your screen.

In this tutorial we will see what happens when you type google.com in the address bar until you see the Google page on the browser screen.

##Structure of Browsers
The browser’s main functionality is to fetch the files from the server and to display them on the screen. It basically displays html files containing images, PDF, videos, flashes, etc in an ordered layout. A browser is a group of structured codes that performs plenty of tasks to display a webpage on the screen. These codes are separated in to different components according to their tasks performed. The structure of a browser is shown in the below image.
![alt text](http://www.engineersgarage.com/sites/default/files/imagecache/Original/wysiwyg_imageupload/28714/Architecture-of-Web-Browser.gif "Structure of Browsers")


This contains the main components of a browser. They Include:<br>

**1. The User Interface**<br>
Browser user interfaces have a lot in common with each other. Among the common user interface elements are:
1. Address bar for inserting a URI
2. Back and forward buttons
3. Bookmarking options
4. Refresh and stop buttons for refreshing or stopping the loading of current documents
5. Home button that takes you to your home page

**2. The Browser Engine**<br>
A web browser engine (sometimes called layout engine or rendering engine) is a program that renders marked up content (such as HTML, XML, image files, etc.) and formatting information (such as CSS, XSL, etc.). It marshals actions between the UI and the rendering engine.<br>

**3. The Rendering Engine**<br>
It is responsible for displaying requested content. For example if the requested content is HTML, the rendering engine parses HTML and CSS, and displays the parsed content on the screen.<br>
By default the rendering engine can display HTML and XML documents and images. It can display other types of data via plug-ins or extension; for example, displaying PDF documents using a PDF viewer plug-in. However, in this chapter we will focus on the main use case: displaying HTML and images that are formatted using CSS.<br>

**4. Networking**<br>
Used for network calls such as HTTP requests, using different implementations for different platform behind a platform-independent interface.<br>

**5. UI Backend**<br>
Used for drawing basic widgets like combo boxes and windows. This backend exposes a generic interface that is not platform specific. Underneath it uses operating system user interface methods.<br>

**6. JavaScript Interpreter**<br>
Used to parse and execute JavaScript code.<br>

**7. Data storage**<br>
This is a persistence layer. The browser may need to save all sorts of data locally, such as cookies. Browsers also support storage mechanisms such as localStorage, IndexedDB, WebSQL and FileSystem.


##References
1. https://en.wikipedia.org/wiki/Web_browser
2. http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/
3. https://dzone.com/articles/how-browsers-work-behind
4. http://grosskurth.ca/papers/browser-refarch.pdf
5. https://en.wikipedia.org/wiki/Web_browser_engine
