# web_intro

!SLIDE

# Be Technical

## msofaer@pivotallabs.com
## elizabeth.stark@stanford.edu

!SLIDE

# The Web
* Series of Tubes

!SLIDE
# Stuff people have installed
## http://installfest.heroku.com
* RVM
* git

!SLIDE
# Browser
* Make requests
* Render responses

!SLIDE
#HTML
* urbanposse.com
* command-option-i
* click on elements
* move your mouse around and see how the page lays out
* find the logo link
* see that the a tag points to /

!SLIDE
#Requests
* click on Network
* click on the logo
* click on the response
* Go to preview
* It's the same page!

!SLIDE

#HTTP
* URL
* Verb (GET for now)

!SLIDE
#Web Server
Computer that listens for HTTP requsts and returns HTML

!SLIDE
#Web Application
Software that decides what HTML to return for a request.

!SLIDE
#Today

We will build one.

!SLIDE
# And Also

Put it on the internet.

!SLIDE
# The simplest server

* Listens to GET /
* Returns "Hello"

!SLIDE
# Sounds like a start!

!SLIDE
#Things we need:

* github - Code storage and transport
* heroku - Web server
* sinatra - Web application framework

!SLIDE
#Web application framework

* Knows about HTTP so you don't have to
* Lets you create your application simply : this request -> that response

!SLIDE
# We create a repo

!SLIDE
# Our first volunteer
* we add her to the repo
* she clones it
* she creates a Gemfile
* she adds sinatra to it
* she commits and pushes

!SLIDE
# Our second volunteer
* we add her to the repo
* she clones it
* she creates the simplest possible Sinatra app
* she starts it and visits it
* she commits and pushes

!SLIDE
# Our third volunteer
* we add her to the repo
* she clones it
* we add her to the Heroku application
* she adds heroku to the gemfile
* she pushes the application to github and heroku
* we visit it

!SLIDE
# Our fourth volunteer
* we add her to the repo
* we add her to the Heroku application
* she clones it
* she adds another URL and response
* she pushes the application to github and heroku
* we visit it

!SLIDE
# URL parameters
http://lmgtfy.com?q=cookie

!SLIDE
# URL parameters in Sinatra
http://app.heroku.com?name=bob

``` ruby
get '/' do
  "Hello, #{params[:name]}"
end
```

!SLIDE
# Our fifth volunteer
* we add her to the repo
* we add her to the Heroku application
* she clones it
* she adds code that responds based on a parameter
* she pushes the application to github and heroku
* we visit it

!SLIDE
# Our sixth volunteer
* we add her to the repo
* we add her to the Heroku application
* she clones it
* she adds code that renders HTML that can generate a parameter
* she pushes the application to github and heroku
* we visit it

!SLIDE
# Everyone gets a chance to change the repo

!SLIDE
# Whiteboard
## People come with ideas
* narrow down to 3 or so
* talk about them all
* choose one

!SLIDE
# Tracker
Create a Tracker project and start brainstorming stories into it

!SLIDE
# Github
Make a new repo for the new project

!SLIDE
# Done for the day

!NOTES

 * Where do we go from here?

!SLIDE

# NEXT!!
