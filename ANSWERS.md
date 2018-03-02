## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?

That's the default text. Nil specifies that the field should start off empty (or with the placeholder text)

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
There is no route that handles GET requests to /teachers

3. What type of request did your browser just perform?


Trying to go to localhost:3000/teachers was a GET request. Submitting the form submitted a POST

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?

localhost:3000/teachers

5. Why does `localhost:3000/teachers` work now?

Because submitting the form used a POST request which is a route that the router was configured to handle
