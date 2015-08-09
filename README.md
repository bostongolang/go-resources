go-resources
============
#####Introductory materials
* [A Tour of Go](http://tour.golang.org), an interactive tutorial on learning Go from scratch. It's easy to follow and especially useful as a quick way to get started in Go from C++.
* [How To Write Go Code](https://golang.org/doc/code.html), A guide to installing Go properly, organizing Go code, and a quick introduction to testing your code.
* [Effective Go](https://golang.org/doc/effective_go.html), A guide to writing idiomatic Go code
* [Resources for new Go programmers](http://dave.cheney.net/resources-for-new-go-programmers), A list of great introductory materials both on and off Go's official website.
* [What are the use(s) for tags in Go?](http://stackoverflow.com/questions/10858787/what-are-the-uses-for-tags-in-go), A StackOverflow question that clarifies what's up with struct tags.
* [json package godoc](http://golang.org/pkg/encoding/json/) Go's JSON package.  Look at the Marshal function to hear about how JSON struct tags are used.

#####Go's standard HTTP package and basic web development concepts
* [http package godoc](http://golang.org/pkg/net/http/) The documentation for the HTTP package in Go
* [Writing Web Applications](https://golang.org/doc/articles/wiki/) Write a web application using Go's http package and no frameworks
* [A Recap of Request Handling in Go](http://www.alexedwards.net/blog/a-recap-of-request-handling) Takes a closer look at the http library's big data structures, Handlers and ServeMuxes, a must-know concept for more advanced stuff like adding middleware to no-frameworks Go web apps
* [From Node.js to Go, Why One Startup Made the Switch](http://thenewstack.io/from-node-js-to-go-why-one-startup-made-the-switch/) A talk from Gophercon 2014 on what it was like moving from Node.js to Go for a startup (not really a tutorial but awesome for hearing about Go in the real world)
* [Go/Gorilla for MEAN Stack developers part 1: HTTP routing](http://csfortheslothful.blogspot.com/2015/01/gogorilla-for-mean-stack-developers.html) A tutorial on Go/Gorilla routing for people learning Go web development from Node.js
* [Basic extension of Go's HTTP Handlers](https://simonsdotnet.wordpress.com/2014/09/06/extending-gos-http-handlers/) A clever workaround for making no-frameworks net/http handler functions with extra functionality

####Go HTTP middleware concepts
* [Alice - Painless Middleware Chaining for Go](https://justinas.org/alice-painless-middleware-chaining-for-go/) An introduction to the [Alice](https://github.com/justinas/alice) library, which gives you middleware chaining that feels a lot like working with middleware in Express.js
* [Making and Using HTTP Middleware](http://www.alexedwards.net/blog/making-and-using-middleware) Learn how to add middleware to your HTTP server like in Express.js
* [Writing HTTP Middleware in Go](https://justinas.org/writing-http-middleware-in-go/) Another great tutorial on middleware for Go web servers
* [Go/Gorilla for MEAN Stack developers part 2: Handlers and middleware](http://csfortheslothful.blogspot.com/2015/02/gogorilla-for-mean-stack-developers.html)

####Go testing
* [Boston Golang - Testing](https://www.youtube.com/watch?v=v_wz6E3uFRg)
* [Codeship - Testing in Go](https://blog.codeship.com/testing-in-go/)
* [Testing Web Apps in Go](http://www.markjberger.com/testing-web-apps-in-golang/)
* [Mocking HTTP Responses in Golang](http://keighl.com/post/mocking-http-responses-in-golang/)
* [An Introduction To Programming in Go - Testing](https://www.golang-book.com/books/intro/12)
