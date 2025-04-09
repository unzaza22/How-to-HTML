# How-to-HTML
W3 School


## HTML เริ่มต้น(HTML Introduction)
<details>  
  <summary>HTML เริ่มต้น(HTML Introduction)</summary>

  ### HTML ง่ายๆ(A Simple HTML Document)
  ```html
  <!DOCTYPE html>
  <html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
      
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
      
  </body>
  </html>
  ```
<hr>

### องค์ประกอบ HTML(What is an HTML Element?)
องค์ประกอบจะต้องเริ่มด้วย tag, เนื้อหา, และตามด้วยปิด tag
| Start tag | Element content | Endtag |
| --- | ---| --- |
| `<h1>` | หัวข้อแรก | `</h1>` |
| `<p>` | ย่อหน้าแรก | `</p>` |
| `<br>` | none | none |
> Note: องค์ประกอบบ้างอย่างไม่จำเป็นต้องมีเนื้อหาและปิด tag เช่น `<br>`
<hr>

### โครงสร้างหน้าตาของ HTML(HTML Page Structure)
![HTML page structure](image.png)
<hr>

### ความเป็นมาของ HTML(HTML History)
| Year | Version |
| --- | --- |
| 1989 | Tim Berners-Lee invented www |
| 1991 | Tim Berners-Lee invented HTML |
| 1993 | Dave Raggett drafted HTML+ |
| 1995 | HTML Working Group defined HTML 2.0 |
| 1997 | W3C Recommendation: HTML 3.2 |
| 1999 | W3C Recommendation: HTML 4.01 | 
| 2000 | W3C Recommendation: XHTML 1.0 |
| 2008 | WHATWG HTML5 First Public Draft |
| 2012 | WHATWG HTML5 Living Standard | 
| 2014 | W3C Recommendation: HTML5 | 
| 2016 |	W3C Candidate Recommendation: HTML 5.1 | 
| 2017 | W3C Recommendation: HTML5.1 2nd Edition | 
| 2017 | W3C Recommendation: HTML5.2 |
<hr>
</details>
<hr>


## พื้นฐาน HTML(HTML Basic)
<details>
  <summary>ตัวอย่างพื้นฐาน HTML(HTML Basic Exaples)</summary>

  ### HTML Documents
  ```html
  <!DOCTYPE html>
  <html>
  <body>

    <h1>My First Heading</h1>
    <p>My first paragraph.</p>

  </body>
  </html>
  ```
<hr>

  ### คำประกาศ <!DOCTYPE>(The <!DOCTYPE> Declaration)
  ```html
  <!DOCTYPE html>
  ```
<hr>

  ### หัวข้อ HTML(HTML Headings)
  ```html
  <h1>This is heading 1</h1>
  <h2>This is heading 2</h2>
  <h3>This is heading 3</h3>
  ```
<hr>

  ### ย่อหน้า HTML(HTML Paragraphs)
  ```html
  <p>This is a paragraph.</p>
  <p>This is another paragraph.</p>
  ```
<hr>

  ### ลิงค์ HTML(HTML Links)
  ```html
  <a href="https://www.w3schools.com">This is a link</a>
  ```
<hr>

  ### รูปภาพ HTML(HTML Images)
  ```html
  <img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
  ```
<hr>
</details>
<hr>


