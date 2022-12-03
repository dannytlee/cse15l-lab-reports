# week 7 lab report


## Part 1
* The task that I chose to do is to change all of the start variable names to base. To start editing, I used the command vim DocSearchServer.java
* in vim, my first comman was /start <Enter>. This brought me to the first instance of the word start 
 ![Image](l7sc1.png)
* next I used dw to delete the word start
 ![Image](l7sc2.png)
* then I used i to enter insert mode, then typed base to write base into the file as the new variable name.
 ![Image](l7sc3.png)
* <Escape> got me back into normal mode. Then n brought me to the next instance of the word start. n in vim is used to repeat the last search
![Image](l7sc4.png)
* again I deleted the word with dw
 ![Image](l7sc5.png)
* then used i to enter insert mode and typed out base to replace the variable name.
 ![Image](l7sc6.png)
* <Escape> got me back into normal mode then n got me to the next instance of the word start. dw deleted the word start
![Image](l7sc7.png)
* i entered insert mode, then i typed base to replace the variable name
 ![Image](l7sc8.png)
* to save and exit the file, I typed :wq <Enter>
![Image](l7sc9.png)
  
## Part 2
  * Next I compared the speed of edits onto a remote server using vim compared to making the edits locally then using scp to transfer the file onto the remote server 
  
  * First I tried making an edit in VS Code then using scp to transfer the edit onto the remote, then running the file in the remote.  The edit I made was to comment out the java command, so the file just compiled instead of compiling and running. This took me 57 seconds.
  ![Image](w7sc21.png)
  
  * Second I tried making that same edit onto the file while already in my remote account by using vim. I then ran the file. In total this only took me 14 seconds. 
  ![Image](w7sc22.png)
  
  ![Image](w7sc23.png)
  
  * Some more questions
  * Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?
* I would probably prefer to use vim because of the drastic difference in times required to make an edit and run the file. I was not used to controlling vim at first, but I became more adept at using it as the lab went on. I imagine if I were to use this tool everyday, I would be able to use it without thinking. 
* What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!)
* I think that the main factor would be the amount of edits that need to be made to the file. If there are just one or two lines that need to be changed, vim would probably be quicker. If there are many changes that need to be made or things that need to be added, using a text editor would likely be the better choice for its ease of use. 
