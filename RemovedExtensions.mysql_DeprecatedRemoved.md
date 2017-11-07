RemovedExtensions.mysql_DeprecatedRemoved
=========================================

## Explanation

The 'mysql_' extension is deprecated since PHP 5.5 and removed since PHP 7.0; Use the mysqli extension instead.

## Resolution

Any use of functions beginning with `mysql_` should be replaced with their `mysqli_` equivalents.

Note the behavior of the `mysqli_` functions may vary; please refer to the corresponding function definition.

## References

* http://php.net/manual/en/migration55.deprecated.php#migration55.deprecated.mysql
