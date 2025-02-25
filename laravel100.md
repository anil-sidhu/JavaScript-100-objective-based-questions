# Lavavel-100-objective-based-questions

**1. What is the default database system used in Laravel?**
```php
A) PostgreSQL
B) MySQL
C) SQLite
D) MongoDB
```

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**2. Which command is used to create a new Laravel project?**
```php
A) composer new laravel
B) laravel new projectname
C) php artisan new projectname
D) composer create-project --prefer-dist laravel/laravel projectname
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B and D
</ul>
</details>

**3. Which method is used to redirect users in Laravel?**
```php
A) redirectTo()
B) redirect()->route()
C) routeRedirect()
D) redirect()->path()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
	
	The redirect()->route('route_name')
</ul>
</details>

**4. Which command is used to generate a new controller in Laravel?**
```php
A) php artisan create:controller
B) php artisan make:controller
C) php artisan generate:controller
D) php artisan controller:make
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
Example:- php artisan make:controller PostController
</ul>
</details>

**5. Which command is used to roll back the last database migration?**
```php
A) php artisan migrate:down
B) php artisan migrate:rollback
C) php artisan migrate:refresh
D) php artisan migrate:undo
```

<details>
	<summary><b>View Answer</b></summary>

<ul>
Answer: B
		
	If you have run a migration that creates a `users` table:
	php artisan migrate
	Then, to roll back the last migration batch, use:
 	php artisan migrate:rollback
 	php artisan migrate:rollback --step=2
</ul>
</details>

**6. Which method is used to define API routes in Laravel?**
```php
A) Route::get()
B) Route::apiResource()
C) Route::post()
D) Route::match()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
	
	Route::apiResource('users', PostController::class);
 	This single line will generate API routes for CRUD operations (index, store, show, update, and destroy) on the posts resource.


</ul>
</details>


**7. Which method is used in Eloquent to fetch the first record matching the query?**
```php
A) first()
B) get()
C) find()
D) whereFirst()
```

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
	
	$user = User::where('email', 'example@example.com')->first();

</ul>
</details>



**8. Which HTTP status code is returned when a Laravel route is not found?**
```php
A) 200
B) 403
C) 404
D) 500
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
	
	200: status code means "OK," indicating a successful request and that the page was loaded properly
 	403: "Forbidden" - means the server understands the request but is refusing access to the resource. 
  	404: "Not Found" - means the server couldn't find the requested page. 
   	500: "Internal Server Error" - indicates a problem on the server side preventing the request from being processed. 
 
</ul>
</details>

**9. Which directory in a Laravel application contains middleware?**
```
A) app/Providers
B) app/Middleware
C) app/Http/Middleware
D) routes/middleware
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**10. What is the role of middleware in Laravel?**
```
A) A type of database migration
B) A tool for managing views
C) A mechanism for filtering HTTP requests
D) A Laravel package for authentication
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>


**11. How to make middleware in Laravel?**
```
A) php artisan make:middleware MiddlewareName
B) php artisan middleware:MiddlewareName
C) php artisan middleware:MiddlewareName --make
D) php artisan middleware:make -- MiddlewareName
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
	
	php artisan make:middleware CheckAge
</ul>
</details>


