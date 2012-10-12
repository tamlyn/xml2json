Create plain PHP associative array from XML
-------------------------------------------

Example usage:

    $xmlNode = simplexml_load_file('example.xml');
    $arrayData = xmlToArray($xmlNode);
    echo json_encode($arrayData);


[More info](http://outlandishideas.co.uk/blog/2012/08/xml-to-json/)
[Public domain](http://creativecommons.org/publicdomain/mark/1.0/)
