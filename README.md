# Performance-of-Web-page
Ways to speed up the website 

## 1.Minimize HTTP Requests
    Web page load time is spend on downloading resources like images, stylesheets, scripts, templates, etc. 
    An HTTP request is made for each one of these elements. There is a limit of parallel request browser can send per domain.
    Quickest way to improve site speed
      * Streamline the number of elements on your page
      * Uses CSS instead of images
      * Minification and Concatenation
      * Reduce scripts and put them at the bottom of the page
      * User async and defer keywords
## 2.Reduce Server response time
    Target for a server response time of less than 200ms
## 3.Compression (Gzip)      
    Compression reduces the bandwidth of the pages, hereby reducing the HTTP response. 
    web developers don't need to implement compression mechanisms, both browsers and servers have it implemented already  but they have to be sure that the server is configured adequately.
## 4.Enable browser caching
     Set the cache policy for cacheable resources  i.e JS, CSS, images, pdf, etc
## 5.Minify Resources
     Minify the HTML and CSS to reduce the size of the files.
     Tools: Pagespeed Chrome plugin, YUI Compressor, Closure Compiler, etc
## 6.Optimize images
    Prefer JPED over PNG, GIF, etc
    Resize the images based on the client type supported.
    Always include the src attribute with a valid URL.When there’s no source in the quotation marks, the browser makes a request to the directory of the page or to the actual page itself. 
## 7.Optimize CSS Delivery
    Avoid including CSS in HTML code, such as divs or your headings i.e inline style
    Ue one external CSS stylesheet since additional stylesheets increase HTTP requests
## 8.Prioritize above-the-fold content
   You can improve user experience by having your above-the-fold (top of the page) load faster—even if the rest of the page takes a few seconds to load.
   Consider splitting your CSS into two parts: a short inline part that styles above-the-fold elements, and an external part that can be deferred.
## 9.Reduce the number of plugins you use on your site
## 10.Reduce redirects
   Redirects create additional HTTP requests and increase load time. So you want to keep them to a minimum.
## 11.Prefer HTTP2 over HTTP1.1

Tools:
    Chrome Developer Tools, YSlow, Chrome's Built-In Task Manager, Fiddler, Chrome Lighthouse, Page speed,

Reference
https://www.crazyegg.com/blog/speed-up-your-website/

