# portfolio
portfolio for Final Project

# welcome to my portfolio

# process 
1. Design  
Produced a unique design for this assignment.
After comparing several freelancers' websites, I decided to keep the design simple to make the work stand out.

2. Create HTML structure  
The site is divided into four pages: Home, About, Works, and Contact. The size and less volume of the text were carefully considered to keep the design simple. 

3. Create basic CSS  
Colors are mostly from favicon and logo. The number of colors was also minimized. The color scheme was changed using custom properties.

4. Add CSS library  
Animate.css was used to add movement to the index and about titles, and cssshake was used to add playfulness to the contact page.

5. Final Check  
Check Accessibility using ARIA, skiplinks  
Image optimization using picture  
Accesibility, especially I checked on ARIA role  
Code validation  

# challenges I faced during development
# how I overcame those changes
1. Using cards - setting & making them clickable  
I wanted to put 3 images and descriptions on the top page of the index, but couldn't figure out how to do it. I wondered if I should use columns.  
However, I remembered the bootstrap cards I had learned in class and was able to place them using that function. I also adjusted the position of the card border and text to make it easier to read.  
In addition, I wanted to make it so that clicking on a card describing the service would take viewers to the works page, so I used the stretch-link function to expand the clickable range to the entire card.  

2. Color optimization  
I had a hard time setting the colors.  
Initially, colors were set one by one. However, in bootstrap, I used `:root{    -bs-primary: `etc.,  
I remembered that I could specify my desired colors, and used them to use two main colors.  
Also, the link file to bootstrap came after main.css, which prevented color changes, so the order was changed.  

3. Using libraries  
It was difficult to understand how to use the library.  
I wanted to add animations to pages other than the works page, which had already been animated with css.  
I looked for animations that would not interfere with the layout, and chose animation.css and cssshake, which can be used in link implementations. 
I was careful about the position of the css files not to do same mistaks when specifying colors.  
The animations are interesting because of their movement, but too many would be difficult to see, so I kept them to a minimum, about one per page.  

4. Accesibility  
It was difficult to write the roles.  
At first, I wanted to write roles as detailed as possible for the sake of clarity, mistakenly believing that I could give them original names just as I had done with the id.  
However, the validation check produced errors, so I re-read the ARIA class content and documentation. I also took advice from my professor and learned that there are several fixed names.  


# What have I learned by creating my web portfolio?  
I learned about the rich features of bootstrap.  
It was very interesting to be able to implement parts of the site that I had previously implemented by writing many lines of css by adding a single sentence in the HTML.For example, I had a hard time with the margins of text and buttons in midterm, but I learned how to use simple words like `mb-` in bootstrap.
Also, creating responsive design is much easier, just writing simple words such as `.col-lg-` supported me to create responsive design.  
Lastly, I found that the visual arrangement of the site can be improved by modifying the position and colors based on various examples in bootstrap.  

I learned about various functions and wanted to try them out, but at the same time, I learned how difficult it is to think about the ease of viewing. For example, too much text can confuse the viewer. If I use a lot of animations, it is more difficult to understand. 
However, as a portfolio, it is also important to show our skills, so it is difficult to find the right balance.  
I felt that it may be important to choose and use simple but necessary techniques.  
In addition, I need to create more works to add my portfolio because just showing them is easier to understand the variation of my skills.


# a list of any assets or resources I used that was not my own,including any frameworks, libraries, plugins, fonts, or images. 

[ARIA](https://www.w3.org/TR/html-aria/#el-footer)

[CSS libraries-animate.css](https://animate.style/)  
[CSs libraries-cssshake](https://elrumordelaluz.github.io/csshake/)

[Fonts](https://fonts.google.com/specimen/Nunito)  (https://fonts.google.com/specimen/PT+Sans)
