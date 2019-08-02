In this project took part Anastasiia Zhmurko and Kseniia Zinchenko.

Task №1 - Zhmurko Anastasiia:

 --- Section Header with menu/dropmenu;
 
 ---Section "People are talking about us".
 
 Task №2 - Kseniia Zinchenko:
 
 --- Section "Revolutionary Editor" with buttons watch/star/fork;
 
 --- Section "Here is what you get".
 
 --- Section "Fork Subscription Pricing".
 
 We created 1 gulp-task  "build" (instead of 2) in the gulpfile, that:
 
 --clears dist-directory;
 
 -- compiles scss in  css files;
 
 -- adds prefixes for a cross-browsering work;
 
 -- concates js и css  files into one
 
 -- modifies resulting js and css files;
 
 --copies  minified js и css files in the dist-directory;
 
 --optimizes images and copyies their in the dist-directory ;
 
 -- loads the server and watches for the changing  *.js и *.scss files in the src-directory;
 
 -- after changing -- rebuilding and copying resulting and minified styles.css or script.js in the dist, page's reload.
 
 In this task we used such npm-modules, as:
 
  - gulp
 
  - gulp-sass
  
  - browser-sync
  
  - gulp-js-minify
  
  - gulp-clean-css
   
   - gulp-clean
   
  -  gulp-concat
  
  - gulp-imagemin
  
  -  gulp-autoprefixer
  
  Thanks for your attention ! 
 
 