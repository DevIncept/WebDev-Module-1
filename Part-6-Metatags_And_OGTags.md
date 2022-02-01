# What is Metatag?
* HTML lets you specify metadata - additional important information about a document in a variety of ways. The meta elements can be used to include name/value pairs describing properties of the HTML document, such as author, expiry date, a list of keywords, document author etc.
* Meta tags always go inside the head element.
* Metadata is used by browsers (how to display content or reload page), search engines (keywords), and other web services.
* Metadata will not be displayed on the page, it is only read by computer.
## Attributes
|Sr.No    | Attributes   |Description                                                                                  |
|:---------:|:--------------:|:---------------------------------------------------------------------------------------------:|
| 1       | Name         | Specifies a name for the metadata                                                           |
| 2       | Content      | Specify the actual meta content                                                             |
| 3       | Charset      | Specifies the character encoding for HTML document                                          |
| 4       | Scheme       | Specifies a scheme to interpret the property's value (as declared in the content attribute).|
| 5       | Http-equiv   | Provides an HTTP header for the information/value of the content attribute                  |
## Uses of metatag
#### Specifying your document's character encoding
```HTML
 1. <meta charset="utf-8">
```
This element specifies the document's character encoding — the character set that the document is permitted to use. utf-8 is a universal character set that includes pretty much any character from any human language. This means that your web page will be able to handle displaying any language.
#### Document  description
You can use <meta> tag to give a short description about the document. This again can be used by various search engines while indexing your webpage for searching purpose.
```HTML
<meta name="author" content="Chris Mills">
<meta name="description" content="The  Web Docs aims to provide
complete beginners to the Web with all they need to know to get
started with developing web sites and applications.">
```
These two  meta elements  are useful to include on your page define the author of the page, and provide a concise description of the page.
#### Setting up Viewport 
The viewport is the user's visible area of a web page. It varies with the device - it will be smaller on a mobile phone than on a computer screen.
Let's look at an example:
```HTML
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
The width=device-width part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).
The initial-scale=1.0 part sets the initial zoom level when the page is first loaded by the browser.


# What is Open Graph (OG)?
Open Graph is an internet protocol that standardize  the use of metadata within a webpage to represent the content of a page.
Within it, you can provide details as simple as the title of a page or as specific as the duration of a video. These pieces all fit together to form a representation of each individual page of the internet.
# Why do I need it?
It is used to create preview of your content.This will help encourage people to check out your content and inevitably click through to your content.
Just like a facebook post of websites where you can see how nicely the preview of your content is made.
For example:
![OG example](https://realfavicongenerator.net/blog/wp-content/uploads/2017/01/crop_example_2-272x300.png)
# Basics 
|Tags|Description| 
|:---------:|:---------:|
|  og:title  |   This is typically the same as your webpage's title tag unless you’d like to present it differently.  |  
|  og:type  |  The “type” of website you have.  | 
|  og:image |  This should be a link to an image that you’d like to represent your content. It should be a high resolution image that the social networks will use in their feeds.|
|  og:url  | This should be the URL of the current page.|
|  og:site_name | The name of the overall website your content is on. Suppose if  you're on a blog post page, you might have a title using that blog post’s title, where the site_name would be the name of your blog.|
# Social media networks using open graph
Most of the social networks adhere to the basics of open graph standards, but a few of them also include their own extension to help customize the look and feel within their ecosystem.

Twitter for instance, allows you to specify twitter:card, which is the type of “card” you can use when they show your website. At this time, their card types include:
* summary
* summary_large_image
* app
* player
So you need to look documentation of specific site to add social media links .

