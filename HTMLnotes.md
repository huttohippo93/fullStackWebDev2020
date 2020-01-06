# HTML Basics, Tricks and Tips

## Basics!

Basic syntax for HTMl as well as code examples

### Headings

`<h1> customText </h1>` //This is the largest heading <br>
`<h2> customText </h2>` //This is the second to largest heading <br>
... <br>
... <br>
`<h6> customText </h6>` //This is the smallest heading

### Formatting

`<hr>` //adds a horizontal line, does not require closing tag <br>
`<hr size="3">` //this syntax allows you to modify the horizontal line using attributes <br>
`<br>` //creates a line break, does not require closing tag <br>
`<center> codeToBeCentered </center>` //centers code that falls within the tags <br>
`<!-- Place your comments here -->` //creates a comment

### List

#### Unordered List

```
<ul>
  <li>first item</li>
  <li>second item</li>
  <li>third item</li>
</ul>
```
#### Unordered List Nested

```
<ul>
  <li>first item</li>
  <li>second item     
  <!-- Look, the closing </li> tag is not placed here! -->
    <ul>
      <li>second item first subitem</li>
      <li>second item second subitem
      <!-- Same for the second nested unordered list! -->
        <ul>
          <li>second item second subitem first sub-subitem</li>
          <li>second item second subitem second sub-subitem</li>
          <li>second item second subitem third sub-subitem</li>
        </ul>
      </li> <!-- Closing </li> tag for the li that
                  contains the third unordered list -->
      <li>second item third subitem</li>
    </ul>
  <!-- Here is the closing </li> tag -->
  </li>
  <li>third item</li>
</ul>
```
#### Unordered List With Nested Ordered List

```
<ul>
  <li>first item</li>
  <li>second item
  <!-- Look, the closing </li> tag is not placed here! -->
    <ol>
      <li>second item first subitem</li>
      <li>second item second subitem</li>
      <li>second item third subitem</li>
    </ol>
  <!-- Here is the closing </li> tag -->
  </li>
  <li>third item</li>
</ul>
```
#### Ordered List

```
<ol>
  <li>Fee</li>
  <li>Fi</li>
  <li>Fo</li>
  <li>Fum</li>
</ol>
```
#### Ordered List Using Roman Numerals

```
<ol type="i">
  <li>Introduction</li>
  <li>List of Greivances</li>
  <li>Conclusion</li>
</ol>
```
#### Ordered List Nested

```
<ol>
  <li>first item</li>
  <li>second item  <!-- closing </li> tag not here! -->
    <ol>
      <li>second item first subitem</li>
      <li>second item second subitem</li>
      <li>second item third subitem</li>
    </ol>
  </li>            <!-- Here's the closing </li> tag -->
  <li>third item</li>
</ol>
```
#### Ordered List Using Started Attribute

```
<p>Finishing places of contestants not in the winners’ circle:</p>

<ol start="4">
  <li>Speedwalk Stu</li>
  <li>Saunterin’ Sam</li>
  <li>Slowpoke Rodriguez</li>
</ol>
```
### Boilerplate

```
 <!DOCTYPE html>
 <html>
   <head>
     <meta charset="utf-8">
     <title>  </title>
   </head>
   <body>
   
   </body>
 </html>
```
