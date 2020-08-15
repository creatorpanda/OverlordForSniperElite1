# Overlord For Sniper Elite 1
Recreating from scratch, a stable and self-sustainable version of the [legendary **Spotter for Sniper Elite**](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/Legendary%20Spotter.png).

*Related Links*\
**[Official Steam Group for the "Overlord for Sniper Elite 1" Software](https://steamcommunity.com/groups/overlordforsniperelite1)**\
**[Bugs Report sub-forum (you have to be a Steam Group member first)](https://steamcommunity.com/groups/overlordforsniperelite1/discussions/7/2793871682804344559/)**\
**[One and only real distributing site (once the software is ready)](https://github.com/creatorpanda/OverlordForSniperElite1)**

### A journal where I record the progress of my biggest, most complicated project ever.

**Note:** *I won't be uploading the program's code throughout the process. I don't know if I ever will or not. This is **the official page** where someone can find information **for Overlord** in case I ever manage to publish a functional piece of software. All the downloads, upgrades, updates and news regarding everything that concerns the proejct will be posted here.*

---
---
# Progress Updates


### Update #1, Wednesday 29/4/2020 (the beginning)

I've been working on the Overlord for some days. Mostly studying IP harvesting and manipulation. Currently, the Overlord looks like this:

![Overlord for Sniper Elite 1](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/Overlord3.png)

Things I'll try to finish until next update

- [x] complete Interface (only "Main Display" for now)

- [x] carefully create variables for software needs.  

- ~[ ] saving IPs in logs~

- ~[ ] proper actions when X button is pressed~

- ~[ ] proper events log functionality~

- ~[ ] proper event log export (including usernames and banned usernames for now)~

Note: I strikethrough'd some points cause I realized the load of work they need to be accomplished. I couldn't get these ready in 7 days. I'n not that good at programming *yet*..

#### ***next README.md update at 06/05/2020 (dd/mm/yyyy)***

---
### Update #2, Wednesday 6/5/2020 (dark theme)
(**R.I.P. [Florian Schneider-Esleben](https://en.wikipedia.org/wiki/Florian_Schneider)**) 

I made no important progress. It's going to take a while until I'm ready to continue on the IP matter. I finished the "Main Display" GUI, all the variables needed, and now I'm focusing on the network capabilities of the program. I believe unless I finish that, nothing else can be accomplished. Finally, created a dark mode because I enjoy dark-themed programs. I like it, but it doesn't serve the main purpose of the Overlord. Here's what I made:

![Dark Mode](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/DarkMode.png)

*I have no plans until the next update. I'll use some quality time to study what i need to learn before I continue.*
Quarantine makes everything difficult + semester is coming. Pray for me.

#### ***next README.md update at 13/05/2020 (dd/mm/yyyy)***

---
### Update #3, Sunday 31/5/2020 (where I've been)
(**R.I.P. [George Perry Floyd](https://en.wikipedia.org/wiki/Death_of_George_Floyd)**)

It's been a while since the date I was supposed to report my progress and even more since the last update.
Truth is that studies for uni (business and tourism management) and other courses I've taken, monopolize my time.
Plus, my 11 years old desktop eventually became unreliable. Most probably a motherboard malfunction caused by corrosion that messes up RAM slots. That of course ruins stability and proper functioning of the machine, so I decided to put my desktop to rest and only use my laptop from now on. The **Overlord for Sniper Elite 1** project is safely waiting for me to extract it, in one of the desktop's drives.

**Note:** *I studied my previous updates and realized that I'm trying to complete the program without a big main plan devided in smaller parts and organized steps. I need to take a step back and make a plan of what needs to be done, when and how.*

That means that the whole progress freezes for a while, but doesn't stop entirely. Since I don't want to let you wait without a certain update date, I'll update this form again in a couple of weeks. Anything that happens regarding the project until then will be posted here.

#### ***next README.md update at 15/06/2020 (dd/mm/yyyy)***

---
### Update #4, Monday 15/6/2020 (game status)

I safely recovered the whole project from my dead desktop and stored it in multiple storage devices and cloud. Updated every piece of software I need to develop the Overlord so everything is fresh and clean.

The Overlord's development took a step further. Now the Overlord knows when SE1 runs and lets us know. 
![GameStatus](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/SniperEliteStatus.png)
This step brings so many new options to the table. Things the old Spotter had and we need back. 

Other things that happened:
- As you may have noticed, the light/dark theme button's size changed. Wow..
- The greatest things though, happened where you cannot see: I revised and reworked many lines of code so things run better and future code studying and debugging is easier.
- I made clear what the program needs, how to make it happen, and in what order. So the development goes smoother and more organized.

I'll slowly continue the development through the uni semester that's attacking. It's going to take a while because the last OS my professors laid their hands on was the mighty MS DOS. Thank you for keeping up with me.

#### ***next README.md update at 15/07/2020 (dd/mm/yyyy)***

---
### Update #5, Wednesday 15/7/2020 (error handling and more)
(**R.I.P. [Grant Masaru Imahara](https://en.wikipedia.org/wiki/Grant_Imahara)**)

*First of all, I'd like to take a minute to let you know that the passing of Grant Imahara hurt me a lot. Mythbusters and Brainiac were my favorite shows when I was a little kid and losing a brilliant, ingenious childhood hero at such a young age was so unexpected. My deepest condolences to his family and friends.*


Now that the uni exams are behind and uni is gone for the summer, I have all the time I need to sharpen my coding skills. I'll be working on many private projects that won't show up here, but the Overlord will be one of my priorities.

What's new about the Overlord? Error handling. I would never share a piece of software that crashes uncontrollably with anyone. I take my work ~~as~~ seriously ~~as my coding skills can go~~. So I added error handling and error codes. Let's see an example:

If you launch the Overlord while not connected to the internet, the Overlord is going to face some issues. One of them is the inability to find the host's public IP. Thus, the Overlord is going to look like this:
![OfflineStatus](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/OFSE1OfflineBehavior.png)

Plus, a window will pop-up and let you know what seems to be the issue and provide you with an error code that you can easily report back to me. I made sure you get a tidy issue report that explains what's probably happening:
![OfflineStatus](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/AttentionOFSE1ErrorMessageBox.png)

So, in case you're sure that everything's fine with your connection and it's the Overlord's fault for not working properly, you can go back to [the Official Steam Group for the "Overlord for Sniper Elite 1" Software](https://steamcommunity.com/groups/overlordforsniperelite1), go to the ["Bugs Reports" sub-forum](https://steamcommunity.com/groups/overlordforsniperelite1/discussions/7/2793871682804344559) (you have to be a member of the group) and let me know that you're getting -for that example- a "KARLSHORST" error (The errors are named after SE1 themes). That way you get a user-friendly interface that tries to help you out before you reach out to me, and if you do, I know a bit better where to search for the issue that appears.

***Please note that the Error Code names HAVE ALREADY CHANGED (still SE1 themes). Plus, the Error Handlings that don't shut the Overlord down print the Error Code at its log box. The previous presentation was just an example. Making a list of these Error Codes doesn't matter for now. Once the Overlord is released, the already existing error codes (may add more after release) will never change again to avoid confusion, and a useful explanation list will be made.***

The Overlord gets better and better every day.

One last thing:
During the past month, a brotherly friend of mine (greater programmer than me) and I, have been studying the Original Spotter in-depth. I am not going to get into details of our actions and studies because that's not the point. The point is that our research helped the development of the Overlord significantly. I really cannot explain how important our work was. All this paved a path for many new ideas and ways to pursue Overlord's development. I'm still the only one working on the code (at least for now) but his contributions are remarkable. Thank you, brother.

#### ***next README.md update at 15/08/2020 (dd/mm/yyyy)***

---
### Update #6, Saturday 15/8/2020 (UI changes)

There was no important progress this time. The UI changed to fit two clickable texts that lead to the only two official sites of the software. The signature was moved way higher and turned to simple text. From now on, if an error that doesn't break the software occurs, apart from the log text that appears (that can be lost as more text comes) and the window that pops that may close accidentally, a red sign also apears to warn you. It breaks or does nothing. It just stays there so you notice that something's wrong. 
![ErrorSign](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/Update6Notes.png)

Fron now on the most important part begins. The main reason this softawre is needed: Kicking and banning.\
This is going to take me a lot of time. One month won't make an important update. I have a lot of studying to do. The next update will be posted in **November** 15th.\
Until then, anything important will be posted right here and announced **[there](https://steamcommunity.com/groups/overlordforsniperelite1)**.

Until then, stay safe and healthy <3
#### ***next README.md update at 15/11/2020 (dd/mm/yyyy)***

---
