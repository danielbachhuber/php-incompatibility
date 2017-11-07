RemovedGlobalVariables.http_raw_post_dataDeprecatedRemoved
==========================================================

## Explanation

The `$HTTP_RAW_POST_DATA` PHP global was deprecated in PHP 5.6 and removed in PHP 7.0.

## Resolution

Replace with `file_get_contents( 'php://input' );`

## References

* http://php.net/manual/en/reserved.variables.httprawpostdata.php
