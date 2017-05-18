#### Website Performance Optimization portfolio project
Website Performance Optimization course at Udacity : https://www.udacity.com/course/ud884
To check the page speed of this site, visit https://vardhini007.github.io/frontend-nanodegree-mobile-portfolio-master/
### Part 1: Optimize Critical Rendering Path
Made the following changes to index.html:
1. Set analytics.js to run asynchronously
2. Set media query for print style sheet
3. For Google fonts, removed the 700 size fonts (the bold font) as it was not used.
4. Moved the content of style.css to "inline" (enclosed in <script> tags with in the index.html file) to speed loading of the initial page
5. Optimized images
### Part 2: Optimize Frame Rate and Computational Efficiency
I made the following change to views/js/main.js :
1. Changed the addEventListener to window.onload. 
2. Changed querySelectorAll to getElementsByClassName as it is more efficient (has fewer elements to search).
3. Moved the getElements (randompizzaContainer) into a variable outside of the loop so it does both need to be processed for each element re-size.

