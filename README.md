# better-handsup
This is an improved/fixed version of KadDarem's walkable handsup script which you can find here -> https://github.com/KadDarem/Walkable-Hands-Up

This version basically stops your ped from doing the hands up animation if you are in a vehicle. This is to prevent conflict with the animation that makes your ped cover himself in a car (default key 'X'). This could simply be achievable by re-mapping the handsup key to other than 'X' but for me it wasn't enough as I didn't want people to raise their hands in the car as it looks wonky.

To install this script you simply need to upload the `better-handsup` file into your server's resources folder and then edit your server.cfg and add `start better-handsup`.

Default Key is '__X__' and you can edit it on line 24 as shown below by changing `X` to whatever you like better.                      ```IsControlJustPressed(1, Keys['X'])```

**ALL CREDITS TO KADDAREM FOR THE SCRIPT
https://github.com/KadDarem**
