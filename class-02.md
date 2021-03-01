# HTML 
## Text:
When we built a web, we add some tag knows as a markup to the contents in the page that help us to 
Design a web and make it more useful and allow to browser show the structure of the web.
Will focus how to add a markup to the text, there’s a two type of structure will be see it now.
•	**Structural markup**
this is markup in html that gives information about the structure of a document. It may also be associated with a change in appearance, but the key is that it provides information about divisions, titles, sections, paragraphs, or other aspects of the structure of a document.
•	**Semantic markup**
Semantic HTML elements are those that clearly describe their meaning in a human- and machine-readable way. Elements such as header,footer and article are all considered semantic because they accurately describe the purpose of the element and the type of content that is inside them.

> Structural markup : 

1 - HEADINGS : html has six level of element from h1 to h6. A heading element implies all the font changes, paragraph breaks before and after, and any white space necessary to render the heading. The heading elements are H1, H2, H3, H4, H5, and H6 with H1 being the highest (or most important) level and H6 the least. And the brewers show the heading in different size.
 > NOTE ; THERS NO HEADING 7 THERE ARE JUST 6 .

2 -  PARAGAPHS : we use <p> tag to create a paragraph , by default every paragraph will show in different line.

3 – BOLD AND ITALIC : The bold tag b you can putting inside paragraph and chose any word and sign it by this tag but don’t foregate it to close it </b>,By enclosing words in the tags and we can make characters appear italic.
4 - SUPERSCRIP AND SUBSCRIPT : The sup tag defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW. Tip: Use the <sub> tag to define subscript text.

5 - WHITE SPACE : its very used element to use its make a code more easier and web page add extra space or start some element, like if you put space by mistake between word have a large space it will not show it .

6 - LINE BREAKS AND HORIZNTAL RULES : break element <br> if you want to add a new line you can use it inside a paragraph element. There are a few elements that do not have any words between an opening and closing tag. They are known as empty elements and they are written differently like horizontal element  you can used it if you want to write book like html book .

 > Semantic Markup:
  

1 - STRONG : its used if you write the strong information you can use this element to make this paragraph more stronger by make it bold.

2 – EMPHASIS:  The element indicates emphasis that subtly changes the meaning of a sentence by default it will show the paragraph in italic style. 

3 – QUOTATIONS: there is two type of element we can used to make quotations, q element indicates that the enclosed text is a short inline quotation. Most modern browsers implement this by surrounding the text in quotation marks. This element is intended for short quotations that don't require paragraph breaks; for long quotations use the blockquote element.

4 – ABBREVIATIONS AND ACRONYMS : The HTML Abbreviation element *<abbr>* represents an abbreviation or acronym; the optional title attribute can provide an expansion or description for the abbreviation. If present, title must contain this full description and nothing else.
5 – CITAYIONS AND DEFINITIONS : citations cite its used to indicate where the citation is from. Like books or reference of paper. And the definitions <def> element is used to indicate the defining instance of a new term. Some web will show it like italics.

6 -  AUTHOR DETILS : will be used at it the address it will be show the contents of author or his email,I thinks it  something not very important to know about it. 

7 – CHANGES TO CONTENT : ins,del and S , the  ins element used to show content putting into  a document and it will be showed like have line under it.del will show text that has been deleted from it the final one is sshow text that has been deleted from it ,the line will be phased out in the word . 

---
**EXAMPLE OF HTML PAGE **

