# Getting-started-with-webpack
Understanding the Moving Parts of Webpack - Tutorial

Thanks to Resources:

http://blog.andrewray.me/webpack-when-to-use-and-why/

Before Webpack came into the picture, We used different ways to bundle the webapp ??

 # What is a Bundle ??
A group of js files and CSS files that go together to make a web page is considered a bundle. Usually a single web page will have one bundle so it is downloaded only when user requests for new page thus keeping the number of http requests low.

user clicks on page one, bundle(JS and CSS) and assets(Images) corresponding to this page is downloaded and so on. thus avoiding to download whole bundle at once. 

Webpack does this in a smarter way. at Webpack Everything is a bundle. .pngs are al made into ne bundle, .js are into ne bundle and .css are in one bundle asn so on . and again everything bundled together as a single bundle.

(webpack has plugins that can take various version of css like sass less and tranpile to css)

webpack will will download only necessary bundles to view the web page. 

This video here helps to learn more about the webpack and its configuration 

https://youtu.be/4qpXnIAZ9Dk?t=374


  
