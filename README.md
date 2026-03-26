# Sun-Labs-Lively-Kernel
Lively Kernel is a Web-based live self-modifying runtime environment

<img width="500" height="327" alt="image" src="https://github.com/user-attachments/assets/968af477-7d97-433b-a12d-67d80d40d4cf" />

 Update (May 2, 2008): The latest development versions of the Lively Kernel are now available on http://livelykernel.sunlabs.com/. Refer to technical documentation for details.

Update (February 8, 2008): Version 0.8.1 of the Lively Kernel is now available. A new technical report is also available.

Introduction
The Sun Labs Lively Kernel is a new web programming environment developed at Sun Microsystems Laboratories. The Lively Kernel supports desktop-style applications with rich graphics and direct manipulation capabilities, but without the installation or upgrade hassles that conventional desktop applications have. The system is written entirely in the JavaScript programming language, a language supported by all the web browsers, with the intent that the system can run in commercial web browsers without installation or any plug-in components. The system leverages the dynamic characteristics of the JavaScript language to make it possible to create, modify and deploy applications on the fly, using tools built into the system itself. In addition to its application execution capabilities, the Lively Kernel can also function as an integrated development environment (IDE), making the whole system self-sufficient and able to improve and extend itself dynamically.

Motivation
The main goal of the Lively Kernel is to bring the same kind of simplicity, generality and flexibility to web programming that we have known in desktop programming for thirty years, but without the installation and upgrade hassles than conventional desktop applications have.

The Lively Kernel places a special emphasis on treating web applications as real applications, as opposed to the document-oriented nature of most web applications today. In general, we want to put programming into web development, as opposed to the current weaving of HTML, XML and CSS documents that is also sometimes referred to as programming.

A key difference between the Lively Kernel and other systems in the same area is our focus on uniformity. Our goal is to build a platform using a minimum number of underlying technologies. This is in contrast with many current web technologies that utilize a diverse array of technologies such as HTML, CSS, DOM, JavaScript, PHP, XML, and so on. In the Lively Kernel we attempt to do as much as possible using a single technology: JavaScript. We have chosen JavaScript primarily because of its ubiquitous availability in the web browsers today and because of its syntactic similarity to other highly popular languages such as C, C++ and Java. However, we also want to leverage the dynamic aspects of JavaScript, especially the ability to modify applications at runtime. Such capabilities are an essential ingredient in building a malleable web programming environment that allows applications to be developed interactively and collaboratively.
Infrastructure
The Lively Kernel runs in supported web browsers without installation or any plug-in components whatsoever. The system utilizes the JavaScript engine, graphics capabilities and asynchronous networking features that are already available in commercial web browsers today. In general, one of our goals has been to leverage existing technologies as much as possible.

A unique feature of the Lively Kernel is a graphics library called Morphic. Morphic is a user interface framework that supports composable graphical objects, along with the machinery required to display and animate these objects, handle user inputs, and manage underlying system resources such as displays, fonts and color maps. A key goal of Morphic is to make it easy to construct and edit interactive graphical objects, both by direct manipulation and from within programs. The Morphic user interface framework was originally developed for the Self system at Sun Labs, but it later became popular also as part of the Squeak Smalltalk programming environment. The Lively Kernel brings the flexibility and power of Morphic also to JavaScript developers and to web application development in general.

Main features
The main features of the Lively Kernel include:

    Small web programming environment and computing kernel, written entirely with JavaScript. In addition to its application execution capabilities, the platform can also function as an integrated development environment (IDE), making the whole system self-contained and able to improve and extend itself on the fly.
    Programmatic access to the user interface. Our system provides programmatic access from JavaScript to the user interface via the Morphic user interface framework. The user interface is built around an event-based programming model familiar to most web developers.
    Asynchronous networking. As in Ajax, you can use asynchronous HTTP to perform all the network operations asynchronously, without blocking the user interface.

