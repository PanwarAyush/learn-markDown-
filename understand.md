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

<!--If you are familiar with whatsapp strikethrough(simple cut to a text ) which use tilde sign( ~ ...this one ) then you can get easily familiar with md strike through .This     strikethrough use double tlde sign-->

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
[![youtube here](https://www.typinggames.zone/web/game-thumbnails/Typing_Racer-small.png)](https://www.youtube.com/watch?v=JcLlQEkQk0A)

---
<!--We can put subscript using $ at the begginng and at the end and including caret( ^ ) for superscript and tilde (~ ) for subscript  --> 
<!--superscript example-->
> ## $ (a+b)^2 :arrow_forward: a^2 +b^2 +2ab$.
> ## $ CH_4+2O_2 &rarr; CO_2 + 2H_2O$
---
<!--To insert emoji we can copy and paste them or use double colon with emoji code,ex-> :arrow_up: -->
# :airplane: :rocket: :fountain:  :rainbow: :tokyo_tower:  
___
<!--To add number of profile views of your github account,just insert the github id name inside curly braces -->

<!--  this is visitor count of github & followers-->
#  **Profile Views**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Visitor Count](https://profile-counter.glitch.me/{PanwarAyush}/count.svg)
<div align="center">
<img src="https://img.shields.io/github/followers/PanwarAyush.svg?style=social&label=Follow"></img>

<img src="https://gpvc.arturio.dev/PanwarAyush"></img>
</div>

---

<!--A cool way to display github stats is here.Just add the this API and insert github profile name in place of PanwarAyush-->
 <details>
<summary>📊 Github Stats</summary>

<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=PanwarAyush&show_icons=true&theme=gotham" alt="Ayush Panwar | Stats" />
</details>

<!-- we can use html syntax to insert images . Below is example of twitter , youtube and linkedin ,etc-->
---
---
---

## Connect with me  
<div align="center">
 <a href="https://www.linkedin.com/in/ayush-panwar-08769720b/" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>
<img height="30" src = "https://img.shields.io/badge/Youtube-%23E4405F.svg?&style=for-the-badge&logo=Youtube&logoColor=white">
<a href="https://github.com/PanwarAyush" target="_blank">
<img src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 5px;" />
</a>

<a href="" target="_blank">
<img src=https://img.shields.io/badge/twitter-%2300acee.svg?&style=for-the-badge&logo=twitter&logoColor=white alt=twitter style="margin-bottom: 5px;" />
</a>

<a href="https://stackoverflow.com/users/edit/17933978" target="_blank">
<img src=https://img.shields.io/badge/stackoverflow-%23F28032.svg?&style=for-the-badge&logo=stackoverflow&logoColor=white alt=stackoverflow style="margin-bottom: 5px;" />
</a>

<a href="" target="_blank">
<img src=https://img.shields.io/badge/instagram-%23000000.svg?&style=for-the-badge&logo=instagram&logoColor=white alt=instagram style="margin-bottom: 5px;" />
</a>
</div>

---
---
<!-- gifs can also be inserted in html style as well as markdown style.-->
</p>
<center><img src="https://logimp.files.wordpress.com/2019/01/viral-p-1.gif?w=736&zoom=2" align="left" width="30%"></center>
<br>

<img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="300px">

#  HI BUDDY

---

<!--Here is a simple way to add arrows in markdown
Up arrow (↑): &uarr;
Down arrow (↓): &darr;
Left arrow (←): &larr;
Right arrow (→): &rarr;
Double headed arrow (↔): &harr;-->

> #  &uarr; &darr; &larr; &rarr; &harr;

<!--you can see more codes by visiting this link
 https://www.ou.edu/research/electron/internet/symbol.shtml-->
 > #  [character codes](https://www.ou.edu/research/electron/internet/symbol.shtml)

<!--Below is the code to include badges , such as linked in badge & Gmail badge ,just use it by replacing id's of the websites inplace of the other one.-->

[![Linkedin Badge](https://img.shields.io/badge/-PanwarAyush-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://[www.linkedin.com/in/PanwarAyush/](https://www.linkedin.com/in/ayush-panwar-08769720b/))](https://www.linkedin.com/in/ayush-panwar-08769720b/)

[![Gmail Badge](https://img.shields.io/badge/-ayushpanwar691@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:ayushpanwar691@gmail.com)](mailto:ayushpanwar691@gmail.com)

---
<!--These are some stickers that may be useful-->
- 👨‍🎓 💻 ❤ 🚀 🐍 🔭  ⭐👋🌱✔️
 ---
 <!--We can easily insert github code/technologies stats using this API, just relace my details with your detais-->
 📶 Stats:<br><br>
 
 [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=PanwarAyush&theme=dark&layout=compact&align=right&width=40%)](https://github.com/PanwarAyush/github-readme-stats)        

---
<!--the below code  can be used to insert the contribution graph-->
[![Aysuh Panwar github activity graph](https://activity-graph.herokuapp.com/graph?username=PanwarAyush&theme=react-dark)](https://github.com/riti2409/github-readme-activity-graph)
---
<!--This is how stackoverflow can be used in readme file.Just insert your stackoverflow id inside round brackets -->
[![stackoverflow card](https://readme-components.vercel.app/api?component=stackoverflow&stackoverflowid=17933978)](https://stackoverflow.com/users/edit/17933978)


<!--This is the way to include technical skills -->
<h1>Technical Skills 🛠</h1>
<p align="center"> 
 <img alt="Python" src="https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white"/>
 <img alt="Java" src="https://img.shields.io/badge/java-%23ED8B00.svg?&style=for-the-badge&logo=java&logoColor=white" />
  <img alt="C++" src="https://img.shields.io/badge/c++-%23ED8B00.svg?&style=for-the-badge&logo=C++&logoColor=red" />
<img alt="HTML5" src="https://img.shields.io/badge/html5-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white" />
 <img alt="CSS3" src="https://img.shields.io/badge/css3-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white" />
 <img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" />
 <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-blue?&style=for-the-badge&logo=typescript&logoColor=white" />
 <img alt="Numpy" src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" />
 <img alt="Pandas" src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" />
 <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-lightgreen?style=for-the-badge&logo=mongodb&logoColor=4EA94B" />
 <img alt="NodeJs" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
    <img alt="npm" src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" />
    <img alt="Express.js" src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
    <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" />
    <img alt="ReactJs" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
    <img alt="firebase" src="https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black" />
    <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
    <img alt="Google Cloud" src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" />
    <img alt="VS Code" src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" />
    <img alt="IntelliJIDEA" src="https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white" />
</p>


<!--These API shows how we can  insert github projects here-->
---
# Recent Projects 👨‍💻
<div align="center">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=PanwarAyush&repo=TributeWebPage&show_icons=true&theme=great-gatsby"> 
<img src="https://github-readme-stats.vercel.app/api/pin/?username=PanwarAyush&repo=technical-documentation
&show_icons=true&theme=great-gatsby"> 
<img src="https://github-readme-stats.vercel.app/api/pin/?username=PanwarAyush&repo=learn-markDown-
&show_icons=true&theme=great-gatsby">

<!--A snake eating github contributions can also be included using this api link-->

![](https://raw.githubusercontent.com/kothariji/kothariji/d043318518985faa1d2e58a7b594aa7033a388ee/github-user-contribution.svg)

--- 
