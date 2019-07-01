//to make controller
php artisan make:controller PagesController
php artisan make:controller PostsController
//controller with functions
php artisan make:controller PostsController --resource

//to make model with migration

php artisan make:model Post -m

//to migrate 
php artisan migrate


// scss
npm run watch 

//tinker to add dummy data
php artisan tinker
>>$post = new App\Post()  //creates an instance 
>>$post->title= 'Post One';
>>$post->body= 'this is post body';
>>$post->save();


//check available routes
 php artisan route:list