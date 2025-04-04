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
</details>
<hr><hr>


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
</details>
<hr><hr>


## องค์ประกอบ HTML(HTML Elements)
[HTML Tag Reference](https://www.w3schools.com/tags/default.asp)
<hr><hr>


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
</details>
<hr><hr>


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
</details>
<hr><hr>


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
</details>
<hr><hr>


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
</details>
<hr><hr>


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
</details>
<hr><hr>


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