What can you do with it?
The Lively Kernel allows you to do pretty much everything that you would expect to do in a conventional desktop programming environment. The main difference is that in the Lively Kernel everything takes place in a web browser.

Utilizing the features described above, you can build conventional, desktop-style applications that run on the web. Utilizing the capabilities of the Morphic user interface framework, you can also build desktop-like environments and systems in which numerous applications and widgets run simultaneously in a regular web browser.
How do I get it?
The Sun Labs Lively Kernel is alive on the web, meaning that you do not download it or install it. If your browser supports the Lively Kernel (see the list of supported web browsers below), then merely clicking on the Enter Lively Kernel link causes the system to come to life in your computer. You may see some static elements on the screen but, by default, everything there is alive and changeable.

Where is the source code or binaries?
The entirety of the Lively Kernel is written in JavaScript, a dynamic language that uses no binary files for execution. The Lively Kernel does not require any installation or plug-ins, since the necessary JavaScript engine is already part of your web browser. As soon as you click on a link to start the system, all the Lively Kernel code is loaded into your browser and running. At some point we may compress the files to make for faster startup but, if so, we will still make the full uncompressed sources available on this site.

For your convenience, we have made the source code available here as a ZIP file.
Supported web browsers
The Lively Kernel is intended to run in every commercial web browser client with no plug-ins or installation whatsoever. However, because of differences in the underlying graphics and other capabilities of various web browsers, we only support a limited set of browsers and browser versions. We have tested our system on Windows XP and MacOS using the following browsers:

    Safari 3 (recommended for best performance and quality of experience)
    Firefox 3 (still some bugs left)
    Firefox 2 (still various bugs left) 

The browsers above provide support for Scalable Vector Graphics (SVG), a graphics library that we use as the underlying low level graphics interface. The SVG interfaces are hidden from the application developer, but our implementation requires an SVG-compatible graphics engine. To end users and developers, the Lively Kernel is an environment that is based purely on JavaScript, not SVG.

IMPORTANT! The Lively Kernel requires SVG support and does not currently run on Microsoft Internet Explorer. We are hoping to have support for Microsoft Internet Explorer available soon.

Publications and Videos
The following research papers provide further information about the project and its background:

    Web Browser as an Application Platform: The Lively Kernel Experience
    Using JavaScript as a Real Programming Language
    Web Applications - Spaghetti Code for the 21st Century 

Videos:

    Lively Kernel talk at Google on January 24, 2008 

Contribute
Visit the forums to find out what people want and what they are working on. If you produce a bug fix or enhancement, post it on a forum to share it, and submit it to us to proffer it for inclusion in future releases.

Caution
The Sun Labs Lively Kernel is research software. It may be remarkable in various ways, but it is not production software. Rather, it is an experimental system for turning the web as we know it into a universe of objects that are active, accessible, changeable; in short, lively.

We are making the Lively Kernel available as open source software to encourage further exploration by academics and adventurous developers, and we anticipate rapid progress toward future versions of the system that are not only lively but also well-behaved.
Credits
The Sun Labs Lively Kernel is the result of a cooperation between four experienced software developers, all frustrated with the state of the web programming practice today:

    Dan Ingalls
    Tommi Mikkonen
    Krzysztof Palacz
    Antero Taivalsaari 

While developing the Lively Kernel, we have received help from various other people. We would especially like to thank Mikko Kuusipalo, Kristen McIntyre, Richard Ortiz, Pekka Reijula, and Stephen Uhler for their valuable contributions. We would also like to thank Linda Bohn and Mario Wolczko for their invaluable assistance during the project.

Intellectual heritage
The idea of the Lively Kernel was inspired in part by the success of the Squeak Smalltalk programming environment. In this regard, we owe a debt to all the people who designed that system. The specific choice of a Morphic-style graphics architecture was inspired by the simplicity of such an architecture manifested originally in the Self system and later in the Squeak system. For historical references, refer to the following documents:

    Directness and liveness in the Morphic user interface construction environment
    History of Morphic
