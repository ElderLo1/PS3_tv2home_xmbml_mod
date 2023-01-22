# PS3_tv2home_xmbml_mod + SDAT Dumper
A simple PS3 xmbml mod turning the TV category into a directory for PlayStation Home offline builds. Also removes the Home icon from appearing under the PSN category to better suit this change.

Home builds will appear under a folder within TV/Video Services, allowing you to not only run several builds of Home Offline, but also download them directly from your PS3! (HEN or CFW required! This will NOT work on OFW!)

Has been tested working on HEN 4.89. I would advise against installing this on a version lower or higher than this firmware.

Please bear in mind that I am a total noob when it comes to XMBML modding. It's working for me personally, but I am not responsible for the chance of you bricking your own console with this. Someone with more experience could tidy this up or just make it 10x better overall but for now it's working fine.

## Can I fork or make contributions to this?
Sure can! Just be sure to test it on your own PS3 (preferrably with video/image proof of it working and info about what CFW/HEN you're running as well) before you commit it or make a pull request!

## To-do:
- Find a way to give each version on the XMB it's own title with the version number rather than all of them simply saying "PlayStation Home". Hope it's possible without RCO editing but very unlikely to be honest. As of right now it shows 4 builds with the same name (The download folder lists 0.41, 0.97, 1.00, and 1.86 in that order for reference)
- Quit option still appears under PSN. Find a way to move it to TV/Video Services without conflicting with the PS Store if possible (or users of this mod can just use the old PS store instead since it's sooo much better than the new garbage fire of a store but I digress)
- Icon for downloading builds and text for builds to be downloaded do not appear on in-game XMB. While minor, i'd like to get this fixed. May help if the first thing on the To-Do list is completed somehow.

## Install instructions
1. Download and unzip this repository or use git to clone it.
2. Make modifications to the XML to point to your own webserver to serve the PKGs.
3. Drag the "custom" folder onto pkg_custom.exe
4. Install PKG on HEN-enabled or CFW PS3
5. Restart PS3 to refresh XMB as soon as possible
6. ???
7. Profit!

## Special Thanks to:
- DeViL303 for his excellent work and documentation on XMBML as well as his offline builds of Home and the SDAT Dumper tool used in this experiment. In other words, he was probably the biggest resource for this little experiment of mine, props should really go to him!
- PS3DevWiki for being a good learning source for XMBML code
- Sony for the creation of the PS3