**12. Which of the following is used to send emails in Laravel?**
```
A) Notification
B) Mail
C) Queue
D) Event
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
	
	In Laravel, the Mail facade is used to send emails. Laravel provides a built-in mail system that allows you to send emails using various drivers such as SMTP, Mailgun, Postmark, Amazon SES,
</ul>
</details>

**13. What is the purpose of the php artisan optimize command?**
```php
A) Clears the cache and re-compiles classes for better performance
B) Optimizes the database queries
C) Deletes unnecessary files from the storage
D) Optimizes image assets
```

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
	
	The php artisan optimize command in Laravel is used to improve application performance by caching commonly used components.
 
 	This command:Compiles commonly used classes into a single file, reducing 	the need to autoload multiple files separately.	
 	Caches configuration files to avoid repeatedly loading and parsing them.
 	Caches routes to speed up route resolution.
</ul>
</details>

**14. Which method is used to retrieve the old input value in Laravel forms?**
```php
A) Input::old()
B) Session::previous()
C) old()
D) Form::getOld()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**15. Which method is used to soft delete a record in Laravel?**
```php
A) $model->remove();
B) $model->delete();
C) $model->softDelete();
D) $model->trash();
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
use Illuminate\Database\Eloquent\Model;
use Illuminate\Database\Eloquent\SoftDeletes;

class User extends Model
{
    use SoftDeletes;
}
</ul>
</details>



**16. What is the purpose of the php artisan route:cache command in Laravel?**

```php
A) Clears the cached routes
B) Caches and optimizes routes for faster performance
C) Generates route URLs dynamically
D) B and C
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
	
	Laravel provides a route caching mechanism to improve performance by compiling all routes into a single file. This cached file allows the application to load routes faster, reducing processing time.
</ul>
</details>

**17. What is the purpose of the php artisan route:clear command in Laravel?**

```php
A) Remove extra routes which is not getting used.
B) Clears the compiled route cache
C) Deletes all routes in web.php
D) Restores default routes
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
	
	The php artisan route:cache command generates a cached version of the routes.
</ul>
</details>

**18. Which API method is used for save operation  in Laravel?**
```php
A) save
B) insert
C) post
D) get
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

**19. What is Laravel?**
```php
A) A PHP framework where we can make API with php
B) A PHP framework for web development 
C) Full stack framwork
D) All of above 
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>


**20. What is the default templating engine in Laravel?**
```php
A) Twig
B) Blade
C) Smarty
D) Mustache
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

**21. Can we use Twig templating engine in Laravel?**
```php
A) Yes
B) Not
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
	
	The default template engine used in Symfony. Twig is fast, secure, and flexible. It has a sandbox mode to evaluate untrusted template code
</ul>
</details>

**22. Which file contains database connection settings in Laravel?**
```php
A) config/database.php
B) .env
C) database/config.php
D) settings.php
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
	
	DB_CONNECTION=mysql
 	DB_HOST=127.0.0.1
	DB_PORT=3306
	DB_DATABASE=laravel_db
	DB_USERNAME=root
	DB_PASSWORD=secret
</ul>
</details>

**23. Which command is used to start the Laravel development server?**
```php
A) php artisan serve
B) laravel run
C) php serve
D) composer serve
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>


**24. What is the default route file in Laravel?**
```php
A) routes.php
B) web.php
C) index.php
D) app.php
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
	
	web.php for web routes
	api.php for api routes
</ul>
</details>


**25. What method is used to define a GET route in Laravel?**
```php
A) Route::make()
B) Route::create()
C) Route::get()
D) Route::add()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
	
	Route::get()
 	Route::post()
  	Route::delete()
</ul>
</details>

**26. Which middleware is used for user authentication in Laravel?**
```php
A) auth
B) csrf
C) verifyUser
D) security
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
	auth is default authentication routes
</ul>
</details>


**27. Which file registers middleware in Laravel?**
```php
A) config/app.php
B) app/Http/Kernel.php
C) routes/middleware.php
D) middleware/kernel.php
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

Controllers & Requests


**28. What method is used to return a view in a controller?**
```php
A) return template('view_name')
B) return 'view_name'
C) return view('view_name)
D) return blade('view_name')
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**29. What is Blade template in laravel?**
```php
A) Blade is a frontend framework in Laravel
B) Blade is Laravel's built-in templating engine
C) Blade is a database query builder in Laravel
D) Blade is a third-party package for Laravel templates
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

**30. Which method is used to validate a request in Laravel?**
```php
A) $request->validate()
B) Validator::make()
C) validate($request)
D) Both A and B
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: D
	
	$request->validate() is a simple and commonly used method for request validation.
	Validator::make() allows for more complex validation scenarios, such as conditional rules or custom validation logic.
</ul>
</details>

