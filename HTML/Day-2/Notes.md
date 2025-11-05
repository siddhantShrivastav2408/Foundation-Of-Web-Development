# HTML Lists

## Unordered HTML List

1. An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.
2. The list items will be marked with bullets (small black circles) by default:

```
<ul>
    <li>HTML</li>
    <Li>CSS</Li>
    <li>JavaScript</li>
</ul>
```

Output:

<ul>
    <li>HTML</li>
    <Li>CSS</Li>
    <li>JavaScript</li>
</ul>

Note:
1. yahan par sirf bullet points aa rhe hai, inko change kr skte hai with the help of some attributes.
2. Attributes ka simple matlab:
tag ke andar extra information / property dena
jisse browser ko zyada detail mile.
3. attributes ko samajhne ka foundation rule bas ye 3 cheezein hoti hain:

(a) name (attribute ka naam) - ye batata hai kis cheez ko control kar rahe ho jaise: href , src , id , class , type , style …etc

(b) = (equals sign) - ye attribute ko uski value assign karta hai.

(c) value (jo data ya configuration dena hai) - ye double quotes " " ke andar hoti hai.

```
<ul style="list-style-type: disc;">
    <li>Apple</li>
    <li>Mango</li>
</ul>
```

Output:

<ul style="list-style-type: disc;">
    <li>Apple</li>
    <li>Mango</li>
</ul>

```
<ul style="list-style-type: circle;">
    <li>Apple</li>
    <li>Mango</li>
</ul>
```

Output:

<ul style="list-style-type: circle;">
    <li>Apple</li>
    <li>Mango</li>
</ul>

```
<ul style="list-style-type: square;">
    <li>Apple</li>
    <li>Mango</li>
</ul>
```

Output:

<ul style="list-style-type: square;">
    <li>Apple</li>
    <li>Mango</li>
</ul>

```
<ul style="list-style-type: none;">
    <li>Apple</li>
    <li>Mango</li>
</ul>
```

Output:

<ul style="list-style-type: none;">
    <li>Apple</li>
    <li>Mango</li>
</ul>


## Ordered HTML List

1. An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.
2. The list items will be marked with numbers by default:

```
<ol>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ol>
```

Output:

<ol>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ol>

Note:
1. yahan par sirf numbers aa rhe hai, inko change kr skte hai with the help of some attributes.

(a) type attribute - ye define karta hai numbering kis format mein hogi.

```
<ol type="1">
  <li>Apple</li>
  <li>Mango</li>
</ol>
```

Output:

<ol type="1">
  <li>Apple</li>
  <li>Mango</li>
</ol>

```
<ol type="A">
  <li>Apple</li>
  <li>Mango</li>
</ol>
```

Output:

<ol type="A">
  <li>Apple</li>
  <li>Mango</li>
</ol>

```
<ol type="a">
  <li>Apple</li>
  <li>Mango</li>
</ol>
```

Output:

<ol type="a">
  <li>Apple</li>
  <li>Mango</li>
</ol>

```
<ol type="I">
  <li>Apple</li>
  <li>Mango</li>
</ol>
```

Output:

<ol type="I">
  <li>Apple</li>
  <li>Mango</li>
</ol>

```
<ol type="i">
  <li>Apple</li>
  <li>Mango</li>
</ol>
```

output:

<ol type="i">
  <li>Apple</li>
  <li>Mango</li>
</ol>


(b) start attribute - ye batata hai numbering kis number se start hogi.

```
<ol start="5">
  <li>Item</li>
  <li>Item</li>
</ol>
```

Output:

<ol start="5">
  <li>Item</li>
  <li>Item</li>
</ol>


## Anchor Tag

1. The `<a>` tag defines a hyperlink, which is used to link from one page to another.
2. The most important attribute of the `<a>` element is the href attribute, which indicates the link's destination.

```<a href="url">link text</a>```

``` <a href="https://www.w3schools.com/">w3schools</a> ```

Output:  <a href="https://www.w3schools.com/">w3schools</a> 

3. The target Attribute - The target attribute can have one of the following values:

(a) _self - Default. Opens the document in the same window/tab as it was clicked

(b) _blank - Opens the document in a new window or tab

