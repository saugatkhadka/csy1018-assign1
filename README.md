_csy1018-assign1_  
_Saugat Khadka_     
_UN id: 17429437_

![My Avatar](images/avatar.gif)
# Portfolio
Throughout the process of coding up this portfolio page, my design did not change very much. Card UI and box shadow was an unexpected addition to the whole portfolio. The first design was a pretty plain but good structure to help facilitate the design process later on and get a good picture of what the webpage should look like. I had a good idea of how I wanted my page to look. Really slimmed down and very basic with pleasing aesthetics. So I decided to choose clean white and greyish theme for the whole page and dark image for the navigation pane. 

Though, it is recommended that websites be done mobile first, I made the desktop version first and scaled everything down to fit all screen sizes down to _**iPhone 4**_.  During the period of the assignment, I went through various portfolios and many designs on the internet. [Codepen](https://codepen.io/) and [Fresh Website Design](https://www.freshdesignweb.com/) are two places I mostly visited to get ideas for my designs.  Most of the design made there, were made with the use of Javascript frameworks and bootstrap. Creating similar designs in pure CSS was a fun and informative experience. I had to go through some tutorials to get a good grasp of box model and positioning. In the end, I made very little sketches and wireframes than I expected. The ones I made are listed below.

## Access to Project

The live project can be access through Github with [link](saugatkhadka.github.io/csy1018-assign1/).

## Sketches
I made a very small sketch of the basic page to be followed throughout the development process. Font sizes for different and basic components for all pages are also written down. Mentioned font size are the latest trend in the blogging community and also medium uses them and I think they have really good readability because of it. And colors theme for the overall page is also written down. I mainly went with flat colors because they are easy on the eyes and catchy at the same time.

After going through some portfolio design and vcards on the web, I decided to make a black and white themed page. I made the following wireframes based on the conclusion. The first wireframe I made was the final and decisive design I settled on. 

![Sketch for web project][sketch]


> Pros: Clean looking design and simple codes required to make  
> Cons: Not enough punch and visual appeal, Has very little content and animation



## Wireframes

### Home Page
![Home Page][Home wireframe]

### Bio/ About Me
![About Me][Bio wireframe]

### CV
![CV][CV Wireframe]

### Contact
![Contact][Contact Wireframe]


## Mobile view
Since I made the page responsive for mobile last, it was quite a hurdle to get everything to work properly. I used the viewport to get the site to scale and made some adjustments to the containers. I only made the wireframe for phones after getting the site to be responsive on smaller devices and used media queries to display the content properly. Very little changes were made to the mobile view after making the wireframe. So the portfolio is consistent with the wireframe all the way to the end.

### Home Page
![Home Page][Home mobile wireframe]

### Bio/ About Me
![About Me][Bio mobile wireframe]

### CV
![CV][CV mobile Wireframe]

### Contact
![Contact][Contact mobile Wireframe]


## Pictures of the first design
I started with a basic structure of the page and built it with black and white accent. I really wanted to use the card UI, so I used it to display the CV page contents. 

### Home Page
![Home Page][Home first design]

### Bio/ About Me
![About Me][Bio first design]

### CV
![CV][CV first design]

### Contact
![Contact][Contact first design]


After the first try at the website, I realized that I was missing some photos (fixed soon after) and footer was not fixed to the bottom of the page. From looking it up, it was due to less content or bad responsive configuration. I tried to look for a solve but most of the suggestion were for using javascript, so I chose to increase the amount of content in every page so even high definition screen would not reach the end without a scroll. After that solved my problem, there were cases where, some online responsive test sent back unresponsive navigation bar.I tried to recreate the scenario with all the devices I could get my hands on but it worked with all my devices, so I decided to leave it just as it is.

## Final look

### Home Page
![Home Page][Home final design]

### Bio/ About Me
![About Me][Bio final design]

### CV
![CV][CV final design]

### Contact
![Contact][Contact final design]

## Final Mobile View

### Home Page
![Home Page][Home final mobile design]
### Bio/ About Me
![About Me][Bio final mobile design]
### CV
![CV][CV final mobile design]
### Contact
![Contact][Contact final mobile design]

## Performance
Although optimization for the current codes is limited due to assignment restriction, images have been optimized and page load speed tested have come up with an A. The performance insight from pingdom.com can be seen below.

![Speed Test Result][Performance report]


## Good practice
To my best extent, I've tried to keep to a good and respected design language as much as possible and reduce code plagarism as well as content plagarism like icon and background files. Although all contents and the code used from external sources have been credited in this file.

Google’s material design was a worthwhile read and implementation was simple. But after completing most of my pages, I found that **_textarea_** element was not working properly or rather doing some random animations or transitions in my browser when using live server or even just opening it directly. But it worked well in other devices In webpage tests, it had good scores and there were no critical validation errors on the w3 validators. After sending it to review to our module tutor, I finalized my designs and code, formatted everything according to the guidelines and prepared for submission.


## References
I used some sites and portfolios for design reference and for background images. All of the resources I used during the period of coding this project are listed below.

> * W3school (card ui, box shadow,  flex tutorial)
> * Flexbox froggy
> * Thinkful HTML & CSS course
> * Portfolios
> 	+ http://ryanscherf.net/ 
> 	+ http://castirondesign.com/ 
> 	+ http://www.hihayk.com/ 
> 	+ https://bert.house/ 
> 	+ https://www.freshdesignweb.com/ 
> 	+ http://learn.shayhowe.com/html-css 
> * Design and patterns from https://www.toptal.com 
> * https://fonts.google.com 
> * Text faces from https://textfac.es 
> * Icons from http://www.flaticon.com 
> * Favicon from http://www.favicomatic.com/ 



[sketch]: images/readme/sketches/sketch-first.jpg

[Home wireframe]: images/readme/wireframes/home.png
[Bio wireframe]: images/readme/wireframes/bio.png
[CV Wireframe]: images/readme/wireframes/cv.png
[Contact Wireframe]: images/readme/wireframes/contact.png

[Home mobile wireframe]:images/readme/wireframes/home-mobile.png
[Bio mobile wireframe]:images/readme/wireframes/bio-mobile.png
[CV mobile wireframe]:images/readme/wireframes/cv-mobile.png
[Contact mobile wireframe]:images/readme/wireframes/contact-mobile.png

[Home first design]:images/readme/first-design/home.png
[Bio first design]:images/readme/first-design/bio.png
[CV first design]:images/readme/first-design/cv.png
[Contact first design]:images/readme/first-design/contact.png

[Home final design]:images/readme/final-design/home-final.png
[Bio final design]:images/readme/final-design/bio-final.png
[CV final design]:images/readme/final-design/cv-final.png
[Contact final design]:images/readme/final-design/contact-final.png

[Home final mobile design]:images/readme/final-design/home-mobile-final.png
[Bio final mobile design]:images/readme/final-design/bio-mobile-final.png
[CV final mobile design]:images/readme/final-design/cv-mobile-final.png
[Contact final mobile design]:images/readme/final-design/contact-mobile-final.png

[Performance report]:images/readme/performance/performance-insight.png