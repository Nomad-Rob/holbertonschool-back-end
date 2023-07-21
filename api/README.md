Requirements
General
Allowed editors: vi, vim, emacs
All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.X)
All your files should end with a new line
The first line of all your files should be exactly #!/usr/bin/python3
Libraries imported in your Python files must be organized in alphabetical order
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the pycodestyle
All your files must be executable
The length of your files will be tested using wc
All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
You must use get to access to dictionary value by key (it won’t throw an exception if the key doesn’t exist in the dictionary)
Your code should not be executed when imported (by using if __name__ == "__main__":)


An application program interface (API) is a set of routines, protocols, and tools for building software applications. Basically, an API specifies how software components should interact. Additionally, APIs are used when programming graphical user interface (GUI) components. A good API makes it easier to develop a program by providing all the building blocks. A programmer then puts the blocks together.

There are many different types of APIs for operating systems, applications or websites. Windows, for example, has many API sets that are used by system hardware and applications — when you copy and paste text from one application to another, it is the API that allows that to work.

Most operating environments, such as MS-Windows, provide APIs, allowing programmers to write applications consistent with the operating environment. Today, APIs are also specified by websites. For example, Amazon or eBay APIs allow developers to use the existing retail infrastructure to create specialized web stores. Third-party software developers also use Web APIs to create software solutions for end-users.

REST was defined in 2000 by Roy Fielding and is considerably simpler than the others. It’s not a standard but a set of recommendations and constraints for RESTful web services. These include:

Client-Server: SystemA makes an HTTP request to a URL hosted by SystemB, which returns a response.It’s identical to how a browser works. A browser makes a request for a specific URL. The request is routed to a web server which typically returns an HTML page. That page may contain references to images, style sheets, and JavaScript, which incur further requests and responses.
Stateless: REST is stateless: the client request should contain all the information necessary to respond.In other words, it should be possible to make two or more HTTP requests in any order, and the same responses will be received (… unless the API was designed to return random responses such as the quiz example above).
Cacheable: A response should be defined as cacheable or not.Caching improves performance because it’s not necessary to regenerate a response for the same URL. Private data specific to a certain user at a certain time would not normally be cached.
Layered: The requesting client need not know whether it’s communicating with the actual server, a proxy, or any other intermediary.
