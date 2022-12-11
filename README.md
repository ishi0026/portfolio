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
using cards - with animation
color optimization
using libraries


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


=========================
Questions?

2 Write README


if possible, create form using javascript or something
if possible, card links - hope not make it blue and undelined  → bad effect for social media link, so deleted once
if possible, description pop up when card touched


==
△
accecibility aria add -almost done / just make sure at last- role:△, placeholder:ok etc
image optimize using "picture" - almost done / just make sure does need --w or not -- i think not (https://www.w3schools.com/tags/tag_picture.asp)
→　It should write from big sizes

card animation delete in specific one →　change class name to avoid move top page's cards
→ card size optimize in each png?(animate showed difference)  → ok? animation not required in rubrics

if possible, icon:ok and favicon make rounded → favicon need to be circle by default image?

if possible, make button for pdf? or, delete button?　whici looks nicer? →　add buttons - centerize did in div text-center / font-size make smaller???  →　 created button ok


==
〇
delete the color around "works" -ok add bg-light
space on "works" ok - delete py-5 it used for y axis
navigation bar right ok -justify content-end, contents right (remove spaces) ok - class="bg-light container-md mb-5"
The size of the icons ok
skiplinks work ok
the size of the box ok - change rem, 
works-delete line around box ok-border-light
index delete line around box ok- div class="card h-100 border-light"
change SNS icon size ok -in css Svg section
submit button center -ok  created div class and set col / mx-auto d-block also work

submit button animation - ok added  .col button {} in css

footer &copy right bottom side - only tried in contact page -ok  added .row{ text-align: left;} in css, and change the div<> to bottom of the sns links

fonts - it works by setting each h1-h5 tags ok

★2.color custom properties - contact page button is ok, will add works page or not? can I change text-danger color? or should add specific name? 　
→ we can change the default color name using bs-primary:#xxxx in css file

★3.validate html, css -  in html, contactForm for attribute role in form →　I can only use some words in ARIA /  ok(deleted footer roles):socialmedia for attribute role on element footer in footer error??? → ARIA roles can only use specific words. such as region. so we can't create original names for them.

1.add contents(paragraphs) ok

★ 1 ★should use other frameworks??? tailwind? js? yes- trying to use animation css or something
should use media query for responsive? only used with bootstrap...
-https://animate.style/ in index,about ok
-https://elrumordelaluz.github.io/csshake/ in contact  ok

3 Validate codes again ok


memo
.display-1～>.display-4 
detail add? - try(if possible, description pop up when card touched)
bold /Equivalent of 700 . - bolder/ Bolder than the inherited font weight