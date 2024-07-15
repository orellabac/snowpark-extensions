## SQL Extensions


| UDF               | Description                                                              |
|-------------------|--------------------------------------------------------------------------|
| _concat_ws         | Concatenates multiple input string columns together into a single string column, using the given separator.|
| _datediff          | Calculates the difference in days between two dates. NOTE: The function name has an underscore at the start to differentiate it from the existing built-in in Snowflake. |
| array_zip          | Returns a merged array of arrays. |
| conv               | Converts num from from_base to to_base. |
| date_add           | Adds days to a date. |
| date_format        | Converts a date/timestamp/string to a value of string in the format specified by the given date format. |
| date_sub           | Subtracts days from a date. |
| format_string      | Returns a formatted string from printf-style format strings. |
| from_unixtime      | Returns a date string representation of a Unix epoch timestamp using the specified format. |
| instr              | Returns the position of the first occurrence of the substr column in the given string. |
| isnan              | Returns true if expr is NaN, or false otherwise. |
| nanvl              | Returns expr1 if it's not NaN, or expr2 otherwise. |
| map_from_arrays    | Creates a new map from two arrays |
| regexp_extract     | Extracts the group specified based on the regexp. |
| regexp_like        | Returns True/False based on whether a regexp matches. |
| regexp_replaceall  | Replaces all matches to a regexp with another string. |
| regexp_split       | Splits into an array based on the regexp. |
| substring_index    | Returns the substring from str before count occurrences of the delimiter. |
| unix_timestamp     | Turns a date or date string into epoch_second. |****
