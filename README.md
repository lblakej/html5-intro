# HTML5 Intro

source material: <cite>HTML5 in easy steps, 2nd edition, 2017.</cite>

We will cover four main topics in this section.

**I will use some mason jar "containers" to introduce the concepts of how HTML is structured.**

1. Document type declaration 
2. html container
3. Head Section
4. Body Section

Next I will demo the basic structure of three content tags.

* Paragraph
* Anchor link 
* 
 We will not have time today to learn this html in depth, but I want you to get a feel for the building block structure which includes **tags**, **attributes**, **values**, all of which makes an **element**.

**I have some cardboard building blocks that will help us see how HTML is modular and not that difficult to understand.**

## 1. Doctype Declaration

Tells the browser to "render" display the document in "Standards Mode."

Each of the following is standard because HTML5 is not case sensitive: 

* ```<!DOCTYPE HTML>``` [ineasysteps.com](http://ineasysteps.com/products-page/all_books/html5-easy-steps-2nd-edition/)
* ```<!Doctype Html>```  
* ```<!DOCTYPE html>``` [apple.com](http://apple.com) | [wordpress.com](http://wordpress.com)
* ```<!doctype html>``` [google.com](http://google.com) | [amazon.com](amazon.com)


*Note that the HTML5 DOCTYPE does not have any reference to the number 5.* 

When we learn about html tags, we will see that it is very rare to see any HTML tags that are not coded in lower case:

```
<p>Welcome to my site!</p>
```
See this link to [learn about previous doctype examples](https://www.w3.org/QA/2002/04/valid-dtd-list.html).

### Following the doctype declaration, there needs to be a pair of ```<html></html>``` tags that contains the head and the body section.



##  Head Section

The head section contains instructions for the broswer that do not show in the web page. For example, the title tag goes in the head section. This shows in the title bar of the browser.

```
<head>
<title>My Home Page</title>
</head>
```
There are only a few required tags that need to go into the head section, but there are very many tags that **can** go in there. Here is the most comprehensive list that I have found: [https://gethead.info/](https://gethead.info/)

## Body Section
Data in this section will form the bulk of the web page. It can contain headings, paragraphs, images, tables, forms, links, and even embedded movies and javascript.

```
<body>
<h1>My Home Page</h1>
<p>This is a paragraph tag.</p>
</body>
```


## Fundamental Structure

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
   <h1>My Home Page</h1>
   <p>This is a paragraph tag.</p>    
  </body>
</html>
```




