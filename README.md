# DRPWFT
Custom Discord Rich Presence That Displays Current Date And How Much Times Left For Tomorrow (aka Discord Rich Presence Waiting For Tomorrow)

---

Installation
------
Install [Node](https://nodejs.org)  
Install [Git](https://git-scm.com/downloads)  
Create a folder for the repository and open it with git bash.
Clone the repository: ```git clone https://github.com/Z3roTwo/DRPWFT.git```  
Install the Discord-Rich-Presence module: ```npm i discord-rich-presence```  

Starting the script
------
Open the repository's folder called DRPWFT and run: ```node main.js```  

Customizing
------
Open the config.json file, should look something like this:
```
{
    "LargeImage": "displaypic",
    "LargeImageText": "Pwease be mwy fwiend ._.",
    "SmallImageToggle": "True",
    "SmallImageText": ["New Year :)", "❤️🧡💛💚💙💜", "March", "AprIl Fo0ls!1!!", "It's gonna be May", "June", "July", "August", "Do you remember?", "Time To Get Spooky 💀", "No Nut November", "Merry Christmas 🎅"]
}
```  

**LargeImage**  
LargeImage is the big image showing what "game" you're playing, currently there's only displaypic, sad and spooktober available but I'll probably add more in the future.  
**LargeImageText**  
This is what pops up over the large image when you hover over it, you can put whatever you want here or just leave it as default.  
**SmallImageToggle**  
This decides if you want to turn on the smaller image in the bottom right corner of the bigger image which just shows a fancy color (Except for spooktober where is shows the doot doot skeleton ._. because spooktober is the most important month).  
**SmallImageText**
This is what's going to pop up over the small image when you hover over it, you want here too as long as you keep it in the same json format and have exactly 12 parts. *If SmallImageToggle is set to false it will ofc not show this either.*  
