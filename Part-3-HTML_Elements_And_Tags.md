# HTML Elements And Tags 

## Elements and Tags

> - An HTML element is usually composed by two tags: the opening tag and the closing tag. An opening tag consists of the element's name encolsed by the lesser-than "<" and greater-than ">" signs. The closing tag is constructed like the opening tag but, in this case, the element's name is preceded by a slash ("/"). In the following example, you'll see the opening and closing tags for the <"b"> element.

> - Be aware that elements aren't tags. Elements are represented by tags in the code. Yet they are usually considered, erroneously, the same thing.



> - ***<'b>Important text<'/b>*** As you can see, there's the opening tag (<'b>) and the closing tag (<'/b>). Now, the text you see in the middle, "Important text", is known as the element's content. As you progress in your learning of this language, you'll see that some elements are not supposed (and not allowed) to have content. These are the empty elements.

> - Each one of the many elements in HTML5 has a specific and particular purpose. Some of them are exclusively semantic, others have an impact in the document rendering and some both.

> - In addition to tags and content, an element can have attributes and events. While attributes define values or properties to be used by browsers in the processing of the document, events can be employed to specify behaviors or actions to be performed when certain conditions are met, like for example, when the users clicks the element.

> - Attributes and events share a common syntax: they must be inserted as a list of space-separated items inside the star tag, after the element's name and preceded by a space. Each one of these items is composed by a name (for the attribute or event), the equal sign ("=") and the value or function (sometimes optionally) enclosed by quotes. The following example shows a <'b> element with one attribute (style) and one event (onclick).

## CONTENT

The content of an element is, generally speaking, whatever falls inbetween its opening and closing tags. Depending on the element, this can go from absolutely nothing to a piece of HTML document. This content is what will be affected by the element's functionality or meaning. For example, the <'em><em> element grants its content emphasis, and browsers usually display its text with a particular font style to make it stand out from regular text.

* Some elements, known as empty elements, aren't allowed to have content and their declaration consist only of the opening tag with any number of attributes and events.

In the following example are three elements each containing a different type of content: the paragraph (<'p> element), cointaining other elements; a word with emphasis (<'em> element), containing plain text; and a button (input (type=button) element), which is an empty element, code line 20

 **HTML Tags**

|       Tags                            |     Description                                                                                |
|---------------------------------------|------------------------------------------------------------------------------------------------|
|      a                                | Defines a hyperlink.                                                                           |
|      article                          | Defines an article.                                                                            | 
|      aside                            | Defines some content loosely related to the page content.                                      |
|      body                             | Defines the document's body.                                                                   |
|      br                               | Produces a single line break.                                                                  |
|     details                           | Represents a widget from which the user can obtain additional information or controls on-demand|
|     div                               | Specifies a division or a section in a document.                                               |
|     h1 to h6                          | Defines HTML headings.                                                                         |
|     head                              | Defines the head portion of the document that contains information about the document.         |
                                 
                                 
  
 **HTML Elements Types**
 
Elements can be placed in two distinct groups: block level and inline level elements. The former make up the document's structure, while the latter dress up the contents of a block.

Also, a block element occupies 100% of the available width and it is rendered with a line break before and after. Whereas, an inline element will take up only as much space as it needs.

 **Div and Span tag**
  
  **div** tag should be used for grouping a set of related elements to create a relationship between them on a webpage, the **span** tag should be used to change the style of something on a webpage without affecting the context it is within. 
  
 ## Executed Code Example: 
 
 > DevIncept Eg:1
 

<center>
<table border="1" cellspacing="10px" cellpadding="10px" width="500px">
<caption style="color:blue;">Student Data</caption>
<tr>
<th colspan="5">DOT</th>
</tr>
<tr>
<th> rollno </th>
<th> name</th>
<th> mark1 </th>
<th> mark2</th>
<th>total</th>
</tr>
<tr style="text-align: center; color: red">
<td>1</td>
<td style="color: black;">AMBIKA</td>
<td>98</td>
<td>98</td>
<td>196</td>
</tr>

</table>
</center>

<br>

<br>

<br>


