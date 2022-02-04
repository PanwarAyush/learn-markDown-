<!-- headings, comments style is as similar of html and heading concept is much similar to html . here hash is used for heading as per the priority  -->
# heading 1
## heading 2
### hading 3
#### heading 4
##### heading 5
###### heading 6

<!-- for italics we use either underscore(_)or asterisk(*)examples are shown below-->
## *this is in italics*
# *this heading is in italics*
## _subheading in italics using underscore_

<!-- to make a text bold we can use double underscore or double asterisk -->
# __this one is a bold heading using underscore__
## **this is a bold subheading using asterisk**

<!--If you are familiar with whatsapp strikethrough(simple cut to a text ) which use tilde sign( ~ ...this one ) then you can get easily familiar with md strike through .This strikethrough use double tlde sign-->

# ~~single~~ double(~~ text ~~) tilde sign
<!--for horizontal rule or a seperator we use three underscore(___) or three hyphens(---)-->

---
___
<!-- if you wanna display *sentence* then you can use backslash(\) with the character you wanna display-->
\*diplaying the asterisk\*
___
---
<!-- now its turn for the blockquote.We can use a simple greater than sign for the blockquote which enhances the look of the line by that blue shady start.-->
 > ## hello , nice if you have read till here
<!--Embedding the link is very easy  ,we just use square brackets and round brackets.if you want that when the link is hovered then a title should should we displayed ,for this feature we use double quotation marks-->

___
> ## [this is the link name](https://thisMayBeThelinkDomainName "double quotations adds the value by giving the title ." )
<!--to make an inline link open in a new tab , we have to  use the syntax{:target="blank"}
[Text to display](link){:target="_blank"}-->
---
<!--mailto is used to avoid creating broken  link of email--> 
 
 > [example@gmail.com](mailto:example@gmail.com)

  [Another text]

---
<!-- ok so next we have list , its concept is same as of html list 
 there are two types of list known as ordered list and unordered list .Ordered list use (1.) for different stuff in the list (look the example below for syntax)
 whereas unordered list use asterisk.to make sublist of a list we simply have to follow the indentation in the syntax-->
 <!-- ordered list -->
 1. this 
 1. is  
 1. ordered
---
<!-- unordered list( we an use hypen too)-->
* this 
  * is  
    * unordered 
       * sublist  
  ---

  ---
  <!--if want to display an inline code or put the code stuff inside the inline code block then we have to use backticks(``). You can get the backtick below escape button -->
  `  <p> inserted a p tag <p> `
___
<!--The way  to insert image to the md file is similar to inserting link, here instead of just using square brackets and round backets we use an exclamation mark behind the square bracket.Caption to the image can be added using asterisk.-->

 ![Markdown logo](https://markdown-here.com/img/icon256.png )*caption to the image*

 ---
 <!-- Now its time for explanation of  github markdown -->

 <!--this is the way to insert codeblock  using three backtick, we can specify the name of the tech or language after those backticks , It will give or add more value to the code block by highlightning code with different shades--> 
 ```html   
 <!DOCTYPE html>
 <head>
   <title>
  </title>
 <head>
 <body>
 </body>
 </html>
 ```
 ---
 ```js 
 npm install 
 ```
```python
def add(x,y):
  return x+y
```
---

<!--Another concept is how to make tables. To we tables we simply use hyphens and vertical bars as shown below-->
|index|  emails                | name|
| --- | --------------------   |---- |
| 1   | example123@gmail.com   | jhon|
| 2   | goodExample@gmail.com  | nina|
---
---
<!-- Task lists => it is a type of check list represented by square brackets , where task is mentioned after square bracket.If there is a X inside that bracket then task is done otherwise task is unfinished.So tasklist is a simple checklist-->

* [x] task 1
* [x] task 2
* [ ] task 3
---
<!-- We can even use <br> tag to break through lines.-->
> hello <br>world
---
<!--the way to insert video is to or for github just drop the link in the markdown-->
[![Little red riding hood](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://youtu.be/StTqXEQ2l-Y)

---
<!--We can put subscript using $ at the begginng and at the end and including caret( ^ ) for superscript and tilde (~ ) for subscript  --> 
<!--superscript example-->
> ## $ (a+b)^2 :arrow_forward: a^2 +b^2 +2ab$.
> ## $ CH_4+2O_2 :arrow_right: CO_2 + 2H_2O$
---
<!--To insert emoji we can copy and paste them or use double colon with emoji code,ex-> :arrow_up: -->
# :airplane: :rocket: :fountain:  :rainbow: :tokyo_tower:  
___
