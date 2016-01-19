PHP 花 framework


# File


root($args) = get basename

 - parameter -
$args->path / string


put_file($args) = put file

 - parameter -
 
$args->target / string, array
$args->content / string, array
$args->seek / int
$args->append / boolean
$args->sort / boolean


mv_file($args) = move/rename file

 - parameter -
 
$args->from / string, array
$args->to / string, array


copy_file($args) = copy file

 - parameter -
 
$args->from / string, array
$args->to / string, array


rm_file($args) = remove file

 - parameter -
 
$args->path / string, array


rm_dir($args) = remove directory

 - parameter -
 
$args->path / string, array


mk_dir($args) = make directory

 - parameter -
 
$args->path / string, array
$args->mode / int

