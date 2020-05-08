# Whatsapp-spammer
The bot that sends entire text files word by word. Corona lockdown is the one to blame 

#UPDATES
The line by line version sends , you guessed it , lines from a text file.Personally , this is my favorite coz atleast it makes a little sense

The SRT version basically allows you to watch a movie through the subtitles coz it sends the texts in sync with when it would have been said in the film


Use at your own risk. You WILL get blocked


Requirements :

You need to have selenium installed and the chromedriver(included) should be present in the path

IMPORTANT THINGS TO NOTE 

Run the first 2 cells -> scan qr code before running the 3rd cell -> run the third cell

Your element xpath for the "search bar" , "text bar" and "send key" might be different. So inspect the element and replace my xpath value with yours 

Change the name from 'Another Carlo' to your targets contact name

The speed at which it sends a file depends on the time.sleep() value. Changing it to 0 makes it really fast , but causes a bottle neck wile sending it to the person causing it to get mixed up
Best value so far is 1 second

Run the count cell for word count

Additional text files are inluded. Just change the text file name for sending a different file

#Thats all folks
