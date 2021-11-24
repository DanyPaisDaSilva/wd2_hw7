
**JavaScript Cookie**

A simple, lightweight JavaScript API for handling cookies

string} get(key)
Gets a cookie using parameter key
Defined in: jscookie.js.

Parameters:
{string} key
    - The key of the cookie that is to be gotten

Returns:
    {string} Value of the cookie belonging to the cookie whose key is equal to parameter key

remove(key, attributes)
Removes a cookie that has the key of parameter key
Defined in: jscookie.js.

Parameters:
{string} key
    - The key of the cookie that is to be deleted
{Object.} attributes
    - A dictionary with a string key and whose values can be either string or numbers. Dictionary of the to be deleted cookie

{undefined|string} set(key, value, attributes)
Create a cookie using parameters key, value and attributes
Defined in: jscookie.js.

Parameters:
{string} key
    - The key of the cookie that will be created.
{string} value
    - The value of the cookie that will be created.
{Object.} attributes
    - A dictionary with a string key and whose values can be either string or numbers. Dictionary of the to be created cookie

Returns:
    {undefined|string} Either returns nothing or a cookie as a string 