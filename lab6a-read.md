# HTML, CSS, JAVASCRIPT TOGETHER
  * HTML, CSS, JS placed in seperate files but can't be seperated from webpages because each one form a layar.
  * These three layers form the basis of a popular approach to building web pages called  progressive enhancement.
      1. html: the content of the webpage, the content should be served regardless of the browser or the device use the website in the age of many devices and softwares.
      2. html + css: the presentation of the content, i may add one css or several to render content in different views.
      3. html + css + js:  js add user experience to the page and it's also seperated on file, some users don't have js activated, and we still want to provide our wepage.

# Basic javascript code.

  1. Create a folder to put the example in called cOl, then start up your favorite code editor, and enter the text to the right.
     ```
      var today= new Date();
      var hourNow = today.getHours();
      var greeting;
      if (hourNow > 18) {
          greeting= 'Good evening!';
          else if (hourNow > 12) {
              greeting = ' Good afternoon!';
         else if (hourNow > 0) {
              greeting = 'Good morni ng!';
         else {
             greeting = 'Welcome! ' ;
        document .write( ' <h3>' +greeting + ' </ h3> ');
     ```
  2. LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE
         1. i use script tag to refer this is a script.
         2. then link it using src attribute added to script tag
   3. link the script to the page.
