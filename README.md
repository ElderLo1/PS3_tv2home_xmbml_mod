# PS3_tv2home_xmbml_mod
IMPORTANT: Tested working on HFW 4.90 and PS3HEN 3.2.0 -- this mod was made with 4.89 in mind so compatibility is NOT guaranteed for lower versions.

A simple PS3 xmbml mod turning the TV category into a directory for PlayStation Home offline builds. Also removes the Home icon from appearing under the PSN category to better suit this change.

Home builds will appear under a folder within TV/Video Services, allowing you to not only run several builds of Home Offline, but also download them directly from your PS3! (HEN or CFW required! This will NOT work on OFW!)

Has been tested working on HEN 4.89. I would advise against installing this on a version lower or higher than this firmware.

Please bear in mind that I am a total noob when it comes to XMBML modding. It's working for me personally, but I am not responsible for the chance of you bricking your own console with this. Someone with more experience could tidy this up or just make it 10x better overall but for now it's working fine.

If you wish to have a version where DeViL303's excellent SDAT Dumper is also available for download from the very same menu (no guaruntees about it appearing under the Builds folder, however.) it can be found [at this branch I made recently](https://github.com/ElderLo1/PS3_tv2home_xmbml_mod/tree/SDAT-dumper-included).

## Important Notes (read before proceeding!)
- You need to edit the XMBML files in category_tv.xml to point to your webserver where the pkg files are held, otherwise it will likely 404 or time out.
- All builds of Home Offline must have their PARAM.SFO modified to ensure the category is "HM", otherwise they will NOT appear under the builds folder!
- By default, the XMBML files use spoofed content IDs of other apps for safety -- you can either modifiy these to original content IDs or resign your builds of Home Offline to use these spoofed content IDs. Either way, it's not gonna work without some legwork on your part.

## Can I fork or make contributions to this?
Sure can! Just be sure to test it on your own PS3 (preferrably with video/image proof of it working and info about what CFW/HEN you're running as well) before you commit it or make a pull request!

## To-do:
- Find a way to give each version on the XMB it's own title with the version number rather than all of them simply saying "PlayStation Home". Hope it's possible without RCO editing but very unlikely to be honest. As of right now it shows 4 builds with the same name (The download folder lists 0.41, 0.97, 1.00, and 1.86 in that order for reference)
- Quit option still appears under PSN. Find a way to move it to TV/Video Services without conflicting with anything else in that category (i.e. custom items in the SF category)
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
- DeViL303 for his excellent work and documentation on XMBML as well as his offline builds of Home used in this experiment. In other words, he was probably the biggest resource for this little experiment of mine, props should really go to him!
- PS3DevWiki for being a good learning source for XMBML code
- Sony for the creation of the PS3
