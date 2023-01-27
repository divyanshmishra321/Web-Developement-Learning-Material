# ⏩Text Formatting,Inline_block Elements , and Types of Lists in HTML

### ✅Introduction ✅

***Hello Everyone This is your boy <mark>Divyansh Mishra </mark> with One Another Amazing informative blog-***

Are you tired of using the same old text formatting techniques in HTML? Look no further! In this blog post, we will be diving into the world of headings, paragraphs, text formatting, inline-block elements, and types of lists in HTML.

We will start by discussing the importance of using headings and paragraphs to structure the content of your webpage. You will learn about the different levels of headings and how to create paragraphs.

Next, we will delve into the world of text formatting. You will learn about the various tags and techniques that can be used to make text bold, italicized, and more.

We'll also explore the concept of inline-block elements and how they differ from block elements. You'll learn how to use these elements to create more flexible and responsive layouts for your webpage.

Finally, we will take a look at the different types of lists that can be used in HTML. You'll learn about ordered and unordered lists, as well as the different markers that can be used to indicate the items in the list.

So, whether you're a beginner looking to improve your HTML skills or an experienced developer looking to refresh your knowledge, this blog post has something for everyone. So, let's get started!

### ⏩Headings and Paragraphs

In HTML, headings and paragraphs are used to structure the content of a webpage.

Headings are used to creating different levels of importance for text, with H1 being the most important and H6 being the least important.

For example, the following code will create an H1 heading:

```html

<!-- Types of Heading in HTml  -->

    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>
```

Paragraphs are used to create blocks of text on a webpage. The following code will create a paragraph element:

```html

<p>This is a paragraph of text.</p>
```

Formatting in HTML can be done by using various tags such as:

* `<b>` and `<strong>` for bold text
    
* `<i>` and `<em>` for italic text
    
* `<u>` for underlined text
    
* `<mark>` to highlight text
    
* `<sup>` and `<sub>` for superscript and subscript text
    
* `**<abbr>**` tag is used for abbreviations
    
* `<small>` is used to insert small text.
    
* \*\*\*\*\*\*\*\*\*\*`<big>`\*\*\*\*\*\*\*\*\*\*is used to insert big text as compared to small text.
    
* \*\*\*\*\*\*\*\*\*\*\*\*\*\*`<strike>` is used to cut text in middle.
    
* `<ins>` is used to insert new text in between.
    
* `<dfn>` text is used to write the definition of something.
    

For example, the following code will create bold, italic, and underlined text:

```html

<p>This is a <b>bold</b> text, 
<i>italic</i> text and 
<u>underlined</u> text.</p>
<small>hello </small>
<big>hello </big>
<strike>strinke text using strike tag</strike> 
<ins>Inserted text using Ins tag </ins>
```

It is important to note that headings and paragraphs should be used in a logical hierarchy, with H1 being used for the main heading of a page and H2 for subheadings, H3 for sub-subheadings, and so on.

### ⏩Inline and Block Elements in HTML

In HTML, elements can be classified as either **inline elements** or **block elements**.

The main difference between the two is how they are displayed on a webpage and how they interact with other elements.

* **Block elements:**
    
    Block elements take up the full width of their parent container and create a new line after them. **Examples** **of block elements include—**
    
    * Headings (H1-H6)
        
    * Paragraphs (`<p>`)
        
    * Divs (`<div>`)
        
    * Lists (`<ol>`, `<ul>`, `<li>`)
        
    * Tables (`<table>`, `<tr>`, `<td>`)
        
    * Form elements (`<form>`, `<fieldset>`, `<legend>`)
        
    * Block-level semantic elements (`<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<footer>`)
        
* **Inline elements:**
    
    Inline elements only take up as much width as necessary and do not create a new line after them.
    
    Some common Inline Elements—
    
    * Images (`<img>`)
        
    * Links (`<a>`)
        
    * Spans (`<span>`)
        
    * Text-level semantic elements (`<strong>`, `<em>`, `<mark>`, `<cite>`, `<dfn>`, `<code>`, `<kbd>`, `<samp>`, `<var>`, `<q>`, `<abbr>`, `<data>`, `<time>`, `<bdo>`)
        
    * Input elements (`<input>`, `<select>`, `<textarea>`, `<label>`, `<output>`)
        
    * Script and style elements (`<script>`, `<style>`)
        

![https://www.bitdegree.org/learn/storage/media/images/inline-elements.o.png](https://www.bitdegree.org/learn/storage/media/images/inline-elements.o.png align="left")

It's important to note that most of the elements in HTML can be both inline and block elements by using CSS properties like `display:block`, `display:inline`, `display:inline-block` etc.

It's also possible to change the behavior of an element using CSS, for example you can make a div element to behave like an inline element by using `display:inline` property.

### ⏩Types of Lists In HTML

In HTML, there are three main types of lists:

* **Ordered lists (**`<ol>`)
    
    Ordered lists are used to create a list of items that are in a specific order, usually numbered. Each item in the list is represented by a `<li>` element and the numbers are automatically generated by the browser.
    
    ```html
    
    <ol>
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
    </ol>
    ```
    
* **Unordered lists (**`<ul>`)
    
    1. Unordered lists (`<ul>`): Unordered lists are used to create a list of items that are not in a specific order, usually bullet points. Each item in the list is represented by a `<li>` element, and the bullet points are automatically generated by the browser.
        
    
    ```html
    
    <ul>
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
    </ul>
    ```
    

### Conclusion

In conclusion, this blog post has provided an in-depth look at various HTML elements and techniques that can be used to structure, format, and style text, and create layouts and lists. We've discussed the importance of using headings and paragraphs to structure content, the different levels of headings, the different tags and techniques that can be used to format text, and the concept of inline-block elements. We also explored the different types of lists that can be used in HTML, including ordered and unordered lists, and the different markers that can be used to indicate the items in the list. By understanding and utilizing these elements and techniques, you will be able to create more visually appealing and structured web pages. Remember to use CSS to format text, it's recommended by web developers because it's more flexible and can be reused. With this knowledge, you are now equipped to take your HTML skills to the next level.

**Thanks for reading! We hope you found this blog post informative and engaging. If you did, please don't hesitate to show your support by liking, sharing, following and subscribing to our blog. Your support helps us continue to create valuable content and we couldn't do it without you. We look forward to connecting with you on our social media and bringing you even more great content in the future!**

If you enjoyed this blog post, be sure to check out our previous ones as well! We have a wealth of information on various topics that you might find interesting. From tips and tricks to in-depth tutorials, there's something for everyone.

Click on the link to access our previous blogs and stay updated with the latest information.

%[https://icoderdivyansh.hashnode.dev/understanding-the-power-of-emmet-in-developers-life]