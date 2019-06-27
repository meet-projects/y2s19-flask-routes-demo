# y2s19-flask-routes-demo

## Demo 1 - Basic Routing
Show how to manually edit the route in the URL and ask the students, how the python code determines which function to run. What if the app.route doesn't exist?

## Demo 2 - Routes and Templates
This is also useful review on templates.  How does hello.html template determine what `{{n}}` is?

## Demo 3 - Variable Routes
This is confusing, so make sure to ask lots of questions. Such as, why do we need to say that the variable `name` is a string? Would it be fine to make it an int? What if the user enters in a URL with a fake name?

## Demo 4 - URL building
With `url_for` you can either enter the function name or the app route. It's generally better practice to muse the function name, because the ap routes are more likely to change.
