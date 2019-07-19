### This is a collection of games I have re-written to make more sleek and user friendly. I made the original collection of games (Version 4.1) on days when my life hit an usually low point #nofriends 😔 You can probably imagine how amazing things are now that I've had time to go back and re-write the entire thing 🤔 JOY!

I am continuing the *very* minimalist approach as with text games, less is often more.

The games currently available are as follows:

 - 1 to 10 Guessing Game: The user has one try to guess a number between one and ten
 - 1 to 100 Guessing Game: The user has unlimited attempts to find a number between one and one hundred with hints along the way
 - Verb Guessing Game: A word with all the vowels missing is displayed on the screen and the user is tasked with figuring out what the original word was
 - Multiplication Games: Multiples two unmbers together and shows on of the these number and the result, the user then has to work out the missing number to complete the equation. Current, there are three "versions":
     - 1 to 10 range numbers are generated (e.g "3 x ? = 12")
     - 10 to 20 range numbers are generated (e.g "12 x ? = 180")
     - 20 to 100 range numbers are generated (e.g "43 x ? = 2752")
     
     I could have added a timer for this but... 
     ```powershell
     if (!$Dev.State.StillLazy){
         $Timer.Add()
     }
     ```
 - Rock, Paper, Scissors: This is a classic so if you don't know where I'm going with this one, you can probably leave now ☺️ This is also the one I enjoyed making the most
     
 - QuickFire Counting 🔥: The user has to quickly read a word that is briefly displayed on screen and guess how many letters are in the word. This is timed, and the time limit decreases the more you get right. The first word shows for one second, this is decreased by 30 miliseconds for every correct answer ⏰
 
 - Blackjack 🃏: I really went to town on this game. The first version (In version 4.1 of this games collection) was HUGE! Really unnecessarily huge. I worked this one down to a much more efficient size and I'm almost proud of myself at the outcome.


#### I would really appreciate it if you could report all errors and issues 🚫 🧯

As you might expect I have a main menu where the games can be selected from  and a help menu which has been condensed. There is also a secret. But we don't talk about that... 🤐

You can always [visit my site](https://mharwood.uk) which has archives of my games as individual scripts and also some of the older game collections.

Enjoy! 🎉
