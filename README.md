# TypeRacer-Hack
TypeRace hack which types huge chunks of words with the single press of the space-bar or any letter key on your keyboard. 
I have added different speeds, you can also make your own speeds by either deleting or adding lines of code. All the lines are the same code so you can copy and paste.
Currently working on a way to change the speed within a single repository so you don't have to do it manually.

# **TypeRacer Bookmarklet**  
You can copy this code and drag it to your bookmark bar, then whenever you want to deploy it just press it when you are in a race. Make sure to reclick it every time you start a new race.

_(13-Key) TypeRacer Bokmarklet:_   
javascript:fetch("https://raw.githubusercontent.com/Imahinion/TypeRacer-Hack/main/Scripts/Original Code.js").then((res)=> res.text().then((t) => eval(t)))

_(Single-Key) TypeRacer Bookmarklet:_    
javascript:fetch("https://raw.githubusercontent.com/Imahinion/TypeRacer-Hack/main/Single-Key Speed").then((res)=> res.text().then((t) => eval(t)))

**Bookmarklet Template:**   
You can always make your add your own bookmarklets for whatever script by pasting the link for the raw code into this bookmarklet template,
then drag or manually add the code to your bookmark bar in order to use the script at a single click.   
Note: This template might not work for all links, but it should work for most.

javascript:fetch("Insert link to RAW javascript here").then((res)=> res.text().then((t) => eval(t)))
