# Advanced Personal Portfolio
 HKR JavaScript for web development
1. Used ChatGPT to Brainstorm titles for the navbar.
2. To insert the social media icons, I added https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css in my head tag. 
3. To make my social media icons to look clickable, I made a :hover selector for .social-media a and transformed the scale to 1.05.
4. I made a * (all) selector to add a solid border, to make it easier for me to see the layout and its containers.
5. I changed name of a class in HTML, which messed up the styling. So I had to change the name in CSS as well. 
6. I got stuck when I wanted to give the main img a 5% margin-right. So I asked ChatGPT for help and it told me to replace space-between, in justify-content, with flex-start since it overrided the other margins for main img and main .intro.
7. Some of the selectors in main were duplicated without me noticing. Which mad eme confused when nothing happend.
8. I want the porttrait to be cropped horizontally for smaller screens. So I added object-fit: cover;
9. Now the portrait looks weird on wide screens. So I added a max-width of 1000px.
10. My content appeared outside the website. I realized that I could have width 100% and 5% margins on each side. Instead, I changed the margins to auto and set the width to 90%.
11. I wanted to make my website responsive width "mobile-first" and made media queries for wider screens. 
12. Max-width sizes found in https://www.w3schools.com/howto/howto_css_media_query_breakpoints.asp
13. One of the most challenging things was that I wanted to structure the HTML different based on the max-width. So I asked ChatGPT for help and it recommended me to do two different codes in HTML, which was totally new for me. And then you just do display: none.
14. I wanted my portrait to be cropped for responsive design. I realized that I wasn't really centered. So instead of editing the source img, I used object-position: 45% 50%;