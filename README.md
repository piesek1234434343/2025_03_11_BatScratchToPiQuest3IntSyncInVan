#  Bat Scratch To Pi Quest 3 Int Sync In Van

For a client project, I need to write some code, ensure it is production-ready, document it, and perform stress testing. So let's create a step-by-step guide.   (In short, it's a **Quest multiplayer game** 🎮 played by **four players** in the same small space, using **time and integers** connected to a **Raspberry Pi**. 🕹️ In short... (^^' )  )

As I will be teaching how to build an XR game right after this project in Charleroi, I am taking this opportunity to create a step-by-step video guide for the workshop with the students.  

### Bat Scratch? What?  

In Scratch, I previously built a small game in just half an hour using the cloud variable system provided by the website.  
The program is only 40 blocks long—a ridiculously short script that fits within a single screenshot!  

The concept is simple: the first player to click on the bat makes it disappear for everyone and earns a point.  

[![image](https://github.com/user-attachments/assets/dd796b72-f4f3-42ca-bab2-4023f4ba43b7)](https://scratch.mit.edu/projects/966307753/editor/)  

If I can set up a lightweight WebSocket server on a Raspberry Pi to allow four players to play and monitor the game within a small mapped space (such as inside a van) and provide complete documentation on how to set up and update everything, then I will have checked all the boxes for my current client project.  

So, if you want to learn how to make this kind of game in Quest 3, feel free to follow along and create your own based on what you learn. You are more than welcome!  

For information here is the inital pitch and the representation of what it looks like in the idea:
[![image](https://github.com/user-attachments/assets/896477f3-2124-4715-82f3-27b0cf3d501f)](https://github.com/EloiStree/2025_01_07_PitchDeckNtpIntPiGame/tree/main)

Bonus: It would be really fun if this were applied to a table tennis game for the club! ^^
Imagine four kits scrambling to get into position and hit the bat as fast as they can... 🏓🧙‍♂️👏
I’d love to see that in action!

State of the project: https://github.com/users/EloiStree/projects/22

-------------------------


**Week 1, 2025-05-11:**  

- [ ] Set up an integer mockup lobby while waiting for the step to be written and ready.  
  - [ ] Be able to restart the game or end it on a developer command.  
  - [ ] Be able to send an integer and receive one from within the game.  
  - [ ] Be able to link an action to the received integer.  
  - [ ] Create a debug tool to send an integer from an inspector menu.  
  - [ ] Create a debug tool to send an integer from a 2D UI menu.  
  - [ ] Optionally: Create a debug tool to send an integer from a 3D World UI debug menu for XR.
  - [ ] Take the time to learn Unity3D timeline and linked to Integer event.

- [ ] Set up the Raspberry Pi installation.  
  - [ ] How to install the Raspberry Pi.  
  - [ ] How to set up the Raspberry Pi as an NTP server.  
  - [ ] How to set up the Raspberry Pi as an integer WebSocket server.  
  - [ ] If the internet is available, download the latest version at startup.  
  - [ ] If an Android device is detected at startup, install the latest APK on it.  
  - [ ] If an Android device is detected at startup, enable ADB Wi-Fi access on all detected devices.  
  - [ ] Ensure that restarting the device is the only requirement for a monitor to function.  


