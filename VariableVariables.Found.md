VariableVariables.Found
=======================

## Explanation

Indirect access to variables, properties and methods will be evaluated strictly in left-to-right order since PHP 7.0. Use curly braces to remove ambiguity.

## Resolution

For example, instead of:

	foreach ( $item['postmeta'] as $meta ) {
		$$meta['key'] = $meta['value'];
	]

The variable should be referenced with:

	foreach ( $item['postmeta'] as $meta ) {
		${$meta['key']} = $meta['value'];
	]

## References

* http://php.net/manual/en/migration70.incompatible.php#migration70.incompatible.variable-handling.indirect
