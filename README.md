# Introduction
A New Digitized Edition of the Admonito Generalis as prepared by Cole Taylor, History Ph.D. Student at Fordham University. This github serves as a repository of the .xml and .odd files necessary for deployment to TEIPublisher as well as the code and files that constructed the .xml edition. As I learn more coding, I plan on having a full display of the text using TEIPublisher embedded within a website which can accurately display the text as intended. This project started as a final assignment for Dr. Brian Reilly's course _Editing Medieval Texts_ at Fordham University.
# Using the Files
If you would like a more visual representation of the text, outside of reading .xml code, follow the steps below:
  1. Navigate to https://teipublisher.com/exist/apps/tei-publisher/index.html
  2. Log in with the username: "tei-demo" and password: "demo" (Do not include the quotations when signing in)
  3. Scroll down to the bottom of the page and enter a file name and title for display (these can be anything you wish) then click create. You will now see your .odd at the bottom of the long list, click the pencil/pen icon which will take you to the .xml of the .odd.
  4. CTRL+A and delete the text, then copy the text from the style sheet provided by this repo and paste all of it into the file, be sure to click save at the top.
  5. Navigate back to the TEI Publisher tab and click on 'Playground' and click the Upload button on the right, select the Admonito Generalis.xml file to upload
  6. You should now see the edition on the screen, click the title of the edition to access the digital edition.
  7. Click on the three lines to the far right (below where it says logged-in as tei-demo) and under 'select ODD' select the odd you created and then click out to return to the edition.
  8. You should now have a visual representation of the edition that represents what I will (eventually) have hosted on a website, removing all these steps to access a visual version of the edition.

The python file provided can also be used to run your own calculations of Euclidean distance, simply change the Matrix and MatrixNames to your preference as well as the matrices themselves with their corresponding points. For example, change V = [0,1,1....] to the corresponding point and sigla, and change the matrix = [V, M3, P3G] to the sigla you use to identify the point. Then, change matrixNames = ['M3', 'V', 'P3G'] to the corresponding sigla. Be sure to keep the apostrophes and commas that define the sigla.
# Credits
I am grateful for Frances Eshleman, History Ph.D. Student at Fordham, for providing the documentaiton on creating .odd files and the various ways to reconfigure the display of text. I also must give credit to the Siege of Antioch Project Team at Fordham University for teaching me the basic formatting of an .xml file, and I largely follow the code guidelines established by this project to recreate the Admonito Generalis. The python code for calculating Euclidean distance between points comes from 2LT Dylan Taylor, MSECE at Purdue University.
