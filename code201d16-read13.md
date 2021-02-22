#Local Storage 

- Web applications don't have a persistent local storage, unlike the native client applications in which the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state.

- Cookies are usually small text files, given ID tags that are stored on the computer's browser directory or program data subfolders. Cookies are created when the browser is used to visit a website that uses cookies to keep track of the user movements within the site, helping in resume where the user left off, remembering the registered login, theme selection, preferences, and other customization functions.

- Cookies are included with every HTTP request, which cause a slowing in the web application by needlessly transmitting the same data over and over and sending data unencrypted over the internet. Also, cookies are limited to about 4 KB of data, these reasons make cookies not a good option ,especially in cases where a lot of storage space is needed. 

- UserData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. 

- Local Shared Objects is a feature allows Flash objects to store up to 100 KB of data per domain. 

- Gears are an open source browser plugin aimed at providing additional capabilities in browsers, lunched by google in 2007. They can store unlimited amounts of data per domain in SQL database tables.

- Local Storage, DOM Storage, Web Storage or HTML5 Storage is a way for web pages to store named key/value pairs locally, within the client web browser.

![](https://slideplayer.com/slide/14890828/91/images/3/Example+%E2%80%93+Html5+localStorage.jpg)

- The named key in HTML5 Storage is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.

- The present condition of HTML5 Storage includes a new API which has been standardized and implemented across all major browsers, platforms, and devices. 

![](https://www.researchgate.net/profile/Azzam_Sleit/publication/320614525/figure/fig1/AS:553282116767744@1508924144633/Modern-Web-Application-Architecture-and-Running-Environments-20.png)