# Design web pages with CSS
#### Read: 05 submission 

#### Hello, This is Fatima. You can view my Markdown webpage using the following [link](https://fati-ma.github.io/reading-notes/Read05)

#### In this blog I will give a summary for the chapters 10 and 11 of the book: "HTML & CSS" :books: :

 [x] *Chapter 10: Introducing CSS*
 [x] *Chapter 11: Color*

##### Note: Keywords are emphasised.

## Chapter 10: Introducing CSS

- CSS treats each HTML element as if it appears inside its own box and uses **rules** to indicate how that element should look.
- Rules are made up of **selectors** (that specify the elements the rule applies to) and **declarations** (that indicate what these elements should look like).
- Different types of selectors allow you to target your rules at different elements.
- **Declarations** are made up of two parts: the **properties** of the element that you want to change, and the **values** of those properties. 
   ```For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.```
- CSS rules usually appear in a **separate document**, although they may appear within an HTML page.


## Chapter 11: Color

- Color not only brings your site to life, but also helps convey the mood and evokes reactions.

- There are three **ways to specify colors** in CSS: 
   1. RGB values 2. hex codes 3. color names.
   
- Color **pickers** can help you find the color you want.
![picker](https://i.stack.imgur.com/lmhuZ.png)

- It is important to ensure that there is enough **contrast** between any text and the background color.

- CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as **RGBA**.
![opasity](https://kathep.com/site/assets/files/3075/screen_shot_2017-11-28_at_3_11_42_pm.png)

- CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as **HSLA**.
![css3color](https://www.techfry.com/images/webmaster/hsl-color-model.png)


#### Example:

```
<!DOCTYPE html> 
<html> 
  <head>  
    <title>Color</title>  
    <style type="text/css">   
    body {    
       background-color: silver;    
       color: white;    
       padding: 20px;    
       font-family: Arial, Verdana, sans-serif;
     }   
   h1 {    
       background-color: #ffffff;    
       background-color: hsla(0,100%,100%,0.5);    
       color: #64645A;    
       padding: inherit;
     } ```
    </style> 
  </head>
</html>
