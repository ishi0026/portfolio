# portfolio
portfolio for Final Project

# welcome to my portfolio

# process 
1. Design  
Produced a unique design for this assignment.
After comparing several freelancers' websites, we decided to keep the design simple to make the work stand out.

2. Create HTML structure  
The site is divided into four pages: Home, About, Works, and Contact. The size and less volume of the text were carefully considered to keep the design simple. 

3. Create basic CSS  
Colors are mostly from favicon and logo. The number of colors was also minimized. The color scheme was changed using custom properties.

4. Add CSS library  
Animate css was used to add movement to the index and about titles, and Shake css was used to add playfulness to the contact page.

5. Final Check  
Check Accessibility using ARIA, skiplinks
Image optimization using picture
code validation, especially I checked on ARIA role

# challenges you faced during development
# how you overcame those changes
1. use of cards - making them clickable
I wanted to put 3 images and descriptions on the top page of the index, but couldn't figure out how to do it. I wondered if I should use columns.
However, I remembered the bootstrap cards I had learned in class and was able to place them using that function. I also adjusted the position of the card border and text to make it easier to read.
In addition, I wanted to make it so that clicking on a card describing the service would take you to the works page, so I used the stretch-link function to expand the clickable range to the entire card.

2. Color optimization
Initially, colors were set one by one. However, in bootstrap, I used :root{    -bs-primary: etc., 
I remembered that I could specify my desired colors, and used them to use two main colors.
Also, the link file to bootstrap came after main.css, which prevented color changes, so the order was changed.

using libraries
accesibility



# What have you learned by creating your web portfolio?
I wanted to create simple designs. 
In that case, 
adding many words sometimes confused to viewers(in my opinion)
adding too much animation disruct understanding
So it may be important I should use simple but necessary (show skills) tools


# a list of any assets or resources you used that was not your own,including any frameworks, libraries, plugins, fonts, or images. 

CSS libraries  
-https://animate.style/  
-https://elrumordelaluz.github.io/csshake/  

Fonts  
-https://fonts.google.com/specimen/Nunito  
-https://fonts.google.com/specimen/PT+Sans  
