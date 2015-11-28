# Reserved words class

This class contains an array of reserved words for PHP including PHP 7. This can be used to make sure reserved words are not used.

##Install
include the class, add a namespace to use composer autoloading or include manually.

##Usage

````
include('ReservedWords.php');
$name = 'list';
if(in_array($name, ReservedWords::getList())){
  exit("Name cannot be a reserved word\n");
}
````
