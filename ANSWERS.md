## Questions

What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
default value for course text box is nil nothing.

Go to `localhost:3000/teachers` in your browser; why does this not work?
There are no routes that point to teachers


What type of request did your browser just perform?
POST

Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
http://localhost:3000/teachers

Why does `localhost:3000/teachers`work now?
routes post to teachers. the render 'shows' points to show.html.erb in views.
