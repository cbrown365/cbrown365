### Hi there 👋

<!--
**cbrown365/cbrown365** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

I'm not entirely sure what I'm doing or if I'm doing it right.
I have absolutely no coding experience or knew that there were so many different coding languages outside of java or python.
This has the possibility of being a massive mistake.
But I hope I have the time to learn something.


Notes about HTML:
HTML Tag;
An HTML tag is a keyword or a set of characters that defines the format of a web page and determines how its content is displayed onscreen. The combination and order of HTML tags will determine the structure and design of the HTML document. A client browser uses the information in each tag to understand the nature of the tags' content and how to display them correctly. The combination of a tag and its content is known as an element. Some tags, called parent tags, can contain other tags, called children tags. Most tags must have an opening and closing tag, like a set of brackets, but some tags do not require a closing tag and include a closing slash to indicate that they are single tags.
<div> - Parent tag
   <span> - opening tag
      content - element/content
  </span> - closing tag and indented child tag
  So all together its
  <div>
    <span>content</span>
    <div>
     
<body></body> - The <body> tag contains all the test, data, and images, that are displayed when the HTML document is opened in a browser.
  <p></p> - This tag contains the test that should appear as a paragraph onscreen. The browser starts a new line and adds margins for spcaing around the paragraph.
  <div></div> - The <div> tag is a container for all the HTML elements that can be styled and positioned as a group. This tag displays elements on a new line.
  <img/> - The <img/> tag is used to describe an image on the page. Its "src" attribute contains the URL that points to the location of the image file.
  <a></a> - The <a> (anchor) tag describes a hyperlink, which is used to link one page to another. This tag contains the "href" attribute (more on that later), which holds the link's destination.
  <html></html> -These are outer tags that apply to the entire HTML document. The first <html> tag indicates the markup language (the system that formats the text for display) used for the document and the </html> tag marks the end of the web page.
  <h1></h1> - The <h1/h2/h3/h4/h5/h6> tags indicate that the text is a header. <h1> is usually used for the title of the page, while the others are used to style smaller headings of the document.
  <br/> - The <br/> tag tells the browser to start a new line. It is a single tag, with the closing slash included before the closing greater-than sign.
  Indenting tags - Good programming includes using visual aids to make code more readable. One of the easiest ways to improve the readability of code is to indent child tags inside their parent tags. To help with indention, a "Tidy HTML" or "Format HTML" tool can be used to format the code and indent the children tags.
  <head></head> - The <head> tag contains the metadata that is required to describe the styles, fonts, linked files, page title, and scripts used by the HTML document.
  <title></title> - This tag contains the text that appears as the title of a document in the browser. There cannot be more than one <title> document in an HTML document.
  <span></span> - The <span> tag contains the text and other HTML elements that should appear on the same line.
  EX of HTML document structure:
  <!doctype HTML> - Document type delcaration
  
  <html>
  <head> 
    <title> </title>
  </head>
  <body>
    <p></p>
  </body>
  </html> 
  
  Attributes:
  Most HTML tags have attributes that provide additional information about the HTML element. An attribute describes a property or characteristic of the element. It always appears inside the element's opening tag in a key="value" format. Some attributes may be required by the tag type to render correctly, while other attributes may be optional.
  <img/> tag attributes - Apart from "src", the "width" and "height" attributes define the dimensions of an image, and the "alt" attribute provides an alternative text description for images that cannot be displayed.
  <a> tag attributes - The "href" attribute contains a URL that points to the hyperlink's destination, and the "target" attribute instructs the browser to open the hyperlink in a new browser tab or the same tab.
  "id" attribute - The "id" attribute describes the identity of an element. It can be added to any kind of tag and is specified to it. This attribute can also be used to select the element in CSS and JavaScript.
  "name" attribute - This attribute is used by input elements to define the name of the property, or characteristic of the element, that is sent to the server. This attribute must be unique to each element in a form.
  "class" attribute - The "class" attribute describes the name of a group that the element is a part of. Many elements on the same page can be members of the same class.
  "style" attribute - The "style" attribute describes the visual characteristics of an element. It defines a list of key-value pairs. Each key-value style definition is seperated by a semicolon (more on that later).
  
  HTML Forms and Hyperlinks:
