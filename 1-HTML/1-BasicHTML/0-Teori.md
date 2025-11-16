# HTML
HTML (Hypertexy Markup Languange) is a markup langueage for creating web pages.
HTML represents the content and structure of a webpage through the use of elements.
most elements will have an opening tag and a closing tabs. Somethings those tags are referred to a start and end tags. 
In between those two tags, you wil hae the content. This content can be text or other HTML elements.
<p>im a paragragh elements</p> 
<p></p> ==> is a element
'im a paragraph elements'==> is a content

Some HTML elements do not hava a closing tags. These are known as void elements. 
Examples void elementd                  
<img> or <img/> 
*Sometimes void element use a / before >

some elements include attribute
Attributes provide additonal information about the element or specify how the element should behave.
An Attribute is a value placed inside the opening tags 
basic syntax for an attribute:
<element attribute='value'></element>

attribute name is followed by an equal sign (=) and a value in qoutes(' ').

# Link Element
The link element is used to link external resources like stylesheets and site icons
basic syntax for using link element:
<link rel="stylesheet" href="/styles.css"/>
the ~rel~ attribute is used to specify the relationship between the linked resource and the HTML doc.
the ~href~ attribute is used to specify the location of the URL for the external resource.

The link elements should be places inside the head element

# HTML Boilerplate
HTML Boilerplate is basic structure and essential elements HTML documents need.
example:
<!DOCTYPE html> 
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta
       name="viewport"
       content="width=device-width, initial-scale=1.0" />
    <title>freeCodeCamp</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
  </body>
</html>

~<!DOCTYPE html> ~ ==> tell browsers which version of HTML you're using

<!DOCTYPE html>
<html lang="en">
  <!--All other elements go inside here-->
</html>
==> 