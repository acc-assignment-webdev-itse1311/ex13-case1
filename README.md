# NP HTML5, CSS3, and JavaScript 6e Tutorial 13, Case Problem 1

## Instruction:
1.  Use your editor to open the mpl_links_txt.html and mp_links_txt.js files from the html13 > case1 folder. Enter your name and the date in the comment section of each file, and save them as mpl_links.html and mpl_links.js respectively.
2.  Go to the mpl_links.html file in your editor. Within the document head, add a script element for the mpl_links.js file. Load the file asynchronously. Take some time to study the content of the file. Note that the selection lists are placed within a form element named "govLinks". Save your changes to the file.
3.  Return to the mp_links.js file in your editor and create an event listener for the load event that runs an anonymous function.
4.  Within the anonymous function, create the allSelect variable referencing all select elements nested within the govLinks form.
5.  Loop through the allSelect object collection and for each selection list in the collection create an anonymous function for the onchange event. Within this anonymous function, use the href property of the location object to change the page shown in the browser window to the value of the target of the event object that initiated the onchange event.
6.  Document your commands with JavaScript comments.
7.  Save your changes to the file and then open the mpl_links.html file in your browser. Verify that you can load different government websites by selecting the website name from the entries in the four selection lists.

