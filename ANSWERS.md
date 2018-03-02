## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
It represents the value contained in the text field–we want it to be empty.

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
There is no route defined in routes.rb for a GET request to /teachers.

3. What type of request did your browser just perform?
GET

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
localhost:3000/teachers

5. Why does `localhost:3000/teachers` work now?
The form submits a POST request to teachers, which has a defined route in routes.rb.
