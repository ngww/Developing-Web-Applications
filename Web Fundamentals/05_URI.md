# URI
URI stands for Uniform Resource Identifier. It's a string of characters used to identify or locate a resource on the internet. URIs are commonly used in web development to reference web pages, files, API endpoints, and other resources. Here's a simplified explanation of URIs:

Think of URIs like addresses to different things:

1. URL (Uniform Resource Locator): A URL is a type of URI that specifies the address of a resource on the internet. It provides both the location and the means to access the resource. URLs often start with "http://" or "https://" and are commonly used to access web pages. For example, "https://www.example.com/index.html" is a URL that points to the "index.html" file on the "www.example.com" website.

2. URN (Uniform Resource Name): A URN is another type of URI that provides a unique name for a resource. Unlike URLs, URNs don't necessarily indicate how to access the resource; they simply serve as an identifier. For example, "urn:isbn:0-486-27557-4" is a URN that uniquely identifies a book by its ISBN number.

3. URI Components: URIs have different components that help identify the resource:

   - Scheme: The scheme is the protocol or the method used to access the resource. It's typically indicated at the beginning of the URI, such as "http://" or "ftp://".
   
   - Authority: The authority component specifies the domain name or IP address associated with the resource. For example, "www.example.com" in "http://www.example.com/index.html".
   
   - Path: The path represents the location of a specific resource on the server. It's separated from the authority component by a forward slash ("/"). For instance, "/index.html" in "http://www.example.com/index.html".
   
   - Query String: The query string is optional and appears after the path in a URI. It includes additional parameters for the resource, usually separated by an ampersand ("&") or a question mark ("?"). For example, "?page=2&sort=asc" can be used to filter and sort data.
   
   - Fragment: The fragment is also optional and comes after a hash symbol ("#"). It refers to a specific section within a resource, like an anchor link on a web page. For instance, "#section3" in "https://www.example.com/page.html#section3".

URIs allow us to uniquely identify and access resources on the internet. Understanding how to read and construct URIs is essential for navigating the web and building web applications that interact with various resources.