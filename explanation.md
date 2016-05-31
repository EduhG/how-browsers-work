#Introduction

What is the meaning of browser?
A web browser (commonly referred to as a browser) is a software application for retrieving, presenting and traversing information resources on the World Wide Web. An information resource is identified by a Uniform Resource Identifier (URI/URL) and may be a web page, image, video or other piece of content.

The main function of a browser is to present the web resource you choose, by requesting it from the server and displaying it in the browser window. The resource is usually an HTML document, but may also be a PDF, image, or some other type of content. The location of the resource is specified by the user using a URI (Uniform Resource Identifier).

In this tutorial we will see what happens when you type google.com in the address bar until you see the Google page on the browser screen.

#Structure of Browsers

This contains the main components of a browser. They Include:
  1. The user interface: this includes the address bar, back/forward button, bookmarking menu, etc. Every part of the browser display except the window where you see the requested page.
  2. The browser engine: marshals actions between the UI and the rendering engine.
    The rendering engine : responsible for displaying requested content. For example if the requested content is HTML, the rendering engine parses HTML and CSS, and displays the parsed content on the screen.
    Networking: for network calls such as HTTP requests, using different implementations for different platform behind a platform-independent interface.
    UI backend: used for drawing basic widgets like combo boxes and windows. This backend exposes a generic interface that is not platform specific. Underneath it uses operating system user interface methods.
    JavaScript interpreter. Used to parse and execute JavaScript code.
    Data storage. This is a persistence layer. The browser may need to save all sorts of data locally, such as cookies. Browsers also support storage mechanisms such as localStorage, IndexedDB, WebSQL and FileSystem.


#References

1. https://en.wikipedia.org/wiki/Web_browser
2. http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/
3. https://dzone.com/articles/how-browsers-work-behind
4. http://grosskurth.ca/papers/browser-refarch.pdf
