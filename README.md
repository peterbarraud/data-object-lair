# data-object-lair
A simple PHP-based data object layer that you can easily use to set up RESTFul services in PHP
## create a data object
For every table that you create in your db, you'll need to create two data object files
### inherit from object base
One file must inherit from the objectbase.php (see `appuser.php` for example)
### inhert from object base collection
The other file must inherit from the objectcollectionbase.php (see `appusercollection.php` for example)

## object base
The object base class has methods to
* get (actually via the construtor)
* save (edit or new)
* delete (this is still work in progress. especially for stuff like cascade delete et al)
## decorating your own class
We're using a decorator pattern type approach here.

So if you want to add functionality to your object, you should be adding that to your own class not meddling around with the base class


