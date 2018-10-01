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

First, your browser and OS determine if they know the IP address already (checks the memory cache). Then, your OS is configured to ask a Resolving Name Server (RNS) for IP addresses it doesnt know. So the OS queries the RNS, and the only thing the RNS should and needs to know is where to find the
root name server. If the RNS doesnt know example.come, it goes to the Root Name Server. If the Root Name Server doesnt know, it directs the RNS to the Top Level Domain Name Servers (TLD name severs),
like COM TLD. The TLD knows where to find the example.com Authoritative Name Servers (when a Domain name is purchased, the Registrar is told which ANS that name should use, and the Registrar notifies the Registry). The RNS goes to the ANS, who supplies the IP address. The RNS puts this info in its cache and delivers it to the OS, who gives it to the browser, who makes a connection to the OP address requesting the web page or resource.

1.  What does HTTP stand for?

Hyper Text Transfer Protocol

1. 	What protocol does the World Wide Web use?

TCP/IP: Transmission Control Protocol/Internet Protocol - suite of protocols use to interconnect network devices.

HTML: simple markup language for describing hypertext pages.

HTTP: used by web browsers to communicate with web clients.

URLs: Uniform Resource Locators - used to specify links between docs.

1. 	Each computer on the Internet is assigned an IP address, what does IP stand for?

Internet Protocol

1. 	What does DNS stand for?

Domain Name System

1. 	How are text domain names matched to their respective numeric IP addresses.

Through the domain name system.

1. 	What is the client?

The software which requests information from a server (browser)

1. 	What does URL stand for?

Uniform Resource Locator

1. 	What are protocols

 The standardised method for transferring data or documents over a network

1. what is the `www` portion of a url?

Subdomain

1. What is The markup language used for all web documents?

HTML

1. What is the organization that monitors web technologies?

World Wide Web Consortium

1. What is the Protocol for transferring web documents on the Internet?

File Transfer Protocol
