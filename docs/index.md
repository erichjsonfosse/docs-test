# blep


```php
<?php

// routes.php
Route::get('/people/{person}', 'PersonController@view');

// PersonController.php
class PersonController {
    public function view(\CC\Domain\Person\Person $person){
        // Person has been fetched based on the ID in the route.
        // if the person is not found, a 404 page is shown.
    }
}
```
