# Overlord For Sniper Elite 1
### Recreating from scratch, a stable and self-sustainable version of the [legendary **Spotter for Sniper Elite**](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/Legendary%20Spotter.png).
![Knife](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/SEKnifeItemIcon.png)\
*The **Spotter for Sniper Elite** cannot operate since its official site was terminated. I tried everything. There is no fix to that. Unofficial fixes partially repaired the kick/ban functionality, but every other functionality -such as *knife*, *panzerfaust*, etc- is unfortunately inoperable.*

*Related Links*\
**[Official Steam Group for the "Overlord for Sniper Elite 1" Software](https://steamcommunity.com/groups/overlordforsniperelite1)**\
**[Bugs Report sub-forum (you have to be a Steam Group member first)](https://steamcommunity.com/groups/overlordforsniperelite1/discussions/7/2793871682804344559/)**\
**[One and only real distributing site (once the software is ready)](https://github.com/creatorpanda/OverlordForSniperElite1)**

:love_letter: *Please reach out to me on [Twitter](https://twitter.com/creatorpanda)!* :love_letter:

![Panzerfaust](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/SEPanzerfaustItemIcon.png)
### A journal where I record the progress of my biggest, most complicated project ever.

**Note:** *I won't upload the program's code throughout the process. I don't know if I ever will or not. This is **the official page** where someone can find information **for Overlord** in case I ever publish a functional piece of software. All the downloads, upgrades, updates, and news regarding everything that concerns the project will be posted here.*

*Current version: 1.0.0*

---
---
# Progress Updates (most recent to oldest)

### Update #10, Wednesday 20/03/2024 (Major Update)

#### Game Status

As Overlord's ability to recognize the game's status improves, there's now the ability to continuously determine if the game is running and whether the player is the host. Overlord will refrain from harvesting game data unless the user is the host. Notice in the GIF below the different cases of the game running, not running, and hosting or not.

![GameStatus](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/OFSE1GameStatus.gif)

#### Update Notification System

As we get closer to a complete program, it becomes crucial for Overlord to effectively inform users about available updates and guide them to a secure location for downloading them.
In my last update, I mentioned that `the interface hasn't changed since the last update that depicted it`, but I was mistaken. Overlord now features a discreet text positioned at the center, directly above the log box, indicating the availability of updates. Upon an update becoming available, the text transforms into a clickable hyperlink, directing users to the Official Releases page.\
Observe this GIF, and notice the different states at which Overlord acts accordingly.

![UpdateCheck](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/OFSE1UpdateCheck.gif)\


#### Hosting Aiding Software

My go-to choice for playing Sniper Elite online nowadays is Gameranger. I love Gameranger and will renew my yearly subscription soon. I have been studying how Gameranger works and how it connects players. While doing so, I remembered Tunngle, and to my surprise, I found out that it had been discontinued since 2018 and was no longer available for safe distribution.
I will continue studying Gameranger while considering Hamachi, Parsec, and ZeroTier One in my research, knowing that they differ from Gameranger.

#### Sniper Elite 1 Time Capsule

That is the name of the repository that will be storing all the mods I mentioned in the previous update. I haven't finished polishing it. Links will be posted here once it is published.

#### Update Outro
*I had no clue what I was getting into when I started this project.
The more I learned, the less I felt I knew.
I owe a lot to Overlord for my personal growth as a programmer.
And I owe it to Overlord to see it through to completion.*
#### ***next README.md update at 24/04/2024 (dd/mm/yyyy)***

---
### Update #9, Wednesday 06/03/2024 (Treasure Hunting)

This update contains knowledge I've been acquiring and data I have been gathering in my spare time for almost three years. This update has been altered for years.

This update doesn't mainly have to do with Overlord, but the old Spotter for Sniper Elite, and the game itself.\
I will keep how I achieved things to a minimum. I do not want to get very technical, just share my excitement and news!

So! My mission had already started...

#### The Beginning
I started by going back in time. The rabbit hole *is* scarily complex. I scraped every bit of information I could get my hands on.\
From old clan sites all over the planet that have never heard of before (like SoG and SniR) and are still alive on free hosting domains, to my main protagonists (like GotS and NZAUS).

![GotSIndexPageImage](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/GotSIndexPageImage.png)

The amount of data that I found is immense and doesn't belong here as a whole. It'll take weeks to just make a collage of every piece of useful data I've found and honestly, it'll be mostly "boring" technical stuff.\
Some of the sites I dug up were closed after the official servers died. They no longer served their purpose. Some others were even taken down by federal court orders!\
The date stamps on these ghost forums made me feel nostalgic. I saw sites, usernames, and profile pics I didn't know I remembered. And I kept everything I could.

#### About Sniper Elite
By using different techniques, I managed to observe how the game worked from the inside:
- What libraries it uses and what they do,
- Stripped characters and items graphic files,
- Stripped game sounds,
- I even patched it so I can put symbols in my name since the regedit trick doesn't work on Steam. Every cool kid would put symbols in their names.

![ExtractedTextures](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/ExtractedTexture.gif)

There are many funny developer notes and weird messages lurking in the software. Texts like:
- `"Silly combination of flags"`
- `"Invalid parameter, tell Adam."` *(who's Adam?)*
- `"Tried to pass a stupidly small route to FollowRoute"`
- `"Why do you want to continue? You have already finished your journey... Stupid truck"`
- `"You called UpdatePosition after telling the spline that you had died. This was stupid."`.

Among them, I found a message stating that `"The Knife should no longer be in the game!"`, which supposedly meant that the knife was supposed to be broadly used but eventually wasn't and
`"Should not allow PANZERFAUST USED items as pickups."`. That is probably why after using that weapon, the character would drop it and it would disappear, rendering it impossible to pick it up as used and empty.

Not much to say here other than that Sniper Elite is still an amazing game to me. Sadly it lacked some options.\
For example, the host should be able to:
- kick or ban players,
- to accept more than 7 players on the server,
- modify the multiplayer settings as much as possible, including which weapons each team spawned with,
- and include more maps in multiplayer

most of these options were covered by the Spotter and that's what made it awesome.\
A hypothetical later and final version of the Overlord will be able to do the second and third dots. 

I still have fun hosting Sniper Elite TDMs on Gameranger. I love Gameranger.\
There are some cheaters though, and the host has a difficult time walking around (walking speed and controls bug).\
Please let me know of any better servers or solutions. Servers have gotten lonely and have no one to play with nowadays.

#### The reason why Spotter for Sniper Elite inevitably died
My favorite mod ever, written in C/C++ and compiled on Borland(?). After its initial installation, it would attempt to "talk to" its official site to download vital files and updates by contacting its static `IP 216.128.23.175`. and access `http://GentlemenOfTheScope.com/downloads/spotter/version/version` or `http://GentlemenOfTheScope.com/downloads/spotter/current`

![SpotterIpContactAttempt](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/SpotterIpContactAttempt.png)

That's why just the installer of Spotter wouldn't be enough to make it function properly and throw errors like:

`"Spotter needs to download validation and update information."` after the initial run, or

`"Make sure GentlemenOfTheScope.com is accessible through your web browser."`, is the error that constantly appeared after the website died with the official servers.

But there are other messages like `"It has been too long since Spotter was able to access GentlemenOfTheScope.com"` and `"To continue to use Spotter, you must get an upgrade at GentlemenOfTheScope.com"`, an error shown later to people who had the program already installed when the site went down. Given the fact that I tried to recover the program after many years, I never got to face the second error.\
This leads me to the conclusion that the Spotter was created to forever fail whenever the developers deemed it necessary, or the site went down for whatever reason. Despite any reason (software integrity?), the Spotter was made to have an expiration date no matter what (software availability).

#### What about Overlord?

The interface hasn't changed since the last update that depicted it, although I have been refining the code and slowly advancing its capabilities. The overlord can now filter connections that have to do with Sniper Elite and print them in a debug-assisting box. Kicking a player will be possible once I attach every player's IP to their corresponding in-game usernames and banning will be implemented once every logging function is completed.

The Overlord will be able to monitor players despite the way the game was hosted - either LAN or VLAN.
Testing the Overlord is fun and promising. It has finally started looking like a legit program.
Version-wise it is too early to share it with other people that want to help.

#### The Surprise
[Announcing this update](https://steamcommunity.com/groups/overlordforsniperelite1/announcements/detail/4202491691443796221) on the Overlord's Official page on Steam, I promised there was a surprise.

So let's reveal it.

During my research, I found tons of mods, skins, huds, Scopes, maps, binoculars, and other software.\
Shortly after collecting everything I could, the remaining sites that hosted all that material vanished. I believe my actions saved a lot of community-made goodies that would otherwise disappear forever. I have been uploading to another repository that I will make public soon, and also pin it here, and at the top of the markdown, among the official Overlord pages.
#### ***next README.md update at 20/03/2024 (dd/mm/yyyy)***

---
### Update #8, Thursday 18/03/2021 (Major Announcement)

Hello again :)\
This thread got quite long so I rearranged the updates, placing the most recent first.\
\
Due to all the events that take place in my country and the whole world, the project slowed down. I will stop posting updates every now and then. I will only post when there's something new to announce. I realized that posting under certain dates pushed my work making it a burden and making me produce bad code. I managed to find more people to help me out with the projects. People with stronger machines that can run tests faster. I have a team of IT students who help me whenever they can.\
\
If you want to stay up to date with the project you can subscribe to this project, and/or join the official sites that are noted above. The project will be completed. It's only a matter of time.\
\
Please keep believing in this project and we will all be rewarded soon.\
Stay safe and healthy <3


---
### Update #7, Tuesday 19/01/2021 (Basic Functionalities)

Happy New Year everyone! Hopefully, this is not 2020 v2.0 and great things come along!\
The long-awaited update is finally here, and I really wish it finds you all healthy and mentally strong. I never updated the project in time because I just couldn't work efficiently.\
The software I've been developing for the last nine months has finally started taking shape, as the inner mechanisms that give Overlord a purpose are slowly being installed.

*There are several issues that are only a matter of time:*
* The communication that Overlord has to do between players is still a massive subject for me, and the needed research/studying is great.
* The quarantine that forces overstaying at home makes things difficult, including studying and researching.
* Friends and I are busy with online uni lessons, and that slows Overlord's development down, since every line of code I implement needs to have the whole software rebuilt and tested in-game.

**So here's how it goes from now on:**
* First of all, Overlord needs to **continuously monitor players** that join and leave a game.
* Once the players that join a game are successfully monitored, the **kick** functionality will be implemented.
* Once the kicking works perfectly, the **logging** functionality will be implemented.
* Once the logging works perfectly, the **banning** functionality will be implemented.

And that's going to be **Overlord for Sniper Elite 1 v1.0**

Please be patient and everything's going to work out.
#### ***next README.md update at 15/03/2021 (dd/mm/yyyy)***

---
### Update #6, Saturday 15/08/2020 (UI changes)

There was no important progress this time. The UI changed to fit two clickable texts that lead to the only two official sites of the software. The signature was moved way higher and turned to simple text. From now on, if an error that doesn't break the software occurs, apart from the log text that appears (that can be lost as more text comes) and the window that pops that may close accidentally, a red sign also appears to warn you. It breaks or does nothing. It just stays there so you notice that something's wrong.\
Please observe this GIF
![Update6Notes](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/Update6Notes.gif)

From now on the most important part begins. The main reason this software is needed is kicking and banning.\
This is going to take me a lot of time. One month won't make an important update. I have a lot of studying to do. The next update will be posted in **November** 15th.\
Until then, anything important will be posted right here and announced **[there](https://steamcommunity.com/groups/overlordforsniperelite1)**.

Until then, stay safe and healthy <3
#### ***next README.md update at 15/11/2020 (dd/mm/yyyy)***

---
### Update #5, Wednesday 15/07/2020 (error handling and more)
(**R.I.P. [Grant Masaru Imahara](https://en.wikipedia.org/wiki/Grant_Imahara)**)

*First of all, I'd like to take a minute to let you know that the passing of Grant Imahara hurt me a lot. Mythbusters and Brainiac were my favorite shows when I was a little kid and losing a brilliant, ingenious childhood hero at such a young age was so unexpected. My deepest condolences to his family and friends.*


Now that the uni exams are behind and uni is gone for the summer, I have all the time I need to sharpen my coding skills. I'll be working on many private projects that won't show up here, but the Overlord will be one of my priorities.

What's new about the Overlord? Error handling. I would never share a piece of software that crashes uncontrollably with anyone. I take my work ~~as~~ seriously ~~as my coding skills can go~~. So I added error handling and error codes. Let's see an example:

If you launch the Overlord while not connected to the internet, the Overlord is going to face some issues. One of them is the inability to find the host's public IP. Thus, the Overlord is going to look like this:
![OfflineStatus](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/OFSE1OfflineBehavior.png)

Plus, a window will pop up and let you know what seems to be the issue and provide you with an error code that you can easily report back to me. I made sure you get a tidy issue report that explains what's probably happening:
![OfflineStatus](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/AttentionOFSE1ErrorMessageBox.png)

So, in case you're sure that everything's fine with your connection and it's the Overlord's fault for not working properly, you can go back to [the Official Steam Group for the "Overlord for Sniper Elite 1" Software](https://steamcommunity.com/groups/overlordforsniperelite1), go to the ["Bugs Reports" sub-forum](https://steamcommunity.com/groups/overlordforsniperelite1/discussions/7/2793871682804344559) (you have to be a member of the group) and let me know that you're getting -for that example- a "KARLSHORST" error (The errors are named after SE1 themes). That way you get a user-friendly interface that tries to help you out before you reach out to me, and if you do, I know a bit better where to search for the issue that appears.

***Please note that the Error Code names HAVE ALREADY CHANGED (still SE1 themes). Plus, the Error Handlings that don't shut the Overlord down print the Error Code at its log box. The previous presentation was just an example. Making a list of these Error Codes doesn't matter for now. Once the Overlord is released, the already existing error codes (may add more after release) will never change again to avoid confusion, and a useful explanation list will be made.***

The Overlord gets better and better every day.

One last thing:
During the past month, a brotherly friend of mine (a greater programmer than me) and I, have been studying the Original Spotter in-depth. I am not going to get into details of our actions and studies because that's not the point. The point is that our research helped the development of the Overlord significantly. I really cannot explain how important our work was. All this paved a path for many new ideas and ways to pursue Overlord's development. I'm still the only one working on the code (at least for now) but his contributions are remarkable. Thank you, brother.

#### ***next README.md update at 15/08/2020 (dd/mm/yyyy)***

---
### Update #4, Monday 15/06/2020 (game status)

I safely recovered the whole project from my dead desktop and stored it in multiple storage devices and the cloud. Updated every piece of software I need to develop the Overlord so everything is fresh and clean.

The Overlord's development took a step further. Now the Overlord knows when SE1 runs and lets us know. 
![SEGameStatus](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/SniperEliteStatus.gif)\
This step brings so many new options to the table. Things the old Spotter had and we need back. 

Other things that happened:
- As you may have noticed, the light/dark theme button's size changed. Wow..
- The greatest things though, happened where you cannot see: I revised and reworked many lines of code so things run better and future code studying and debugging is easier.
- I made clear what the program needs, how to make it happen, and in what order. So the development goes smoother and more organized.

I'll slowly continue the development through the uni semester that's attacking. It's going to take a while because the last OS my professors laid their hands on was the mighty MS-DOS. Thank you for keeping up with me.

#### ***next README.md update at 15/07/2020 (dd/mm/yyyy)***

---
### Update #3, Sunday 31/05/2020 (where I've been)
(**R.I.P. [George Perry Floyd](https://en.wikipedia.org/wiki/Death_of_George_Floyd)**)

It's been a while since the date I was supposed to report my progress and even more since the last update.
The truth is that studies for uni (business and tourism management) and other courses I've taken, monopolize my time.
Plus, my 11-year-old desktop eventually became unreliable. Most probably a motherboard malfunction caused by corrosion that messes up RAM slots. That of course ruins the stability and proper functioning of the machine, so I decided to put my desktop to rest and only use my laptop from now on. The **Overlord for Sniper Elite 1** project is safely waiting for me to extract it, in one of the desktop's drives.

**Note:** *I studied my previous updates and realized that I'm trying to complete the program without a big main plan divided into smaller parts and organized steps. I need to take a step back and make a plan of what needs to be done, when and how.*

That means that the whole progress freezes for a while, but doesn't stop entirely. Since I don't want to let you wait without a certain update date, I'll update this form again in a couple of weeks. Anything that happens regarding the project until then will be posted here.

#### ***next README.md update at 15/06/2020 (dd/mm/yyyy)***

---
### Update #2, Wednesday 6/05/2020 (dark theme)
(**R.I.P. [Florian Schneider-Esleben](https://en.wikipedia.org/wiki/Florian_Schneider)**) 

I made no important progress. It's going to take a while until I'm ready to continue on the IP matter. I finished the "Main Display" GUI, and all the variables needed, and now I'm focusing on the network capabilities of the program. I believe unless I finish that, nothing else can be accomplished. Finally, created a dark mode because I enjoy dark-themed programs. I like it, but it doesn't serve the main purpose of the Overlord. Here's what I made:

![Dark Mode](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/OFSEDarkMode.gif)

*I have no plans until the next update. I'll use some quality time to study what I need to learn before I continue.*
Quarantine makes everything difficult + the semester is coming. Pray for me.

#### ***next README.md update at 13/05/2020 (dd/mm/yyyy)***

---
### Update #1, Wednesday 29/04/2020 (the beginning)

I've been working on the Overlord for some days. Mostly studying IP harvesting and manipulation. Currently, the Overlord looks like this:

![Overlord for Sniper Elite 1](https://github.com/creatorpanda/OverlordForSniperElite1/blob/master/pics/Overlord3.png)

Things I'll try to finish until next update

- [x] complete Interface (only "Main Display" for now)

- [x] carefully create variables for software needs.  

- ~[ ] saving IPs in logs~

- ~[ ] proper actions when the X button is pressed~

- ~[ ] proper events log functionality~

- ~[ ] proper event log export (including usernames and banned usernames for now)~

Note: I strikethrough'd some points cause I realized the load of work they need to be accomplished. I couldn't get these ready in 7 days. I'm not that good at programming *yet*..

#### ***next README.md update at 06/05/2020 (dd/mm/yyyy)***

---
