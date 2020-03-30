# Learnings

* app.use() is a function made available by the express framework
* app.use() allows us to use a new middleware function
* app.use is executed for every incoming request and 
* app.use receives 3 arguments -> req, res, next
* next has to be executed in order for the code to progress to the succeeding middleware