**30. Print a variable in Blade template in laravel?**
```php
A) echo $variable;
B) {{ $variable }}
C) print($variable);
D) {{ echo $variable }}
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

**31. What command creates a new model in Laravel?**
```php
A) php artisan make:model ModelName
B) php artisan create:model ModelName
C) php artisan model:make ModelName
D) php artisan generate:model ModelName
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**32. How do you retrieve all records from a model?**
```php
A) Model::all()
B) Model::getAll()
C) Model::fetch()
D) Model::retrieve()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**33. Which method finds a record by primary key in Eloquent?**
```php
A) firat()
B) find()
C) where()
D) search()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>



**34. What Laravel feature prevents SQL injection?**
```php
A) Middleware
B) CSRF tokens
C) Query Builder
D) Eloquent ORM (prepared statements)
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: D
	
	SQL injection is a code injection technique that might destroy or make unwanted changes your database.
</ul>
</details>

**35. How do you generate a new application key in Laravel?**
```php
A) php artisan key:generate
B) php artisan generate:key
C) php artisan make:key
D) php artisan new:key
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
	
	primarily used for encrypting and decrypting sensitive data within your application
</ul>
</details>

**36. What command is used to create a job in Laravel?**
```php
A) php artisan create:job JobName
B) php artisan make:job JobName
C) php artisan job:make JobName
D) php artisan generate:job JobName
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
	
	Jobs are used to handle tasks that should be executed in the background
</ul>
</details>


**37. Which database driver is used for Laravel queue?**
```PHP
A) MySQL
B) Redis
C) Beanstalkd
D) All of the above
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: D
</ul>
</details>

**38. How do you extend a layout in Blade?**
```php
A) @extend('layout')
B) @layout('main')
C) @extends('layout')
D) @include('layout')
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
	
	blade layouts are used to create a consistent structure for web pages
</ul>
</details>

**39. How do you include another Blade view inside a template?**
```php
A) @import('viewname')
B) @include('viewname')
C) @use('viewname')
D) @render('viewname')
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
	
	we include blade view to reuse functionality 
</ul>
</details>

**40. What syntax is used to for loop Blade template laravel?**
```php
A) @foreach ($items as $item)
B) @for ($i = 0; $i < 10; $i++)
C) @while ($condition)
D) @if ($condition)
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
	
	@for ($i = 0; $i < 5; $i++)
    		<p>Iteration {{ $i }}</p>
	@endfor
</ul>
</details>

**41. How do you create a Blade component?**
```php
A) php artisan make:component ComponentName
B) php artisan create:component ComponentName
C) php artisan component:make ComponentName
D) php artisan new:component ComponentName
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
		
	define reusable UI elements and layouts in Blade template
</ul>
</details>

**42. What directive is used to check if a section exists?**
```php
A) @hasSection('sectionname')
B) @ifSection('sectionname')
C) @isset('sectionname')
D) @sectionExists('sectionname')
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
	
	The @section directive in a Laravel Blade file is used to define a section of content
</ul>
</details>



**43. What Laravel package is used for file storage?**
```php
A) Filesystem
B) Storage
C) FileManager
D) LaravelFile
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**44. How do you store a file using Laravel's Storage facade?**
```php
A) Storage::put('path/file.txt', 'content');
B) File::save('path/file.txt', 'content');
C) Storage::store('path/file.txt', 'content');
D) FileManager::put('path/file.txt', 'content');
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>


**45. How do you return a JSON response in Laravel?**
```php
A) return json_encode($data);
B) return response()->json($data);
C) return JsonResponse::make($data);
D) echo json($data);
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

**46. Which middleware is used for API authentication in Laravel?**
```php
A) apiAuth
B) auth:api
C) passport
D) sanctum
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: D
</ul>
</details>

**47. How do you define an API route in Laravel?**
```
A) Route::get('/api/data', 'Controller@method');
B) Route::apiResource('resource', 'Controller');
C) Route::get('/data', 'Controller@method')->middleware('api');
D) All of the above
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: D
</ul>
</details>


