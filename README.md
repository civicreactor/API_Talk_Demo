


GET:
curl -i http://localhost:5000/todo/api/v1.0/tasks
curl -i http://localhost:5000/todo/api/v1.0/tasks/3

POST (Add):
curl -i -H "Content-Type: application/json" -X POST -d 
'{"title":"Read a book", "Desc":"Info slot"}' http://localhost:5000/todo/api/v1.0/tasks