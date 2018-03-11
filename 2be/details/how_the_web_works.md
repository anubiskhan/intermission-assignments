## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?  
    Your computer sends a get request to your router asking for www.example.com. Your router uses your modem to send that message to your ISP. Your ISP communicates that to www.example.com's ISP. That ISP sends that message to a www.example.com router via a modem. That router sends a message to the example server. At each step in this process the requisite IP addresses are collected and packaged atop one another. www.example.com then sends a message through the chain in reverse using the prepackaged IP addresses to find its way.  
1.  What does HTTP stand for?  
    Hypertext Transfer Protocol  
1. 	What protocol does the World Wide Web use?  
    Application Protocols Layer  
1. 	Each computer on the Internet is assigned an IP address, what does IP stand for?  
    Internet Protocol  
1. 	What does DNS stand for?  
  * A. Domain Name System
  * B. ~~Digital Number System~~
  * C. ~~Domain Number System~~
  * D. ~~Domain Name Service~~
  * E. ~~Digital Name Service~~
1. 	How are text domain names matched to their respective numeric IP addresses.  
    A DNS resolver takes in the domain name and uses servers controlled by the Internet Assigned Numbers Authority in order to, through many steps along they way, match the domain name string with an associated IP(and possibly a more geographically narrowed response). This allows your ISP to connect your client/router with the IP you wanted to go to using the given domain name.  
1. 	What is the client?
  * A. ~~A purchaser~~
  * B. ~~Internet shopping customer (Consumer)~~
  * C. ~~The software which requests information from a server (browser)~~
  * D. ~~The server to which a particular computer sends data~~
  * E. The computer which the IP address belongs to
1. 	What does URL stand for?  
    Uniform Resource Locator, a subclass of Uniform Resource Identifier. It is essentially a web address.  
1. 	What are protocols 
 * A. ~~The standardisation of IP addressess~~
 * B. ~~The DNS standard method for data transfer~~
 * C.	~~The standardised network address system ~~
 * D.	The standardised method for transferring data or documents over a network
 * E.	~~The standardised method for prioratising data or document storage over a network~~
1. What does DNS stand for?  
    Domain Name System.  
1. what is the `www` portion of a url?  
    A sub domain of the .example.com domain. It is just an additional specifier in the DNS.  
1. What is The markup language used for all web documents?  
    HTML, Hypertext Markup Language.  
1. What is the organization that monitors web technologies?  
    W3C, World Wide Web Consortium.  
1. What is the Protocol for transferring web documents on the Internet?  
    TCP, Transmission Control Protocol.  
1. What matches the domain names with numeric IP addresses?  
    A DNS resolver, typically via your ISP.  





