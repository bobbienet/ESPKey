# NOTE this is a fork of the original ESPKEY by octosavvi

This fork is based on the original espkey by [octosavvi here](https://github.com/octosavvi/ESPKey/releases/latest), however the original hasn't been updated in quite some time which is why I've decided to fork the original and update portions to enable you to order your own from a pcb house instead of purchasing a premade unit.
Bill of materials and ordering information is located in the [hardware](https://github.com/bobbienet/ESPKey/tree/master/hardware) subdirectory. 

## Example of a small batch

<img src="https://github.com/bobbienet/ESPKey/blob/master/images/dime4scale.png" alt=pads width="568"/>

### Purchasing units
Redteam tools sells the original espkey [here](https://redteamtools.com/espkey) and the cost of a single unit is cheaper than ordering a small run yourself, however if you wish to purchase more than one unit then it may be cheaper to instead [build them yourself](hardware/) (or through a pcb manufacturer) for anything more than a single unit

### What the heck is this anyway?
ESPKey is a small device which can be implanted into facility access control systems.  ESPKey is compatible with pretty much every door that requires a card swipe or tap with optional pin code to unlock.  It even works on many systems requiring finger print or other biometric authentication.  Inserting an ESPKey behind a card reader is better than a skimmer because not only can it log all authorized use of a system, it can also inject or replay captured credentials.  Once ESPKey shows you what credentials work on this door, use your favorite RFID tools to clone or simulate those credentials for use on other doors.  Want to show someone how insecure their facility is?  This is an incredibly easy way to start.

In case you need a simple access control system to play with, ESPKey can do that too.  All you need is a card reader, ESPKey and some device to be controlled (like a door lock, electric strike, magnetic lock or just an indicator light).  ESPKey replaces the giant door controller, allowing you to build a simple mobile test lab.  Or a great little portable RFID credential sponge, ready to be hand carried or installed in any heavily trafficked area.

### Releases
Have a look [over here](https://github.com/octosavvi/ESPKey/releases/latest) for the latest pre-built firmware and UI release.

### Build instructions
Open in Arduino IDE and click Verify (or Upload if connected to UART).

### Usage
Check out [this great documentation](https://redteamtools.com/espkey) put together by Babak of Red Team Tools.

### Hardware
Hardware can be [purchased](https://redteamtools.com/espkey) or have a look in the [hardware](hardware/) directory if you want to build your own.
