# MongiBG
Kronos IV battleground queueing addon.

Use the /mbg show or /mongibg show command to open the gui.

!In order for the addon to use it's full potential the kronos queueing cd needs to be over!

How it works:

UPDATE_BATTLEFIELD_STATUS event fires whenever joining a queue, leaving a queue, battlefield to join is changed, when you can join a battlefield, or if somebody wins the battleground. On that event we insert the .join command, pretty simple.

![alt text](https://github.com/krasbulle/MongiBG/blob/master/MongiBG.png?raw=true)
