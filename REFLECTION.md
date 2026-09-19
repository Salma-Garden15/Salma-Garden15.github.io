Homework 1 Reflection

Describe the path an HTTP Request takes from a browser to your GitHub Pages site.

When a user enters my GitHub Pages URL, the browser uses DNS to find the IP address of the server hosting the website. The browser then connects to the GitHub Pages server and sends an HTTP request asking for the page. The server responds by sending back my index.html file. The browser reads the HTML and sends more HTTP requests for other files it needs, such as my style.css file and images. Once all the files are received, the browser uses the HTML for the structure and the CSS for the styling to display my website to the user.