**48. What framework does Laravel use for testing?**
```php
A) PHPUnit
B) Jest
C) Mocha
D) Selenium
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**49. What command clears the application cache?**
```php
A) php artisan cache:clear
B) php artisan clear:cache
C) php artisan app:cache
D) php artisan refresh:cache
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
	
	This command is used for clear all cache such as routes, view etc
</ul>
</details>


**50. How do you create a custom helper function in Laravel?**
```php
A) Define it in helpers.php and include it in composer.json
B) Create a Service Provider
C) Use a Blade directive
D) Define it in web.php
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**51. What is a named route in Laravel??**
```php
A) A route that uses the GET method only
B) A route that is assigned a unique name for easier URL generation and redirection
C) A route that requires authentication before access
D) A route that dynamically generates URLs based on user input
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
		
	A named route in Laravel is a way to assign a name to a specific route, making it easier to generate URLs or redirects dynamically.
</ul>
</details>

**52. What method is used to define a named route in Laravel?**
```php
A) Route::name()
B) Route::alias()
C) Route::get()->name()
D) Route::define()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**53.What is the purpose of CSRF protection in Laravel?**
```php
A) Prevent SQL Injection
B) Prevent Cross-Site Scripting (XSS)
C) Prevent Cross-Site Request Forgery (CSRF)
D) Prevent Session Hijacking
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
	
	web attack that tricks a user into performing unwanted actions on a website. 
</ul>
</details>


**54. What command is used to list all registered routes?**
```php
A) php artisan route:list
B) php artisan routes
C) php artisan show:routes
D) php artisan list:routes
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**55. Which middleware is used for verifying email in Laravel authentication?**
```php
A) verified
B) checkEmail
C) emailAuth
D) verifyEmail
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
	
	Illuminate\Auth\Middleware\EnsureEmailIsVerified

	 if (! $request->user() || ! $request->user()->hasVerifiedEmail()) {
	    return redirect()->route('verification.notice');
	}
</ul>
</details>

**56. What is the default database engine in Laravel?**
```php
A) MySQL
B) SQLite
C) PostgreSQL
D) None (Configurable)
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: D
</ul>
</details>


**57. How do you specify a custom primary key in Eloquent?**
```php
A) Define $primaryKey in the model
B) Use setPrimaryKey() method
C) Define a custom index in migration
D) Use primaryColumn() in model
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**58. What method updates a record in Laravel Eloquent?**
```php
A) save()
B) update()
C) modify()
D) edit()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
	
	$user = User::find(1);  // Find the user with ID 1
	$user->update([
    'name' => 'John Doe',
    'email' => 'johndoe@example.com'
	]);
</ul>
</details>

**59. What is the purpose of Laravel’s timestamps property in a model?**
```php
A) Enables created_at and updated_at columns
B) Stores UNIX timestamps
C) Disables automatic timestamps
D) Tracks session timestamps
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
	
	class Post extends Model
	{
    public $timestamps = false;
	}
</ul>
</details>

**60. Which method is used to delete a record in Eloquent?**
```php
A) remove()
B) delete()
C) erase()
D) destroy()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
	
	$user = User::find(1); // Find the user with ID 1
	$user->delete(); // Delete the user
</ul>
</details>

**61. What is the purpose of Laravel Horizon?**
```php
A) Manage task scheduling
B) Monitor and manage Redis queues
C) API rate limiting
D) Debug Laravel applications
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
			
	Laravel Horizon is a tool within the Laravel framework designed to monitor and manage background job queues
</ul>
</details>

**62. What is the purpose of dd() function in Laravel?**
```php
A) Debug and die
B) Display database queries
C) Delete database records
D) Define default values
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
		
	$data = ['name' => 'John', 'email' => 'john@example.com'];
	dd($data);
</ul>
</details>

**63. What tool does Laravel use for debugging?**
```php
A) Laravel Debugbar
B) Telescope
C) Xdebug
D) All of the above
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: D
</ul>
</details>

