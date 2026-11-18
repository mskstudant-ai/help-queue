Ex1
Q1
Ex2
1/Route::get('/', function () {return view('welcome');});
2/DB_CONNECTION=sqlite
3/migrations = 3
4/
Ex3
3.2/Hello from Laravel!
Question 2/not found
Ex4
Q3
http://localhost:8000/hello/samer --> Hello samer!
http://localhost:8000/hello/a/b -->not found 
car un seul paramètre `{name}`
Ex5
http://localhost:8000/hello/samer -->
Hello samer!
This page was built by a Blade view.
http://localhost:8000/hello/<marquee>EBob -->
Hello <marquee>Bob!
This page was built by a Blade view.
Q5 
 Columns: 7  
  Column: Type  
  id integer, autoincrement integer  
  name varchar varchar  
  topic varchar  varchar  
  description text, nullable text  
  status varchar  'waiting' varchar  
  created_at datetime, nullable  datetime  
  updated_at datetime, nullable  datetime 
Q6
   Illuminate\Database\Eloquent\MassAssignmentException  Add [name] to fillable property to allow mass assignment on [App\Models\Ticket].