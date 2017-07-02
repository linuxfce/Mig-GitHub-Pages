# MigPortfolio
Testing my initial approach to GitHub Pages ...


  This site was built using [GitHub Pages](https://pages.github.com/).
	
 And also reading for the first time **Markdow** notation on [GitHub Help](https://guides.github.com/features/mastering-markdown/#examples).
 
 I'm also learning HTML-CSS-JS w/ [BootStrap](https://v4-alpha.getbootstrap.com/) & [JQuery](https://jquery.com/) at [FreeCode Camp](https://www.freecodecamp.org/).

 # Task
 
 - [x] Finish my changes
 - [x] Push my commits to GitHub
 - [x] Open a pull request
 - [ ] Host my 1st webpage on GitHub
 - [ ] Show my FreeCode Camp exercices solutions
 - [x] Write JS function to change Webpages background
 without having to change URL's on the CSS file
     
 * And above all, written in a simple & intituitive manner ...
 
# About JScript
 And this is one way to change the webpage background using JQuery, by just alter the index number on this function instead of having to change the url of the picture on the CSS or the HTML file.
 
 ```
 $(function(){
  
  var backgroundImg = [
    'https://www.images1.com', 'https://www.images2.com', 'https://www.images3.com'
  
  ];
  
  $('body').css('background-image', 'url(' + backgroundImg[1] + ')');
  
})
```
 So, you just have to change the backgroundImg parameter `[1]` to one of your choice, don't forget in JScript language the index starts at 0, so, in the example above, the parameter of backgroundImg is number 1 which is equivalent to the url `https://www.images2.com`,counting from the left, is the second url because it starts counting at 0.
 
Bye, Mig 
:+1:  