**64. What hashing algorithm does Laravel use by default?**
```php
A) MD5
B) SHA-256
C) Bcrypt
D) AES-256
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
	
	use Illuminate\Support\Facades\Hash;
	$hashedPassword = Hash::make('secret');
 
	'default' => 'argon2id', // Change 'bcrypt' to 'argon2id' if desired

</ul>
</details>

**65. How do you hash a password in Laravel?**
```php
A) Hash::make('password');
B) encrypt('password');
C) password_hash('password');
D) Hash::encrypt('password');
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>


**66. How do you enable API authentication in Laravel?**
```php
A) Laravel Passport
B) Laravel Sanctum
C) Laravel JWT
D) All of the above
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: D
</ul>
</details>

**67. What is Laravel Mix?**
```php
A) A tool for managing assets (CSS, JS)
B) A Laravel package manager
C) A database migration tool
D) A job scheduler
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>


**68. How do you enable Laravel's maintenance mode?**
```php
A) php artisan down
B) php artisan maintenance:on
C) php artisan disable:app
D) php artisan site:down
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**69. How do you exit maintenance mode?**
```php
A) php artisan up
B) php artisan maintenance:off
C) php artisan enable:app
D) php artisan site:up
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**70. What command optimizes class loading in Laravel?**
```php
A) php artisan optimize
B) php artisan cache:clear
C) php artisan optimize:classmap
D) php artisan clear-compiled
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
	
	analyzes and modifies code to improve its performance
</ul>
</details>

**71. What is Laravel Livewire?**
```php
a) A front-end JavaScript framework
b) A package for real-time applications using WebSockets
c) A full-stack framework for building dynamic interfaces with PHP
d) A Laravel authentication system
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>


**72. What is the difference between first() and find() in Eloquent?**
```php
a) first() retrieves a model by primary key, while find() retrieves the first record matching a query
b) first() retrieves the first record matching a query, while find() retrieves a model by primary key
c) first() and find() function the same way
d) find() returns a collection, while first() returns a single model
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>


**73. What is the difference between soft deletes and hard deletes?**
```php
a) Soft deletes permanently remove records, while hard deletes mark them as deleted
b) Soft deletes move records to a backup table, while hard deletes remove them permanently
c) Soft deletes mark records as deleted without removing them, while hard deletes permanently delete records
d) There is no difference between soft deletes and hard deletes
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**74. What is Laravel’s Broadcasting feature used for?**
```php
a) Sending email notifications
b) Real-time event broadcasting using WebSockets
c) Uploading media files
d) Scheduling background jobs
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: b
</ul>
</details>

**75. What is the difference between groupBy() and chunk() in Eloquent?**
```php
a) groupBy() groups records based on a column, while chunk() retrieves records in smaller portions
b) chunk() groups records, while groupBy() retrieves them in batches
c) Both perform the same function
d) groupBy() is only used for caching data
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**76. what is mutator in laravel?**
```php
a) In Laravel, a mutator is a method defined in an Eloquent model that manipulates the value of a column before it is saved. 
b) Mutators in Laravel allow automatic data transformation when setting attributes in an Eloquent model.
c) A mutator in Laravel is a function that alters the format of model attributes before persisting them to the database.
d) A mutator in Laravel is a method used to modify an attribute before saving it to the database.
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: D
</ul>
</details>


**77. How do you encrypt and decrypt data in Laravel?**
```php
a) Using Crypt::encrypt() and Crypt::decrypt()
b) Using Hash::make() and Hash::check()
c) Storing data as base64 strings
d) Using the secure() helper function
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**78. What is the default session driver in Laravel?**
```php
A) array
B) cookie
C) database
D) file
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: D
</ul>
</details>

**79. Which method is used to retrieve a configuration value in Laravel?**
```php
A) Config::get()
B) config()
C) Configuration::get()
D) getConfig()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

**80. Which command is used to run database migrations in Laravel?**
```php
A) php artisan migrate
B) php artisan db:migrate
C) php artisan make:migration
D) php artisan migrate:run
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**81. Which method is used to define a route that responds to multiple HTTP verbs in Laravel?**
```php
A) Route::any()
B) Route::match()
C) Route::all()
D) Route::multi()
```

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>


**82. In Laravel, what does the nullable validation rule indicate?**
```php
A) The field must be null
B) The field is optional and can be null
C) The field cannot be null
D) The field must have a default value
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
	
	$request->validate([
    'email' => 'nullable|email', // Email can be null, but if present, must be valid
	]);
