# Introduction to HTML
    
HTML stands for Hyper Text Markup Language. 
It is the most basic building block of the Web. 
It defines the meaning and structure of web content. 

HyperText means text that has links to other pages.
You can click and jump from one page to another.

Markup Language means a language that uses tags to structure and describe the content.


## Headings

1. HTML headings are titles or subtitles that we want to display on a webpage.
2. There are six heading elements: h1, h2, h3, h4, h5, and h6. Each element represents a different level of content in the document; 
   h1 represents the main heading, h2 represents subheadings, h3 represents sub-subheadings, and so on.

```
<h1>My First Heading</h1>
<h2>My Second Heading</h2>
<h3>My Third Heading</h3>
<h4>My Fourth Heading</h4>
<h5>My Fifth Heading</h5>
<h6>My Sixth Heading</h6> 
```

```   
<h1>Book</h1>

<h2>Chapter 1</h2>
<h3>Section 1</h3>
<h3>Section 2</h3>
<h3>Section 3</h3>

<h2>Chapter 2</h2>
<h3>Section 1</h3>
<h3>Section 2</h3>
<h3>Section 3</h3>

<h2>Chapter 3</h2>
<h3>Section 1</h3>
<h3>Section 2</h3>
<h3>Section 3</h3>
```

3. Headings not only help to organize content but also improve accessibility and SEO by providing structure to the webpage.
4. Using headings appropriately helps users and search engines understand the hierarchy and organization of the content on your webpage.

Note: Use HTML headings for headings only. Don't use headings to make text BIG or bold.


## Paragraphs

1. A paragraph always starts on a new line, and is usually a block of text.
2. Browsers automatically add some white space (a margin) before and after a paragraph.

```
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

Output:

<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

3. The browser will automatically remove any extra spaces and lines when the page is displayed.

```
<p>
This paragraph
contains         a lot of   lines and       spaces
in the source         code,
but the        browser
ignores it.
</p>
```

Output:

<p>
This paragraph
contains         a lot of   lines and       spaces
in the source         code,
but the        browser
ignores it.
</p>

```
<p>lorem10</p>
```

Output:

Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem, consequatur.

Note: “Lorem” ya “Lorem ipsum” ek dummy / placeholder text hota hai jo designers, developers, content writers testing ke liye use karte hain. Iska real meaning kuch nahi hota. Ye sirf dikhane ke liye hota hai ki jab content aa jayega toh woh kaisa dikhega. 
lorem + numberinput, like lorem10 and then enter press karne se aapko utne words ka lorem ipsum text mil jayega. 

```
<h1>Welcome to My Coding Blog</h1>
<h2>Introduction to Web Devlopment</h2>
<p>Web development is the process of creating websites and web applications.</p>

<h2>HTML Basics</h2>
<p>HTML is the foundation of the web devlopment.</p>

<h2>CSS for Styling</h2>
<p>CSS is used to make web pages visually appealing.</p>

<h2>JavaScript for Interactivity</h2>
<p>JavaScript allows you to add interactivity to your web pages.</p> 
```


## Horizontal Rules (hr)

1. The hr tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.
2. The hr element is used to separate content (or define a change) in an HTML page.
3. The hr tag is an empty tag, which means that it has no end tag.
4. In XHTML documents, write this element as `<hr />`.

```
<p>This is some text.</p>
<hr>
<p>This is some other text.</p>
<hr>
```

Output:

<p>This is some text.</p>
<hr>
<p>This is some other text.</p>
<hr>


## Line Breaks (br)

1. Use br if you want a line break (a new line) without starting a new paragraph:
2. The br tag is an empty tag, which means that it has no end tag.
3. It is useful for writing a poem or an address, where the division of lines is significant.
4. In XHTML documents, write this element as `<br />`.

```
<p>This is <br> a paragraph <br> with line breaks.</p> 
```

Output:

<p>This is <br> a paragraph <br> with line breaks.</p>

```
Mozilla<br />
331 E. Evelyn Avenue<br />
Mountain View, CA<br />
94041<br />
USA<br />
```

Output:

Mozilla<br />
331 E. Evelyn Avenue<br />
Mountain View, CA<br />
94041<br />
USA<br />

```
<p>
O’er all the hilltops<br />
  Is quiet now,<br />
  In all the treetops<br />
  Hearest thou<br />
  Hardly a breath;<br />
  The birds are asleep in the trees:<br />
  Wait, soon like these<br />
  Thou too shalt rest.
</p>  
```

Output:

O’er all the hilltops<br />
  Is quiet now,<br />
  In all the treetops<br />
  Hearest thou<br />
  Hardly a breath;<br />
  The birds are asleep in the trees:<br />
  Wait, soon like these<br />
  Thou too shalt rest.

Note: 
1. If we write the `<br>` tag directly without backticks, Markdown will treat it like a real line break and not as normal text.
2. If we don’t use backticks, Markdown will treat HTML as real code and it may run or render instead of showing as plain text.
3. Backticks are used to show code as text in Markdown, so the code doesn’t run and appears exactly as written. like `<br />`.
4. Single backtick (`) small words / short code ke liye use hota hai.
5. Triple backtick (```) bada code block / multiple lines ke liye use hota hai. 


## Preformatted Text (pre)

1. The pre tag represents preformatted text which is to be presented exactly as written in the HTML file.
2. It preserves both spaces and line breaks.

```
<pre>
    Roses are red,
       
     Violets are blue.
   

 This is preformatted text,
        Just for you.
</pre>
```

Output:

<pre>
    Roses are red,
       
     Violets are blue.
   

 This is preformatted text,
        Just for you.
</pre>



Note:
1. Render: Means the HTML tag shows its visual effect on the screen (in Live Preview or browser).
2. Run: Means the logic gets executed and produces output.
3. HTML: only renders, it does not run.
4. Markdown: preview also renders HTML with its own styling.