# s39_firefightModules
Source for FF modules mod for Arma 3.

### What does this do?
It provides a very limited framework to allow folks to generate FIBUA fights as-needed. 
Originally developed as a training tool for my Arma 3 unit (RSF) I've cleaned it up considerably, 
fixed some serious issues, and am putting this out for additional use. 

### Are there any special requirements?
No, you just need to have the mod downloaded and running on both client and server machines, that's it.

### How do I use it?
Open your chosen map in the editor, and pick an object to get the UI action, then place it wherever. 
Drop a 'Firefight Core Module' on the map in the editor, and sync that to your chosen object. 
Next, drop 'Firefight Position Module' elements in towns/built up areas you've made, and sync those to the core module.
You can set a custom name for the position in the module if you want, otherwise it'll try to use the nearest named locations name.

Once done, jump into the game, look at your chosen UI object, and select the 'Open Skirmish Spawner' action to open the menu. 
Select your chosen enemy faction (will depend on your side as to what's available), the location to fight in, radius to spawn units
in, and how heavy resistance should be, then hit the green button. 

You will receive a new task once the spawning process is done. The task completion requirement is very simple; you need to control the area you spawned enemies at by numbers/strength.
There will also be 2 additional side-objectives 'hidden' in the AO, which can be:
Fuel Depot - Destroy
Small Cache - Destroy
Large Cache - Destroy
Crashed Heli - Secure blackbox (custom holdaction)
Comms Relay Post - Disable comms (custom holdaction)

Those objectives are not required to complete the main task. 

The skirmish itself will be garrisoned infantry with some patrols scattered about. Vehicles will come later, but are not spawned now.
Spawned units and objectives are added to Zeus control. 

You can clear the currently spawned skirmish via the button in the UI if you want to reset or pick a different area. 

### What's planned for the future?
- Add light/medium vehicle spawning for garrisons.
- Add QRF for garrisoned forces that can come in. 
- More (and varied) secondary objectives.

### I have a problem...
Please file [an issue using this link.] (https://github.com/SpartanD39/s39_firefightModules/issues/new) I cannot promise I will be able to fix every issue presented, but I will certainly try.