``` <a href="https://www.w3schools.com/" target="_blank">w3schools</a> ```

Output: <a href="https://www.w3schools.com/" target="_blank">w3schools</a>

4. How to link to an email address:

``` <a href="mailto:someone@example.com">Send email</a> ```

Output:

<a href="mailto:someone@example.com">Send email</a> 

(a) mailto: browser ko ye batata hai ki jo link diya hai woh email open karne ke liye hai, web page open karne / kisi URL pe jaane ke liye nhi hai.

(b) mailto: nhi likhege agar toh browser ye soch lega ki ye ek normal website link hai toh click karne par browser try karega open karne ka toh error milega.

5. How to link to a phone number:

``` <a href="tel:+4733378901">+47 333 78 901</a> ```

Output:

<a href="tel:+4733378901">+47 333 78 901</a> 

(a) tel: browser ko ye batata hai ki ye link phone dial karne ke liye hai.

(b) tel: nhi likhege agar toh browser ye soch lega ki ye ek normal website link hai toh click karne par browser try karega open karne ka toh error milega.

Note: 
1. mailto: and tel: are NOT attributes. They are URI schemes used inside the href attribute to tell the browser “this link is for email” or “this link is for phone call”.

2. URI scheme is the first part of a URL that tells the browser which type of action to perform (open website, open phone dialer, open email app, etc).


## Image Tag

1. The HTML `<img>` tag is used to embed an image in a web page.
2. The `<img>` tag is empty, it contains attributes only, and does not have a closing tag.
3. The `<img>` tag has two required attributes:

(a) src - Specifies the path to the image

(b) alt - Specifies an alternate text for the image - The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

``` <img src="url" alt="alternatetext"> ```

Tip: A screen reader is a software program that reads the HTML code, and allows the user to "listen" to the content. Screen readers are useful for people who are visually impaired or learning disabled.

4. You can use the width and height attributes:

``` <img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600"> ```

Note: Always specify the width and height of an image. If width and height are not specified, the web page might flicker while the image loads.

5. Image as a Link - To use an image as a link, put the `<img>` tag inside the `<a>` tag:

```
<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial" width="42" height="42">
</a>
```

Note: If src works, the image shows. The alt text only appears when the image fails to load.

Inshort:

```
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-AgR8Uqu9ua-EJ45sBiGvJ8ojVX4SUXOJXQ&s">  
```

by default image apni original size mein hi appear hogi agar height aur width attribute na diya ho toh

Output:

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-AgR8Uqu9ua-EJ45sBiGvJ8ojVX4SUXOJXQ&s">  

```
<img src="https://encryd-tbn0.gstatic.com/ima?q=tbn:ANd9GcS-R8Uqu9ua-EBiGvJ8SUXOJXQ&s" alt="kk image">
```

agar src wrong hai → image load nhi hogi → tab HTML fallback ke taur par alt text show karta hai

Output:

<img src="https://encryd-tbn0.gstatic.com/ima?q=tbn:ANd9GcS-R8Uqu9ua-EBiGvJ8SUXOJXQ&s" alt="kk image">

```
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-AgR8Uqu9ua-EJ45sBiGvJ8ojVX4SUXOJXQ&s" alt="kk image" height="50" width="70">
```

height aur width attribute use karke image ka size change kar sakte hai

Output:

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-AgR8Uqu9ua-EJ45sBiGvJ8ojVX4SUXOJXQ&s" alt="kk image" height="50" width="70">


```
<a href="https://www.youtube.com/@JubinNautiyal" target="_blank">
        <img src="https://s.saregama.tech/image/c/m/5/4c/9d/jubin-nautiyal_1689336392.jpg" alt="Jubin Nautiyal" width="100" height="100">
        </a>
        <p>His voice is so soothing.</p>
```

Image as a Link - To use an image as a link, put the `<img>` tag inside the `<a>` tag:

Output:

<a href="https://www.youtube.com/@JubinNautiyal" target="_blank">
        <img src="https://s.saregama.tech/image/c/m/5/4c/9d/jubin-nautiyal_1689336392.jpg" alt="Jubin Nautiyal" width="100" height="100">
        </a>
        <p>His voice is so soothing.</p>