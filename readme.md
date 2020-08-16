# Some of the most useful php functions

| Function | Description |
| --- | ----------- |
| [substr](https://www.php.net/manual/en/function.substr.php) | Returns the portion of string specified by the start and length parameters |
| [str_replace](https://www.php.net/manual/en/function.str-replace.php) | This function returns a string or an array with all occurrences of search in subject replaced with the given replace value. |
| [str_len](https://www.php.net/manual/en/function.strlen.php) | Returns the length of the given string. |
| [strpos](https://www.php.net/manual/en/function.strpos.php) | Find the numeric position of the first occurrence of needle in the haystack string. |
| [function_exists](https://www.php.net/manual/en/function.function-exists.php) | Returns TRUE if function_name exists and is a function, FALSE otherwise. |
| [get_class](https://www.php.net/manual/en/function.get-class.php) | Returns the name of the class of an object |
| [class_exists](https://www.php.net/manual/en/function.class-exists.php) |This function checks whether or not the given class has been defined.|
|[intval](https://www.php.net/manual/en/function.intval.php)|Returns the integer value of var, using the specified base for the conversion (the default is base 10). intval() should not be used on objects, as doing so will emit an E_NOTICE level error and return 1.|
|[str_repeat](https://www.php.net/manual/en/function.str-repeat.php)|Repeat a string|
|[parse_url](https://www.php.net/manual/en/function.parse-url.php)|This function parses a URL and returns an associative array containing any of the various components of the URL that are present. The values of the array elements are not URL decoded.|
|[func_get_args](https://www.php.net/manual/en/function.func-get-args.php)|Gets an array of the function's argument list.|
|[end](https://www.php.net/manual/en/function.end.php)|end() advances array's internal pointer to the last element, and returns its value.|
|[max](https://www.php.net/manual/en/function.max.php)|If the first and only parameter is an array, max() returns the highest value in that array. If at least two parameters are provided, max() returns the biggest of these values.|
|[min](https://www.php.net/manual/en/function.min.php)|If the first and only parameter is an array, min() returns the lowest value in that array. If at least two parameters are provided, min() returns the smallest of these values.|
|[preg_split](https://www.php.net/manual/en/function.preg-split.php)|Split the given string by a regular expression.|
|[gettype](https://www.php.net/manual/en/function.gettype.php)|Returns the type of the PHP variable var. For type checking, use is_* functions.|
|[ini_get](https://www.php.net/manual/en/function.ini-get.php)|Returns the value of the configuration option on success|
|[ini_set](https://www.php.net/manual/en/function.ini-set.php)|Sets the value of the given configuration option. The configuration option will keep this new value during the script's execution, and will be restored at the script's ending.|
|[ksort](https://www.php.net/manual/en/function.ksort.php)|Sorts an array by key, maintaining key to data correlations. This is useful mainly for associative arrays.|
|[uniqid](https://www.php.net/manual/en/function.uniqid.php)|Gets a prefixed unique identifier based on the current time in microseconds.|
|[floor](https://www.php.net/manual/en/function.floor.php)|Returns the next lowest integer value (as float) by rounding down value if necessary.|
|[ceil](https://www.php.net/manual/en/function.ceil.php)|Returns the next highest integer value by rounding up value if necessary.|

## Array Functions
| Function | Description |
| --- | ----------- |
|[array_unique](https://www.php.net/manual/en/function.array-unique.php)|Takes an input array and returns a new array without duplicate values.Note that keys are preserved. If multiple elements compare equal under the given sort_flags, then the key and value of the first equal element will be retained.|
|[array_slice](https://www.php.net/manual/en/function.array-slice.php)|Extract a slice of the array. Returns the sequence of elements from the array array as specified by the offset and length parameters.|
|[array_diff](https://www.php.net/manual/en/function.array-diff.php)|Compares array1 against one or more other arrays and returns the values in array1 that are not present in any of the other arrays.|
|[array_search](https://www.php.net/manual/en/function.array-search.php)|Searches the array for a given value and returns the first corresponding key if successful|
|[array_reverse](https://www.php.net/manual/en/function.array-reverse.php)|Return an array with elements in reverse order|
|[array_unshift](https://www.php.net/manual/en/function.array-unshift.php)|array_unshift() prepends passed elements to the front of the array. Note that the list of elements is prepended as a whole, so that the prepended elements stay in the same order. All numerical array keys will be modified to start counting from zero while literal keys won't be changed.|
|[in_array](https://www.php.net/manual/en/function.in-array.php)|Checks if a value exists in an array|
|[array_merge](https://www.php.net/manual/en/function.array-merge.php)|Merges the elements of one or more arrays together so that the values of one are appended to the end of the previous one. It returns the resulting array.|
|[array_keys](https://www.php.net/manual/en/function.array-keys.php)|returns the keys, numeric and string, from the array.|
|[array_key_exists](https://www.php.net/manual/en/function.array-key-exists.php)|array_key_exists() returns TRUE if the given key is set in the array. key can be any value possible for an array index.|