</ul>
</details>

**83. What is the purpose of the php artisan config:cache command in Laravel?**
```php
A) Clears all cached views and routes
B) Caches the configuration files for faster performance
C) Removes all cache files from the storage
D) Clears session and application cache
```

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>


**84. Which file in Laravel contains the application’s main configuration settings?**
```php
A) .env
B) config/app.php
C) routes/web.php
D) bootstrap/app.php
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

**85. Which of the following statements correctly describes the use of the any route method in Laravel?**
```php
A) The any method is used to define a route that responds to all HTTP request methods.
B) The any method only allows GET and POST requests.
C) The any method is used for defining API routes exclusively.
D) The any method automatically applies middleware authentication.
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**86. How can you pass data to a view from a controller in Laravel?**
```php
A) Use the compact() function to pass an array of data to the view.
B) Use the with() method to attach variables to the view.
C) Use the view() helper function and pass data as an associative array.
D) All of the above.
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: D
</ul>
</details>

**87. What is an accessor in Laravel?**
```php
A) An accessor in Laravel is a method used to modify an attribute before saving it to the database.
B) An accessor in Laravel is a method used to transform an Eloquent attribute when retrieving it from the database.
C) An accessor in Laravel is a built-in function to access private properties of a model.
D) An accessor in Laravel is a middleware used for authentication.
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

**88. Which primary design pattern does Laravel follow?**
```php
A) Singleton Pattern
B) Observer Pattern 
C) Model-View-Controller (MVC) Pattern
D) Strategy Pattern
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**89. Does Laravel follow the object-oriented approach?**
```php
A) Yes
B) No
C) Depand on developer
D) A and C
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**90. All dependencies are specified in the ____ file, which is located in the source folder??**
```php
A) laravel.json
B) composer.json
C) package.json
D) config.json
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>


**91. What is the primary purpose of using views in Laravel?**
```php
A) To store business logic
B) To handle database queries
C) To separate the presentation layer from business logic
D) To define routes

```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**91. What is the primary purpose of using views in Laravel?**
```php
A) To store business logic
B) To handle database queries
C) To separate the presentation layer from business logic
D) To define routes

```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**92. Rest API method name?**
```php
A) GET
B) POST
C) PUT and Patch
D) All of above

```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: D
</ul>
</details>


**93. What is database seeding in Laravel?**
```php
A) The process of creating database migrations
B) The process of populating the database with sample data
C) The process of encrypting database records
D) The process of deleting database records

```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>


**94. What is database seeding in Laravel?**
```php
A) The process of creating database migrations
B) The process of populating the database with sample data
C) The process of encrypting database records
D) The process of deleting database records

```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>



**95. Can you use raw PHP tags (<?php ... ?>) inside a Laravel Blade template?**
```php
A) Yes, but it is discouraged
B) No, it is not allowed
C) Yes, and it is the recommended way
D) Only inside JavaScript blocks

```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>


**96. What is the purpose of a controller in Laravel?**
```php
A) To manage database migrations
B) To handle HTTP requests and responses
C) To define application routes
D) To create Blade templates

```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>



**97. What is the primary purpose of sessions in Laravel?**
```php
A) Storing temporary data across multiple requests
B) Managing database connections
C) Handling Blade templates
D) Encrypting user passwords

```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>



**98. What is the purpose of a flash session in Laravel?**
```php
A) To store data permanently in the session
B) To store data temporarily for the next request only
C) To store data for multiple requests
D) To store data in the database

```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

**99. How many main types of middleware exist in Laravel?**
```php
A) 1
B) 2
C) 3
D) 4

```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>


**100. Which middleware is applied to all HTTP requests in Laravel?**
```php
A) Route Middleware
B) API Middleware
C) Global Middleware
D) Web Middleware

```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>









