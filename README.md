XPATH
=====

*This class is from a video tutorial I did on youtube. It is very simple and should be built upon. I will keep this version the same as the video.* 

##Basic Example

```
// Create an instance of XPATH
$path = new XPATH("http://example.com");

// An example query. This will grab all the link href attributes from a page
$links = $path->query("//a/@href");

// loop through and output node values
if($links->length > 0){
    foreach($links as $link) {
        echo $link->nodeValue . "<br>";
    }
}
```


###Youtube videos on Scraping Websites with Xpath

* [Scraping Websites with PHP using DOMDocument and DOMXpath](https://www.youtube.com/watch?v=632ql93H90g)
* [Scraping Websites with PHP using DOMXpath and DOMDocument Part 2: Building an XPath Class](https://www.youtube.com/watch?v=SIPGkrlM3R8)
* [Scraping Websites with PHP using DOMXpath and DOMDocument Part 3: Recursive Scraping](https://www.youtube.com/watch?v=0GbCjIJTvac)

###More useful Links
* [PHP DOMDocument](http://www.php.net/manual/en/class.domdocument.php)
* [PHP DOMXpath](http://www.php.net/manual/en/class.domxpath.php)
* [PHP cURL](http://php.net/curl)

__I dont usually link to w3fools but they have a nice Xpath syntax reference, even MDN links to it.__
* [Xpath syntax reference (w3schools)](http://www.w3schools.com/xpath/xpath_syntax.asp)
* [More Xpath info on MDN](https://developer.mozilla.org/en-US/docs/XPath)

Hope you find this useful.

*-Nate Wiley*

[Follow me on Twitter](http://twitter.com/htmlnate)

[Add me to a circle G+](http://google.com/+NateWiley)
    
