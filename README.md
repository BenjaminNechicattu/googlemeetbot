# googlemeetbot
A simple Google meet bot so the bot can attend classes for you.(fuck the education system)
 
## REQUIREMENTS
      $ pip3 install selenium
      $ pip3 install pause
      $ pip3 install pynput
  I encourage you to work on a virtual enviornment like anaconda
  
### My Test Cases

* Firstly I work with with the selenium chrome-driver and uses chromium as the interface =  WORKS 
* Secondly I tested on a headless chrome = BUG 
* Mozilla headless driver works fine in mozilla firefox = WORKS

## Advantages of headless drivers?
   
   The program runs in background until you have a good internet connection and power . It never requires mozilla tab to be     opened . I really worked on chrome-headless but some bugs reported while running so i switched into the mozilla-headless it works cool .
   
### CODES
  * chromium.py
  * mozilla.py
  
#### Working of chromium.py
  
  
  You can uncomment the pause.until in the chromium.py ie you can set the time and execute when to start the program
  
  Replace the usernameStr and passwordStr with your gmailid and password
  
  Replace the url meet with the meeting id
  
  There are certain permissions to use our media by google meet i just blocked it all (micrphone and webcam) and set to a default value of 2(block) and 1(unblock)
  
  *In the last line before pause if you are a student in an organization replace the 'ask to join' with 'Join now'
  ##### note please: i tested on a chromium browser
 
### Working  of mozilla.py 

  The cool headless functionality i implemeted her and it works pretty well there are more options like --disable gpu 
  
  The headless option makes the program to run in background .even if the program terminated  we will be the particpants in the  meeting
  
  The permission parameters are littlr different than in chrome 
  
   
