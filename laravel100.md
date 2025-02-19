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

**2. Which command is used to roll back the last database migration?**
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
</ul>
</details>

**3. Which method is used in Eloquent to fetch the first record matching the query?**
```php
A) get()
B) first()
C) find()
D) whereFirst()
```

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>



**6. Which command is used to generate a new controller in Laravel?**
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
</ul>
</details>

**7. Which method is used to define API routes in Laravel?**
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

**10. Which of the following is used to send emails in Laravel?**
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
</ul>
</details>

**11. What is the purpose of the php artisan optimize command?**
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
	Explanation: The optimize command caches configuration and compiles commonly used classes to improve performance.
</ul>
</details>

**12. Which method is used to retrieve the old input value in Laravel forms?**
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
Explanation: The old('input_name') function retrieves the previous input value stored in the session.
</ul>
</details>

**13. Which method is used to soft delete a record in Laravel?**
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
Explanation: The delete() method soft deletes a record when the SoftDeletes trait is used in a model.
</ul>
</details>


**14. Which command is used to create a Laravel policy?**
```php
A) php artisan make:policy
B) php artisan create:policy
C) php artisan generate:policy
D) php artisan policy:make
```

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
Explanation: The delete() method soft deletes a record when the SoftDeletes trait is used in a model.
</ul>
</details>

**15. What is the purpose of the php artisan route:clear command in Laravel?**

```php
A) Clears the application cache
B) Clears the compiled route cache
C) Deletes all routes in web.php
D) Restores default routes
```

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

**16. Which API method is used for save operation  in Laravel?**
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



**1. What is Laravel?**
```php
A) A JavaScript framework
B) A PHP framework
C) A Python framework
D) A Ruby framework
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>


**2. Which command is used to create a new Laravel project?**
```php
A) laravel start
B) php artisan new
C) composer create-project
D) php new laravel
```

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**3. What is the default templating engine in Laravel?**
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

**4. Which file contains database connection settings in Laravel?**
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
</ul>
</details>

**5. Which command is used to start the Laravel development server?**
A) php artisan serve
B) laravel run
C) php serve
D) composer serve

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>


Routing & Middleware
**6. What is the default route file in Laravel?**
A) routes.php
B) web.php
C) index.php
D) app.php

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>


**7. What method is used to define a GET route in Laravel?**
A) Route::make()
B) Route::create()
C) Route::get()
D) Route::add()

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**8. Which middleware is used for user authentication in Laravel?**
A) auth
B) csrf
C) verifyUser
D) security
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>


**9. How do you define a middleware in Laravel?**
```php
A) php artisan make:middleware MiddlewareName
B) php artisan middleware:make MiddlewareName
C) php artisan create:middleware MiddlewareName
D) php artisan middleware:create MiddlewareName
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**10. Which file registers middleware in Laravel?**
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

**11. What command creates a new controller in Laravel?**
```php
A) php artisan make:controller ControllerName
B) php artisan create:controller ControllerName
C) php artisan controller:make ControllerName
D) php artisan controller:create ControllerName
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**12. What method is used to return a view in a controller?**
```php
A) return template()
B) return render()
C) return view()
D) return blade()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**13. Which method is used to validate a request in Laravel?**
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
</ul>
</details>

**14. What command creates a new model in Laravel?**
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

**15. How do you retrieve all records from a model?**
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

**16. Which method finds a record by primary key in Eloquent?**
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

**17. What command is used to create a migration?**
```php
A) php artisan migrate:make MigrationName
B) php artisan create:migration MigrationName
C) php artisan make:migration MigrationName
D) php artisan generate:migration MigrationName
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**18. How do you rollback the last migration?**
```php
A) php artisan migrate:rollback
B) php artisan migrate:reset
C) php artisan migrate:down
D) php artisan rollback:migration
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>


**19. Which database migration method is used to add a new column?**
```php
A) Schema::create()
B) Schema::addColumn()
C) Schema::table()
D) Schema::alter()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**20. What command is used to set up Laravel authentication?**
```php
A) php artisan make:auth
B) php artisan ui:auth
C) php artisan auth:setup
D) php artisan make:login
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

**21. What Laravel feature prevents SQL injection?**
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
</ul>
</details>

**22. How do you generate a new application key in Laravel?**
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
</ul>
</details>

**23. What command is used to create a job in Laravel?**
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
</ul>
</details>


**24. Which method dispatches a job in Laravel?**
```php
A) dispatch(new JobName)
B) JobName::run()
C) Queue::push(JobName)
D) Job::execute(JobName)
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>


**25. Which database driver is used for Laravel queue?**
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

**26. How do you extend a layout in Blade?**
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
</ul>
</details>

**27. How do you include another Blade view inside a template?**
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
</ul>
</details>

**28. What syntax is used to display a variable in Blade?**
```php
A) {{ $variable }}
B) <?php echo $variable; ?>
C) <% $variable %>
D) {!! $variable !!}
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**29. How do you create a Blade component?**
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
</ul>
</details>

