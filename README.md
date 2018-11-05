# TG-Pre-Work

## When we hit https://www.techtonicgroup.com/ what happens? Don’t focus too much on architecture (Monolithic, SOA, Microservices, etc.). Try to focus more on how the web functions.

How the Web Functions

The “web,” short for the “world wide web (www),” is a sub-set of the internet.  The internet is the interconnection of all computers in the world, and there are various internet protocols for the intercommunication of data and files between these computers.  Examples of early internet protocols are: FTP (File Transfer Protocol); SMTP (Simple Mail Transfer Protocol); IMAP (Internet Mail Access Protocol); and IRC (for chatting). Then, in 1989, HTTP (Hyper Text Transfer Protocol) was defined, invented and implemented along with HTML (Hyper Text Markup Language), and thus the web was born. The web refers to a subset of all the interconnection and intercommunication of data and files between computers, and is limited to the computer intercommunications of data and files using HTTP wherein the files being transferred meet HTML file specifications.

HTTP has also evolved into HTTPS which is a secured version of HTTP using encryption to protect information contained within communications from persons that would improperly snoop or intercept communications.  Encryption uses encryption keys, and that is another discussion. The web today uses both HTTP and HTTPS, but HTTPS is of course preferred whenever any sensitive, i.e. personal and private, data is to be sent.

HTML has also evolved overtime incorporating more and more features and functionalities, and now also supports and incorporates richer and richer (for example images, audio and video) data types for objects (or elements) with a “web page.” Currently, HTML5 is the standard, and browsers that support HTML5 should be backward compatible to support HTML files written for previous and more primitive HTML specifications.

The concept is that an HTML file represents a “web” page.  Somewhere a “server” computer holds the web page, i.e. HTML file.  When someone requests to see the web page, the server delivers the HTML file to the requester. The requester is called the “client” computer.

When a computer is turned on, it loads and begins running its operating system.  The operating system  can then in turn run software applications as requested by the user.  One type of application that can be run under an operating system is called a web browser (or just browser for short).  When a browser application is running, it can display a browser window, provided it has not been iconified.  There is a place within a browser window to specify a URL (Uniform Resource Locator).

The URL is the address of (or specifies) the HTML file to be displayed in the browser window. The URL has three parts: 1) Protocol (or scheme); 2) domain; and 3) path.  For example, consider the URL https://www.techtonicgroup.com:
1)	The https:// - is the protocol definition of the URL, and for web pages we are only concerned with https and http protocols;
2)	www.techtonicgroup.com – is the domain. The domain is associated with an IP address. That is, the domain correlates to a numeric IP address. A numeric IP address specifies the server computer that “hosts” the web site. For example: 91.198.174.192 is the IP address for the www.wikipedia.org domain. So, when a client computer specifies a server host with a domain, the domain is sent out into the Domain Name System (DNS) so that a correct IP address can be returned.  The DNS comprises a network of servers that store translations for domains to IP addresses. The DNS will successively ask various servers within its network until the correct IP address is located and returned.  A domain has three parts: 1) Top Level Domain (TLD), which is the portion including and after the “.” dot, for example .com, .org, .us, ect.; 2) domain name, which is the text with no “dots” or spaces, for example techtonicgroup or wikipedia; and 3) subdomain which is the “www.” Portion in the front of the domain name and is optional; and
3)	Path is also optional, and is a path to a lower level file within the hosting web site. For example: in the URL https://marksheet.io/afilename.html, the “/afilename.html” is the path to the file “afilename.html” which is one level below

Note that although a URL points to a single HTML file, that file likely specifies many other files that are needed together along with the HTML file and are called out by the HTML file to complete the web page.  For example, a <link> tag within an HTML file can specify a CSS file (Cascading Style Sheets) needed to coordinate and specify much of the styling, sizing, coloring, transparency and placement, ect. of many of the elements of the HTML file, thus affecting the appearance of the web page. Furthermore, JavaScript files for real time interactions with the viewer of the web page are needed as well and are often also called out by HTML files. Still further, hyper links to further web pages can be selected by the viewer of the web page, and the whole process begins again.

So, the user, through a browser application, specifies a valid URL, and then a hand shaking begins between them, the client, and the server computer delivering the HTML file and other files needed along with it to represent the web page in the client’s browser. This happens after the DNS converts the domain to an IP address, so that the server computer can be found in the network.

Files are not sent over the network from the server to the client as a single piece or single file, but rather, files are fragmented into packets, and the plurality of packets sent out individually, taking different paths through the network, and are then received and reassembled by the client browser.

The client browser renders and interprets the HTML, CSS, and JavaScript code to display the web page.  The server-side code’s main function is to fragment and send out the HTML, CSS and JavaScript files after identifying which files are requested and needed by the client, i.e., the server-side code must look into the HTML file to see what other files are linked or called out by it.

Cookies are small text files sent to the client browser from the server host.  Plug-ins are additional software, like an additional application that can be added to a web browser to perform a function within a box isolated and identified within the web page for the plug-in to execute code. For example, before browsers supported video, an Adobe Flash Player plug-in, could be added to the browser, and then a video clip played within a defined box of the web page. Plug-ins are less of a need, as the browsers and HTML5 specification becomes more rich in features and capabilities supporting greater date types.


## From start to finish how does that data reach you to be rendered in the browser?

put your answer here

## What code is rendered in the browser?

put your answer here

## What is the server-side code’s main function?

put your answer here

## What is the client-side code’s main function?

put your answer here

## How many instances of the client-side assets (HTML, CSS, JS, Images, etc.) are created?

put your answer here

## How many instances of the server-side code are available at any given time?

put your answer here

## What is runtime?

put your answer here

## How many instances of the the databases connected to the server application are created?

put your answer here
