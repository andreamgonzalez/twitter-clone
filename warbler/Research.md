-How is the logged in user being kept track of?
--Using flask g object, similar to how we would use the session.

-What is Flask’s g object?
--G is basically an object that stores theb app context. G is refreshed when a request is initiated and remains available until it ends.

-What is the purpose of add_user_to_g?
--It basically assigns g the value of the current apps context so that we can reference it it later using g, like one would with a variable assigned a value to it.

-What does @app.before_request mean?
--This decorator allows us to execute a function before any request.