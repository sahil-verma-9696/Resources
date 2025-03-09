- **1. Can we display a web page inside a web page or
  Is nesting of webpages possible?**

  - **Yes**, we can display a web page inside another HTML web page. HTML provides a tag `<iframe>` using which we can achieve this functionality.

  ```html
  <iframe src="”url" of the web page to embed” />
  ```

- **2. What are tags and attributes in HTML?**

Tags are the primary component of the HTML
that defines how the content will be structured/ formatted,

whereas Attributes are **used along with the HTML tags** to define the **characteristics** of the element.

For example,

```html
<p align="center">Interview questions</p>
,

<img src="path_of_image" alt="" />

<a href="hperlink">hypertext</a>
```

in this the ‘align’ is the attribute using which we will align the paragraph to show in the center of the view.

- **3. What are void elements in HTML?**

HTML elements which do not have closing tags or do not need to be closed are **Void elements**.
For Example

```html
<br />, <img />,
<hr />
, etc.
```

- **4. What is the advantage of collapsing white space?**

In HTML,
a **blank sequence of whitespace** characters is treated as a **single space character**,  
Because the browser collapses multiple spaces into a single space character and  
this **helps a developer to indent lines** of text without worrying about multiple spaces and **maintain readability** and understandability of HTML codes.

- **5. What are HTML Entities?**

```html
Character Entity Name Entity Number < &lt; &#60; > &gt; &#62; & &amp; &#38;
(non-breaking space) Eg. 10 PM &nbsp; Eg.
<p>10&nbsp&nbspPM</p>
&#160;
```

- **6. What are different types of lists in HTML?**

- [un-orderd list](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
- [orderd list](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
- [discription list](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dl)

- **7. What is the ‘class’ attribute in HTML?**
- The class attribute is used to specify the class name for an HTML element. Multiple elements in HTML can have the same class value. Also, it is mainly used to associate the styles written in the stylesheet with the HTML elements.

- **8. What is the difference between the ‘id’ attribute and the ‘class’ attribute of HTML elements?**

Multiple elements in HTML can have the same class value, whereas a value of id attribute of one element cannot be associated with another HTML element.

- **9. Define multipart form data?**

- text/plain
- multipart/form-data
- application/x-www-form-urlencoded

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>upload</title>
  </head>
  <body>
    <form
      action="http://localhost:8000"
      method="post"
      enctype="multipart/form-data"
    >
      <p><input type="text" name="text1" value="text default" /></p>
      <p><input type="text" name="text2" value="a&#x03C9;b" /></p>
      <p><input type="file" name="file1" /></p>
      <p><input type="file" name="file2" /></p>
      <p><input type="file" name="file3" /></p>
      <p><button type="submit">Submit</button></p>
    </form>
  </body>
</html>
```

- **10. Describe HTML layout structure.**

Every web page has different components to display the intended content and a specific UI. But still, there are few things which are templated and are globally accepted way to structure the web page, such as:

<header>: Stores the starting information about the web page.
<footer>: Represents the last section of the page.
<nav>: The navigation menu of the HTML page.
<article>: It is a set of information.
<section>: It is used inside the article block to define the basic structure of a page.
<aside>: Sidebar content of the page.



- **11. How to optimize website assets loading?**

