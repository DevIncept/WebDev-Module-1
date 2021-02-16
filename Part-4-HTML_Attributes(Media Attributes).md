## HTML Attributes

> - Attributes are the way authors have to define properties for an element. These properties usually change the way a browser interpret the element, by changing its meaning or presentation. For example, the <'a> [element](https://www.htmlquick.com/reference/tags/a.html) inserts a link in the document, but the <b>rel</b> *attribute states the relationship between the current document (the one containing the link) and the destination resource (the one the link is pointing to).*

> - Many of the attributes in HTML5, the ones known as [global attributes](https://www.htmlquick.com/reference/attributes.html), are available for all elements in the standard. But most elements have also a set of specific attributes that are only available or specifically adapted for them.

> - As we already saw in previous examples, attributes are declared by stating their name, followed by an equal sign ("=") and the assigned value enclosed by quotes. But some attributes, which can only take boolean values (true or false), apply their value just with their presence. In these cases, attributes can be declared just by stating their name.

> - In the following example, the [<'button> element](https://www.htmlquick.com/reference/tags/button.html) has three attributes present: <b>id and acceskey</b>, which are [global attributes](), and disabled (boolean), which isn't global but is shared by a particular group of element


All HTML elements can have attributes
> - The href attribute of <'a> specifies the URL of the page the link goes to
> - The src attribute of <'img> specifies the path to the image to be displayed
> - The width and height attributes of <'img> provide size information for images
> - The alt attribute of <'img> provides an alternate text for an image
> - The style attribute is used to add styles to an element, such as color, font, size, and more
> - The lang attribute of the <'html> tag declares the language of > - the Web page
> - The title attribute defines some extra information about an element

:star:**Html Attributes**

* All HTML elements can have attributes.
* Attributes provide additional information about elements.
* Attributes are always specified in the start tag.
* Attributes usually come in name/value pairs like: name="value".
* for eg. 1. Use [text](url) for hyperlinks
            [Devincept Website](https://devincept.tech/)
            
 
 # Media Attributes?
The media attribute specifies what media/device the linked document is optimized for.
The media attribute can be used on the following elements:
```HTML
<a>
<link>
<source>
<style>
```
1.Anchor tag ```<a>```:
The <a> tag defines a hyperlink, which is used to link from one page to another.</br>
A link with a media attribute:
```HTML
<a href="att_a_media.asp?output=print"
media="print and (resolution:300dpi)">
Open media attribute page for print.</a>
```
2. Link tag:
The ```<link>``` tag defines the relationship between the current document and an external resource.
Example:
```HTML
<head>
<link rel="stylesheet" type="text/css" href="theme.css">
<link rel="stylesheet" type="text/css" href="print.css" media="print">
</head>
```
3. Source tag: The ```<source>``` tag is used to specify multiple media resources for media elements, such as video, audio, and picture.
Example:
```HTML
<source src="movie.ogg" type="video/ogg"
media="screen and (min-width:320px)">
```
4.Style: The <style> tag is used to define style information (CSS) for a document.
```HTML
<style media="print">
h1 {color:#000000;}
p {color:#000000;}
body {background-color:#FFFFFF;}
</style>
```
5. Video:The HTML``` <video>``` element is used to show a video on a web page.
```HTML
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  </video>
  ```
  The controls attribute adds video controls, like play, pause, and volume.
It is a good  to always include width and height attributes. If height and width are not set, the page might flicker while the video loads.
The <source> element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.</br>
6. Audio: The HTML ```<audio>``` element is used to play an audio file on a web page.
```HTML
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  </audio>
  ```
 The controls attribute adds audio controls, like play, pause, and volume.
The ```<source>``` element allows you to specify alternative audio files which the browser may choose from. The browser will use the first recognized format.</br>
7.Youtube video:To play your video on a web page, do the following:

* Upload the video to YouTube
* Take a note of the video id
* Define an <iframe> element in your web page
* Let the src attribute point to the video URL
* Use the width and height attributes to specify the dimension of the player
* Add any other parameters to the URL (see below)
```HTML
<iframe width="420" height="315"
src="https://www.youtube.com/embed/tgbNymZ7vqY">
</iframe>
```


