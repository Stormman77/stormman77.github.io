## Second journal entry

**Creating an app with MIT appinventor**

Perhaps the hardest part of this assignment for me personally was to get an idea for my app. After 10 minutes of active brainstorming, I decided to create an age calculator, "The Goofy Age Calculator". I also didn't come up with using anything better than appinventor for the sake of time saving, but as it turned out that was a mistake, and I wasted not only time, but also my nerve cells.

My idea was to simply create two screens, the first one asking the user their age, and the second one printing the result for the user's calculated age. In order to keep the app goofy enough, I decided to use a drop-down list with age values. I also used button with a red button background image to make it more real. Overall, I had no problems with designing and "programming" the first screen.

Real struggle started with "programming" the second screen, whose only purpose was supposed to be showing the user's age. In order for that to work, I created a variable in the first screen (the only way to do so that I found was by creating a global variable) called *age* in which I stored the age that user was choosing in the dropdown list. After that, I had to somehow pass that variable with the user's age to the next screen. Again, the only way to do that was to open the new screen and sending it a start value which I assigned to the *age* variable:

![image](https://github.com/user-attachments/assets/74625582-52bb-4193-8394-c06a21c447d7)

Real real struggle started when I was trying to get the age value that I was passing on the new screen and show it on the screen. For that, I was using a *TextBox* component which initially had an empty text field, so that I could assign it the value of the variable that I passed on to the new screen. It took me 5 harrowing minutes to figure out that *TextBox* is actually a component for entering text, while *Label* component is used to display a piece of text. However, even switching to the *Label* component didn't solve the problem - the user's age just wasn't showing up on the screen. I believe that the problem is in passing the age value between screens. Unfortunately, I did not find the way to make this thing work:

![image](https://github.com/user-attachments/assets/9d70f608-37ad-4b2f-af0b-22bc0176c302)

Finally, I realized that even though my app wasn't working as intended, it still was an app that was working on my phone. Therefore, technically I met the requirements of the assignment, and with this being said, here's the final version of "The Goofy App Calculator" (which doesn't really calculate your age, but surely is goofy):

![IMG_9210-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/2bdf5441-b482-4c6e-a8a4-176fe6762955)

