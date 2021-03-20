Create plain PHP associative array from XML
-------------------------------------------

Example usage:

```php
    $xmlNode = simplexml_load_file('example.xml');
    $arrayData = xmlToArray($xmlNode);
    echo json_encode($arrayData);
```

Read the blog post for [more info](https://outlandish.com/blog/tutorial/xml-to-json/).

License: [Public domain](http://creativecommons.org/publicdomain/mark/1.0/)