## องค์ประกอบ HTML(HTML Elements)
[HTML Tag Reference](https://www.w3schools.com/tags/default.asp)
<hr>


## HTML Attributes
<details>
  <summary>The href Attribute</summary>

  ```html
  <a href="https://www.w3schools.com">Visit W3Schools</a>
  ```
  [HTML Links chapter](https://www.w3schools.com/html/html_links.asp)
<hr>
</details>

<details>
  <summary>The Image Attributes</summary>

  #### The src Attribute
  ```html
  <img src="img_girl.jpg">
  ```

  #### The width and height Attributes
  ```html
  <img src="img_girl.jpg" width="500" height="600">
  ```

  #### The alt Attribute
  ```html
  <img src="img_girl.jpg" alt="Girl with a jacket">
  ```
  [HTML Images chapter](https://www.w3schools.com/html/html_images.asp)
<hr>
</details>

<details>
  <summary>The style Attribute</summary>

  ```html
  <p style="color:red;">This is a red paragraph.</p>
  ```
  [HTML Styles chapter](https://www.w3schools.com/html/html_styles.asp)
<hr>
</details>

<details>
  <summary>The lang Attribute</summary>

  กำหนด country ในการ search

  ```html
  <!DOCTYPE html>
  <html lang="en">
  <body>
  ...
  </body>
  </html>
  ```
  Or
  ```html
  <!DOCTYPE html>
  <html lang="en-US">
  <body>
  ...
  </body>
  </html>
  ```
  [HTML Language Code Reference](https://www.w3schools.com/tags/ref_language_codes.asp)
<hr>
</details>

<details>
  <summary>The title Attribute</summary>
  ข้อมูลเพิ่มเติมหรือ tooltip
  
  <br>

  ```html
  <p title="I'm a tooltip">This is a paragraph.</p>
  ```  
<hr>
</details>


<details>
  <summary>Single or Double Quotes?</summary>
  ใช้แบบใดก็ได้เพื่อให้ quotes ใช้งานได้

  <br>

  ```html
  <p title='John "ShotGun" Nelson'>
  ```  
  Or
  ```html
  <p title="John 'ShotGun' Nelson">
  ```  
<hr>
</details>
<hr>


## การใช้งานหัวข้อ(HTML Headings)
<details>
  <summary>HTML Headings</summary>

  ```html
  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h6>
  ```
<hr>  
</details>

<details>
  <summary>กำหนดขนาดอักษรหัวข้อ(Bigger Headings)</summary>

  ```html
  <h1 style="font-size:60px;">Heading 1</h1>
  ```  
<hr>
</details>

<details>
  <summary>HTML Tag Reference</summary>

  | Tag | Description |
  | --- | ---|
  | `<html>` | กำหนดให้ว่าเป็น HTML |
  | `<body>` | กำหนดส่วนเนื้อหา |
  | `<h1> to <h6>` | กำหนดหัวข้อ |
  [HTML Tag Reference](https://www.w3schools.com/tags/default.asp)
<hr>
</details>
<hr>


## วิธีใช้งานย่อหน้า(HTML Paragraphs)
<details>
  <summary>HTML Paragraphs</summary>

  ```html
  <p>This is a paragraph.</p>
  <p>This is another paragraph.</p>
  ```  
<hr>
</details>

<details>
  <summary>การแสดงผล(HTML Display)</summary>
  ย่อหน้าจะตัดเว้นวรรคออกไม่ว่างจะใช้เยอะแค่ไหน
  <br>
  input:

  ```html
  <p>
  This paragraph
  contains a lot of lines
  in the source code,
  but the browser
  ignores it.
  </p>

  <p>
  This paragraph
  contains         a lot of spaces
  in the source         code,
  but the        browser
  ignores it.
  </p>
  ```  
  output:
    <p>
  This paragraph
  contains a lot of lines
  in the source code,
  but the browser
  ignores it.
  </p>

  <p>
  This paragraph
  contains         a lot of spaces
  in the source         code,
  but the        browser
  ignores it.
  </p>
<hr>
</details>

<details>
  <summary>ขีดเส้นแนวนอน(HTML Horizontal Rules)</summary>

  ```html
  <hr>
  ```  
<hr>
</details>

<details>
  <summary>ขึ้นบรรทัดใหม่(HTML Line Breaks)</summary>
  input:

  ```html
  <p>This is<br>a paragraph<br>with line breaks.</p>
  ```  
  output:
  <p>This is<br>a paragraph<br>with line breaks.</p>
<hr>
</details>

<details>
  <summary>ย่อหน้าแบบไม่กำหนดรูปแบบ(The HTML &lt;pre&gt; Element)</summary>
  &lt;pre&gt; จะไม่สนใจการเว้นวรรค

  ```html
  <pre>
    My Bonnie lies over the ocean.

    My Bonnie lies over the sea.

    My Bonnie lies over the ocean.

    Oh, bring back my Bonnie to me.
  </pre>
  ```  
<hr>
</details>

<details>
  <summary>HTML Tag Reference</summary>

  | Tag | Description |
  | --- | ---|
  | `<p>` | กำหนดเป็น ย่อหน้า |
  | `<hr>` | ขีดเส้นแนวนอน |
  | `<br>` | ขึ้นบรรทัดใหม่ |
  | `<pre>` | กำหนดข้อความแบบไม่จัดรูปแบบ |
<hr>
</details>
<hr>


## กำหนดรูปแบบ HTML(HTML Styles)
กำหนดองค์ประกอบ เช่น color, font, size
<details>
  <summary>กำหนดรูปแบบ(The HTML Style Attribute)</summary>

  ```html
  <tagname style="property:value;">
  ```  
<hr>
</details>

<details>
  <summary>สีพื้นหลัง(Background Color)</summary>
  input:

  ```html
  <body style="background-color:powderblue;">

  <h1 style="background-color:powderblue;">This is a heading</h1>
  <p style="background-color:tomato;">This is a paragraph.</p>

  </body>
  ```  
  output:
  <body style="background-color:powderblue;">

  <h1 style="background-color:powderblue;">This is a heading</h1>
  <p style="background-color:tomato;">This is a paragraph.</p>

  </body>
<hr>
</details>

<details>
  <summary>สีข้อความ(Text Color)</summary>
  input:

  ```html
  <h1 style="color:blue;">This is a heading</h1>
  <p style="color:red;">This is a paragraph.</p>
  ```  
  output:
  <h1 style="color:blue;">This is a heading</h1>
  <p style="color:red;">This is a paragraph.</p>
<hr>
</details>

<details>
  <summary>กำหนดรูปแบบ Font(Fonts)</summary>
  input:

  ```html
  <h1 style="font-family:verdana;">This is a heading</h1>
  <p style="font-family:courier;">This is a paragraph.</p>
  ```  
  output:
  <h1 style="font-family:verdana;">This is a heading</h1>
  <p style="font-family:courier;">This is a paragraph.</p>
<hr>
</details>

<details>
  <summary>ขนาด Font(Text Size)</summary>
  input:

  ```html
  <h1 style="font-size:300%;">This is a heading</h1>
  <p style="font-size:160%;">This is a paragraph.</p>
  ```  
  output:
  <h1 style="font-size:300%;">This is a heading</h1>
  <p style="font-size:160%;">This is a paragraph.</p>
<hr>
</details>

<details>
  <summary>ตำแหน่ง Font(Text Alignment)</summary>
  input:

  ```html
  <h1 style="text-align:center;">Centered Heading</h1>
  <p style="text-align:center;">Centered paragraph.</p>
  ```  
  output:
  <h1 style="text-align:center;">Centered Heading</h1>
  <p style="text-align:center;">Centered paragraph.</p>
<hr>
</details>
<hr>


## รูปแบบ Font(HTML Formatting)
<details>
  <summary>รูปแบบองค์ประกอบ(HTML Formatting Elements)</summary>

  | Tag | Description |
  | --- | ---|
  | `<b>` | ตัวหนา |
  | `<strong>` | ตัวหนาและสำคัญกว่า |
  | `<i>` | ตัวเอียง |
  | `<em>` | ตัวเอียงแต่สำคัญกว่า |
  | `<mark>` | Highlight |
  | `<small>` | กำหนดข้อความให้เล็ก |
  | `<del>` | ขีดเส้นกลางทับ Font |
  | `<ins>` | ขีดเส้นใต้ |
  | `<sub>` | ตัวห้อย |
  | `<sup>` | ยกกำลัง |
<hr>
</details>
<hr>


## การอ้างอิ้ง(HTML Quotations)
<details>
  <summary>การอ้างอิ้งแบบบล็อก(HTML &lt;blockquote&gt; for Quotations)</summary>

    ```html
    <p>Here is a quote from WWF's website:</p>
    <blockquote cite="http://www.worldwildlife.org/who/index.html">
    For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
    </blockquote>
    ``` 
<hr> 
</details>

<details>
  <summary>การอ้างอิ้งแบบสั้น(HTML &lt;q&gt; for Short Quotations)</summary>
  input:

  ```html
  <p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
  ```  
  output:
  <p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
<hr>
</details>

<details>
  <summary>การอ้างอิ้งงานแบบแสดงการใช้คำย่อ(HTML &lt;abbr&gt; for Abbreviations)</summary>
  input:

  ```html
  <p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
  ```  
  output:
  <p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
<hr>
</details>

<details>
  <summary>การอ้างแบบที่อยู่(HTML <&lt;address&gt; for Contact Information)</summary>
  input:

  ```html
  <address>
  Written by John Doe.<br>
  Visit us at:<br>
  Example.com<br>
  Box 564, Disneyland<br>
  USA
  </address>
  ```  
  output:
  <address>
  Written by John Doe.<br>
  Visit us at:<br>
  Example.com<br>
  Box 564, Disneyland<br>
  USA
  </address>
<hr>
</details>

<details>
  <summary>การอ้างอิ้งของหัวข้อชิ้นงาน(HTML &lt;cite&gt; for Work Title)</summary>
  input:

  ```html
  <p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
  ``` 
  output: 
  <p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
<hr>
</details>

<details>
  <summary>กำหนดทิศทางข้อความ(HTML &lt;bdo&gt; for Bi-Directional Override)</summary>
  input:

  ```html
  <bdo dir="rtl">This text will be written from right to left</bdo>
  ```
  output:  
  <bdo dir="rtl">This text will be written from right to left</bdo>
<hr>
</details>

<details>
  <summary>HTML Quotation and Citation Elements</summary>

  | Tag | Description |
  | --- | ---|
  | `<abbr>` | การอ้างอิ้งแบบใช้คำย่อ |
  | `<address>` | การอ้างอิ้งแบบที่อยู่ |
  | `<bdo>` | กำหนดทิศทางข้อความ ทิศทางจริงๆเลย |
  | `<blockquote>` | การอ้างอิ้งแบบเอกสาร |
  | `<cite>` | การอ้างอิ้งชื่อผลงาน |
  | `<q>` | การอ้างอิ้งแบบสั้น |
<hr>
</details>
<hr>


## ความคิดเห็น(HTML Comments)
<details>
  <summary>แท็กความคิดเห็น(HTML Comment Tag)</summary>

  ```html
  <!-- Write your comments here -->

  <p>This is a paragraph.</p>
  <!--
  <p>Look at this cool image:</p>
  <img border="0" src="pic_trulli.jpg" alt="Trulli">
  -->
  <p>This is a paragraph too.</p>

  <p>This <!-- great text --> is a paragraph.</p>
  ```  
<hr>
</details>
<hr>


## การใช้งานสี(HTML Colors)
<details open>
  <summary>สี(Colors)</summary>
  <details>
    <summary>สีพื้นหลัง(Background Color)</summary>
    input:

    ```html
    <h1 style="background-color:DodgerBlue;">Hello World</h1>
    <p style="background-color:Tomato;">Lorem ipsum...</p>
    ```  
    output:
    <h1 style="background-color:DodgerBlue;">Hello World</h1>
    <p style="background-color:Tomato;">Lorem ipsum...</p>
  <hr>
  </details>

  <details>
    <summary>สีตัวอักษร(Text Color)</summary>
    input:

    ```html
    <h1 style="color:Tomato;">Hello World</h1>
    <p style="color:DodgerBlue;">Lorem ipsum...</p>
    <p style="color:MediumSeaGreen;">Ut wisi enim...</p>
    ```  
    output:
    <h1 style="color:Tomato;">Hello World</h1>
    <p style="color:DodgerBlue;">Lorem ipsum...</p>
    <p style="color:MediumSeaGreen;">Ut wisi enim...</p>
  <hr>
  </details>

  <details>
    <summary>สีกรอบ(Border Color)</summary>
    input:

    ```html
    <h1 style="border:2px solid Tomato;">Hello World</h1>
    <h1 style="border:2px solid DodgerBlue;">Hello World</h1>
    <h1 style="border:2px solid Violet;">Hello World</h1>
    ```  
    output:
    <h1 style="border:2px solid Tomato;">Hello World</h1>
    <h1 style="border:2px solid DodgerBlue;">Hello World</h1>
    <h1 style="border:2px solid Violet;">Hello World</h1>
  <hr>
  </details>

  <details>
    <summary>ค่าของสี(Color Values)</summary>
    input:

    ```html
    <h1 style="background-color:rgb(255, 99, 71);">rgb(255, 99, 71)</h1>
    <h1 style="background-color:#ff6347;">#ff6347</h1>
    <h1 style="background-color:hsl(9, 100%, 64%);">hsl(9, 100%, 64%)</h1>

    <h1 style="background-color:rgba(255, 99, 71, 0.5);">rgba(255, 99, 71, 0.5)</h1>
    <h1 style="background-color:hsla(9, 100%, 64%, 0.5);">hsla(9, 100%, 64%, 0.5)</h1>
    ```  
    output:
    <h1 style="background-color:rgb(255, 99, 71);">rgb(255, 99, 71)</h1>
    <h1 style="background-color:#ff6347;">#ff6347</h1>
    <h1 style="background-color:hsl(9, 100%, 64%);">hsl(9, 100%, 64%)</h1>

    <h1 style="background-color:rgba(255, 99, 71, 0.5);">rgba(255, 99, 71, 0.5)</h1>
    <h1 style="background-color:hsla(9, 100%, 64%, 0.5);">hsla(9, 100%, 64%, 0.5)</h1>
  <hr>
  </details>
<hr>
</details>

<details>
  <summary>RGB</summary>
  rgb(red, green, blue)<br><br>

  rgb(60, 60, 60)<br>
  rgb(240, 240, 240)

  rgba(red, green, blue, alpha)<br>
  alpha = ความโปร่งใส
<hr>
</details>

<details>
  <summary>HEX</summary>
  #rrggbb <br><br>

  #404040<br>
  #f8f8f8
<hr>
</details>

<details>
  <summary>HSL</summary>
  hsl(hue, saturation, lightness)<br><br>

  hsla(hue, saturation, lightness, alpha)
<hr>
</details>
<hr>


## HTML CSS
<details>
  <summary>HTML Styles - CSS</summary>

  ### การใช้งาน CSS(Using CSS)
  มี 3 วิธี
  1. Inline - การใช้ `style` ใน HTML element
  2. Internal - การใช้ `<style>` ใน `<head>` section
  3. External - การใช้ `<link>` เพื่อใช้งานกับ CSS file ที่สร้างเอง

  ### Inline
  ```html
  <h1 style="color:blue;">A Blue Heading</h1>

  <p style="color:red;">A red paragraph.</p>
  ``` 

  ### Internal CSS
  การใช้งาน `<style>` ใน `<head>` Section
  ```html
  <!DOCTYPE html>
  <html>
  <head>
  <style>
  body {background-color: powderblue;}
  h1   {color: blue;}
  p    {color: red;}
  </style>
  </head>
  <body>

  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>

  </body>
  </html>
  ``` 

  ### External CSS
  เพิ่ม `<link>` ใน `<head>` Section
  ```html
  <!DOCTYPE html>
  <html>
  <head>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>

  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>

  </body>
  </html>
  ``` 
  "styles.css":
  ```css
  body {
    background-color: powderblue;
  }
  h1 {
    color: blue;
  }
  p {
    color: red;
  }
  ``` 
 <hr> 
</details>

<details>
  <summary>CSS Color, Fonts and Sizes</summary>
  
  `color` - สีของสิ่งต่างๆ<br>
  `font-family` - กำหนดรูปแบบของ font<br>
  `font-size` - กำหนดขนาดของ font
  ```html
  <head>
  <style>
  h1 {
    color: blue;
    font-family: verdana;
    font-size: 300%;
  }
  p {
    color: red;
    font-family: courier;
    font-size: 160%;
  }
  </style>
  </head>
  ```  
<hr>
</details>

<details>
  <summary>กรอบข้อความ(CSS Border)</summary>

  ```css 
    p {
    border: 2px solid powderblue;
  }
  ```  
<hr>   
</details>

<details>
  <summary>ความห่างด้านในของกรอบ(CSS Padding)</summary>

  ```css
  p {
    border: 2px solid powderblue;
    padding: 30px;
  }
  ```  
<hr>
</details>

<details>
  <summary>ความห่างด้านนอกของกรอบ(CSS Margin)</summary>

  ```css
  p {
    border: 2px solid powderblue;
    margin: 50px;
  }
  ```  
<hr>
</details>

<details>
  <summary>Link to External CSS</summary>
  สามารถใช้ Full URL หรือ path ในการใช้งานได้

  ```html
  <link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">

  <link rel="stylesheet" href="/html/styles.css">

  <link rel="stylesheet" href="styles.css">
  ```  
  [HTML File Paths](https://www.w3schools.com/html/html_filepaths.asp)
<hr>
</details>

<details>
  <summary>Chapter Summary</summary>

  - ใช้ `style` เพื่อกำหนดแบบ inline
  - ใช้ `<style>` เพื่อกำหนดแบบ internal CSS
  - ใช้ `<link>` เพื่อกำหนดแบบ external CSS
  - ใน `<head>` section กำหนด &lt;style&gt; and &lt;link&gt;
  - ใช้ `color` ในการกำหนดสีข้อความ
  - ใช้ `font-family` ในการกำหนดรูปแบบข้อความ
  - ใช้ `font-size` ในการกำหนดขนาดข้อความ
  - ใช้ `border` เพื่อสร้างกรอบของข้อความ
  - ใช้ `padding` เพื่อกำหนดความห่างของกรอบด้านในข้อความ
  - ใช้ `margin` เพื่อกำหนดความห่างของกรอบด้านนอกข้อความ

  [CSS Tutorial](https://www.w3schools.com/css/default.asp)
<hr>
</details>

<details>
  <summary>HTML Style Tags</summary>

  | Tag | Description |
  | --- | ---|
  | `<style>` | กำหนดรูปแบบ |
  | `<link>` | กำหนด URL ภายนอกหรือ path |
  [HTML Tag Reference](https://www.w3schools.com/tags/default.asp)
<hr>
</details>


<!-- Template -->
# Template
<details>
  <summary>&lt; &gt;</summary>

  ```html
  ```  
</details>

|  |  |  |
| --- | ---| --- |
| `<>` |  | `<>` |
| `<>` |  | `<>` |
| `<>` |  |  |