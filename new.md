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

---
<!-- ok so next we have list , its concept is same as of html list 
 there are two types of list known as ordered list and unordered list .Ordered list use (1.) for different stuff in the list (look the example below for syntax)
 whereas unordered list use asterisk.to make sublist of a list we simply have to follow the indentation in the syntax-->
 <!-- ordered list -->
 1. this 
 1. is  
 1. ordered
---
<!-- unordered list-->
* this 
  * is  
    * unordered 
       * sublist  
  ---
  <!--if want to display an inline code or put the code stuff inside the inline code block then we have to use backticks(``). You can get the backtick below escape button -->
  `  <p> inserted a p tag <p> `
___
<!--The way  to insert image to the md file is similar to inserting link, here instead of just using square brackets and round backets we use an exclamation mark behind the square bracket-->

 ![Markdown logo](https://markdown-here.com/img/icon256.png)

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