**30. What directive is used to check if a section exists?**
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
</ul>
</details>

**31. How do you define a one-to-one relationship in Eloquent?**
```php
A) hasOne()
B) belongsTo()
C) hasMany()
D) hasOneThrough()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**32. What method defines a one-to-many relationship?**
```php
A) belongsTo()
B) hasMany()
C) hasOne()
D) manyToOne()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>


**33. What method is used to define a many-to-many relationship?**
```php
A) belongsToMany()
B) hasMany()
C) belongsTo()
D) hasManyThrough()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**34. What method is used to eager load relationships?**
```php
A) load()
B) eagerLoad()
C) with()
D) preload()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**35. What pivot table convention does Laravel use for many-to-many relationships?**
```php
A) Table1Table2
B) Table2Table1
C) table1_table2
D) Both A and C
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: D
</ul>
</details>


**36. How do you generate an event in Laravel?**
```php
A) php artisan make:event EventName
B) php artisan event:create EventName
C) php artisan event:generate EventName
D) php artisan make:listener EventName
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**37. What function is used to dispatch an event?**
```php
A) event(new EventName)
B) Event::fire(new EventName)
C) dispatch(new EventName)
D) trigger(new EventName)
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**38. How do you create an event listener?**
```php
A) php artisan make:listener ListenerName
B) php artisan listener:make ListenerName
C) php artisan create:listener ListenerName
D) php artisan generate:listener ListenerName
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>


**39. What Laravel package is used for file storage?**
```php
A) Flysystem
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

**40. How do you store a file using Laravel's Storage facade?**
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


**41. How do you return a JSON response in Laravel?**
```php
A) return response()->json($data);
B) return json_encode($data);
C) return JsonResponse::make($data);
D) echo json($data);
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>

**42. Which middleware is used for API authentication in Laravel?**
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

**43. How do you define an API route in Laravel?**
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


**44. What framework does Laravel use for testing?**
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

**45. How do you create a new test in Laravel?**
```php
A) php artisan make:test TestName
B) php artisan create:test TestName
C) php artisan test:create TestName
D) php artisan generate:test TestName
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>


**46. What command clears the application cache?**
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
</ul>
</details>


**47. How do you create a custom helper function in Laravel?**
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

**48. What method is used to define a named route in Laravel?**
```php
A) Route::name()
B) Route::get()->name()
C) Route::alias()
D) Route::define()
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

**49.What is the purpose of CSRF protection in Laravel?**
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
</ul>
</details>

**50. How do you exclude a route from CSRF protection?**
```php
A) Add it to the $except array in VerifyCsrfToken middleware
B) Disable CSRF in .env
C) Use Route::withoutCsrf()
D) Add a middleware noCsrf
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
</ul>
</details>


**51. What command is used to list all registered routes?**
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

**52Which middleware is used for verifying email in Laravel authentication?**
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
</ul>
</details>

**53. What is the default database engine in Laravel?**
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


**54. How do you specify a custom primary key in Eloquent?**
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

**55. What method updates a record in Laravel Eloquent?**
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
</ul>
</details>

**56. What is the purpose of Laravel’s timestamps property in a model?**
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
</ul>
</details>

**57. Which method is used to delete a record in Eloquent?**
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
</ul>
</details>

**58. What is the purpose of Laravel Horizon?**
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
</ul>
</details>

**59. What is the purpose of dd() function in Laravel?**
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
</ul>
</details>

**60. What tool does Laravel use for debugging?**
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

**61. Which command clears application logs in Laravel?**
```php
A) php artisan log:clear
B) php artisan logs:reset
C) rm -rf storage/logs/*
D) php artisan optimize:clear
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: C
</ul>
</details>

**62. What hashing algorithm does Laravel use by default?**
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
</ul>
</details>

**63. How do you hash a password in Laravel?**
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


**64. How do you enable API authentication in Laravel?**
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

**65. What is Laravel Mix?**
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


**66. How do you enable Laravel's maintenance mode?**
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
**67. How do you exit maintenance mode?**
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

**68. What command optimizes class loading in Laravel?**
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
</ul>
</details>

**69. What is Laravel Livewire?**
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

**70.What is Laravel Jetstream?**
```php
a) A package for database migrations
b) A Laravel starter kit for authentication and team management
c) A tool for API development in Laravel
d) A library for handling background jobs
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
</ul>
</details>

**71. What is the difference between first() and find() in Eloquent?**
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

**72. What are Laravel macros?**
```php
a) Functions used for database seeding
b) A way to add custom methods to Laravel’s built-in classes
c) A tool for writing reusable Blade templates
d) A feature used for routing middleware
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

**76. What are observers in Laravel?**
```php
a) A design pattern for middleware
b) A feature for handling model events
c) A tool for monitoring database queries
d) A method for API versioning
```

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: B
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
A) file
B) cookie
C) database
D) array
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: A
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





