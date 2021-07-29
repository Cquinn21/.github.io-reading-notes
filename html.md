# HTML

- HTML stands for **H**yper**T**ext **M**arkup **L**anguage. This is the code that is used to structure a web page and the content of the page. It consists of **elements** that you uses to wrap or enclose content to make it appear a certain way.

- An **element** defines the HTML document. A typical element includes: opening tag, closing tag, attributes, and enclosed text.

- *Example:* ```<p> my dog has a very loud bark </p>``` Read in order from left to right, the code is as follows:

    1. **Opening Tag:** ```<p>``` name of the element with opening and closing angle brackets ```(<>)```

    2. **Closing Tag:** ```<\p>``` same as the opening tag, but also has a forward slash ```(\)``` before the element name.

    3. **The Content:** the elements content, which depends on the element, in this case ```<p><\p>``` for paragraph, so it would include text.

    4. **The Element:** consists of opening and closing tag and the content.

- **Attributes** is extra information about the element. *Example:* ```<p class="reading-notes"> <\p>``` The attribute is class, then the value is reading-notes.

- **Attributes** should contain the following:
    1. Space between the element name.

    2. Name of the attribute followed by the equal sign.

    3. The value of the attribute. Should have open and closing quotations.

- **Nesting Elements:** placing elements inside of elements. *Example:* ```<p> My dog barks <strong>very<\strong> loud. <\p>``` This will emphasize the word "very".

- **Empty Elements:** Empty elements have no content. Example of an empty element would be the ```<img>``` element. Its only purpose is to embed an image. It does not require a closing tag. 

## Starting HTML

- To start you HTML coding, you use html boilerpoint. Boilerpoint is the set of files that give the website its foundation. It goes as follows:

  - ```<!DocType html>``` ensures the document behaves correctly.

  - ```<html><\html>``` Known as the root element. Wraps all the content for the entire page.

  - ```<head> <\head>``` The container for all things you don't want the viewers to see such as keywords, css, and character sets among other things. 

  - ```<meta charset="utf-8">``` gives the character set your document should use.

  - ```<title><\title>``` Gives your page a title. Shows in the browser tab once loaded, also the page description for bookmarking.

  - ```<body><\body>``` Holds all the content that you want the user to see.

  - ```<img src="image.png alt= "test image">``` **src** contains the path to the image and **alt**(short for alternative) is the description of the image in case the image has issues loading. Needs to be descriptive enough so a viewer will have an idea of what the image is.

- **Headings** range from ```<h1 - h6>``` but you mostly only use 3 to 4 headings

- **Lists** To create an unordered list us the ```<ul>``` element. Ordered list will use the ```<ol>``` element. Each item in the list will start with ```<li>```element.

- **Links** to create a link, use the ```<a>``` element with the href="" attribute. The value will go after the href(hypertext reference) attribute. *Example:* ```<a href="[URL]"></a>``` **_Note_** Always click the link to make sure it works properly and takes you to the site you wanted it to go to.

## Semantics

- Semantics is the *meaning* of code. What effect does this line have or the purpose of an element etc...

- Can write an HTML line of code to look like an h1 header but it holds no semantic value. Instead, let html do what it does best and use CSS for what it does best and that is styling.

- When determining the markup to use, you should ask yourself questions such as "What data will best describe the data that will be populated?" and build on that questioning to determine the best elements to use.

- Semantic naming mirrors element naming.

### Semantic Examples

- ```<article>``` used to markup about me page or blog entry. Not to be used in every single paragraph. Whatever is in in the ```<article>``` tag should make sense on its own.

- ```<aside>``` usually a sidebar or call-out box represents part of a document that is indirectly related to the content of the page.

- ```<details>``` creates a disclosure widget.

- ```<figcaption>``` a caption or legend describing the rest of the content.

- ```<time>``` represents how time will be displayed such as a 24 hour clock, a precise date or a duration of time.

- ```<footer>``` typically has information about the author of the section, copyright data, or links to related documents.

- ```<header>``` introductory content, logo, author name, search form, among other things.

- ```<main>``` has dominant content of the ```<body>``` of the document. Content is related directly to or expands upon the topic.

- ```<mark>``` marked or highlighted for reference or notation purposes.

- ```<nav>``` provides navigation links.

- ```<section>``` should always have a heading. Contains standalone section of a document.

- ```<summary>``` specifies summary, caption or legend for the ```<details>``` disclosure box.

- ```<figure>``` self contained content using ```<figcaption>``` element.

[Home](https://cquinn21.github.io/.github.io-reading-notes/index)
