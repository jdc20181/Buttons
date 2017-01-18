# Buttons
Some Easy Examples of buttons - 

#Setting Up 

To start off with you need to know the basics of CSS and HTML, without those, this is useless. 

Next- We will work with both `<a>` Buttons and `<button>` buttons  using a class we can use a regular Hyperlink to create a button. 

Example:




`   a.button:link, a.button:visited {
    background-color:#1E90FF;
    color: white;
    padding: 14px 25px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
}


a.button:hover, a.button:active {
    background-color: 	#1E90FF;
    text-decoration:none;
    
}`

<style>
   a.button:link, a.button:visited {
    background-color:#1E90FF;
    color: white;
    padding: 14px 25px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
}


a.button:hover, a.button:active {
    background-color: 	#1E90FF;
    text-decoration:none;
    
}
</style>
<a class="button" href="#"></a>