(![LAB02](https://user-images.githubusercontent.com/79087366/109434170-9dcc0a80-7a1c-11eb-96fd-a5e0ea6f2f49.png)

*SORCE FROM BOOK HTML AND CSS JON DUCKETT
---

# CSS : 
-CSS can be used to define the cell padding of table cells, the style, thickness, and color of a table's border, and the padding around images or other objects. CSS gives Web developers more exact control over how Web pages will look than HTML does.

> WHY CSS TO USED:
CSS saves time Easy Maintainence Search Engines Superior styles to HTML Offline Browsing <<<<<<< HEAD

> css selectors :
thers a lot of css selectore its used every select have rule or target to used. but you must know every selector are very sensitve.so its must match same name you have wirte it.two of theme we have used it there are class and id. if i write more than orde in one element, i must know which one will be done first. when i read i see you can put ! these element to change order and make this more important than other.

**optional choice : but you first must put my css code in sparted element that html one**
> WHAT ARE THE 3 TYPE OF CSS? 
Difference Between the 3 Types of CSS Styles: Inline, External and Internal. In this tutorial, you will learn the difference between the three types of CSS styles: inline, external, and internal.

# JAVASCRIPTS: 
> JavaScript ("JS" for short) is a full-fledged dynamic programming language that can add interactivity to a website. It was invented by Brendan Eich (co-founder of the Mozilla project, the Mozilla Foundation, and the Mozilla Corporation).

JavaScript is versatile and beginner-friendly. With more experience, you'll be able to create games, animated 2D and 3D graphics, comprehensive database-driven apps, and much more!

JavaScript itself is relatively compact, yet very flexible. Developers have written a variety of tools on top of the core JavaScript language, unlocking a vast amount of functionality with minimum effort. These include:

- Browser Application Programming Interfaces (APIs) built into web browsers, providing functionality such as dynamically creating HTML and setting CSS styles; collecting and manipulating a video stream from a user's webcam, or generating 3D graphics and audio samples.
- Third-party APIs that allow developers to incorporate functionality in sites from other content providers, such as Twitter or Facebook.
- Third-party frameworks and libraries that you can apply to HTML to accelerate the work of building sites and applications.
### script : 
The <script> element either contains scripting statements, or it points to an external script file through the src attribute. Common uses for JavaScript are image manipulation, form validation, and dynamic changes of content. 
> Language basics crash course: 
1 - Variables : Variables are containers that store values. You start by declaring a variable with the var (less recommended, dive deeper for the explanation) or the let keyword.
 JavaScript variables can hold numbers like 100 and text values like "John Doe".In programming, text values are called text strings.JavaScript can handle many types of data, but for now, just think of numbers and strings.
Strings are written inside double or single quotes. Numbers are written without quotes.
f you put a number in quotes, it will be treated as a text string.
 
 2 - Comment: are meaningful way to deliver message. It is used to add information about the code, warnings or suggestions so that end user can easily interpret the code. The JavaScript comment is ignored by the JavaScript engine i.e. embedded in the browser.Advantages of JavaScript comments.
 3 -Array : An array is a single variable in JavaScript that is used to store various elements. When we want to store a list of elements and access them through a single variable, it is often used. Unlike many other languages where an array is a various variable reference, there is a single variable in the JavaScript array that stores various elements.
 ### EXperssion in javascripts : 
 An expression is any valid unit of code that resolves to a value.

Every syntactically valid expression resolves to some value but conceptually, there are two types of expressions: with side effects for example: those that assign value to a variable and those that in some sense evaluate and therefore resolve to a value.

The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to seven.

The code 3 + 4 is an example of the second expression type. This expression uses the + operator to add three and four together without assigning the result, seven, to a variable.

JavaScript has the following expression categories:

- Arithmetic: evaluates to a number, for example 3.14159. *Generally uses arithmetic operators.*
- String: evaluates to a character string, for example, "Fred" or "234". *Generally uses string operators.*
- Logical: evaluates to true or false. *Often involves logical operators.*
- Primary expressions: Basic keywords and general expressions in JavaScript.
- Left-hand-side expressions: Left values are the destination of an assignment.

## Decision and loops : 
Like other languages, JavaScript also provides many decision making statements like if, else etc. 
- if statement : if is used to check for a condition whether its true or not. Condition could be any expression that returns true or false. When condition satisfies then statements following if statement are executed.If you have only one statement to be executed after the if condition then you can drop the curly braces ({ }). For more than one statement use curly braces.
- else statement : else statements are used with if statements. When if condition gets fail then else statement is executed.You can drop off the curly braces with else too if there is a single statement to be executed within else.
 - else if statement : Suppose there are variety of conditions that you want to check. You can use multiple if statements to do this task. All the if conditions will be checked one by one. But what if you want that if one condition satisfies then don't perform further conditional checks. At this point else if statement is what you need.
 - switch statement : switch statements do the same task that else if statements do. But use switch statements when conditions are more. In that case, switch statements perform better than else if statements.
 > Loops in javascript : Loops are used to execute a specific statement for a given number of times. Loops are always followed by some condition. JavaScript provides all the basic loops that other programming languages have.
 - While loop : a while statement is a loop that executes as long as the specified condition evaluates to true. The syntax is very similar to an if statement, as seen below. The while statement is the most basic loop to construct in JavaScript.
 - for loop :The For Loop in JavaScript is the best method to iterate through a series of data at the same time. For loop is an entry-controlled loop in which the test condition checked before going to the body of the program. For loop is used when we know the number of iterations before entering the loop. 

i have Written summary from js duckett and html duckett
- [x] (Chapter 2 "text")

- [x] (Chapter 10 “Introducing CSS")
- [x] (Chapter 2: “Basic JavaScript Instructions”)
- [x] (Chapter 4: “Decisions and Loops)


 
 
 
 
 
 



