# TourGuide

### Installation

```
git checkout https://github.com/Loathing-Associates-Scripting-Society/TourGuide.git Release
```

### Updating

```
git update
```

### Migrating from SVN to Git

With Mafia support now implemented for git you can now remove the old SVN repo and convert to git.

```
svn delete Loathing-Associates-Scripting-Society-TourGuide-branches-Release
```

Then install TourGuide as normal.

### How do I use it?
Once it's installed, look in the relay browser. In the upper-right, there will be a **"run script"** menu. Select TourGuide and it will dock to the side of your window.

![Instructions](/Images/Instructions.png)


### What does it do?
TourGuide is a relay script which will give advice on playing [Kingdom of Loathing](http://www.kingdomofloathing.com) within [KoLmafia](http://kolmafia.sourceforge.net). It details how to complete quests you're on, and what resources you have available.

It keeps track of your quests and resources and helps you complete ascensions as fast as possible.

#### Quest advice:

![Quest Example 1](/Images/Quest_1.JPG)

![Quest Example 2](/Images/Quest_2.JPG)

#### Resources:

![Resource 1](/Images/Resource_1.png)

![Resource 2](/Images/Resource_2.png)

The script will inform you of many resources you have - free runaways, banishes, semi-rares, etc. - and ideas on what to use them on.

**Quests supported**: All council quests, azazel, pretentious artist, untinker, legendary beat, most of the sea, unlocking the manor, the nemesis quest, pirate quest, repairing the shield generator in outer space, white citadel, the old level 9 quest, jung man's psychoses jars, and the wizard of ego.

### Development guidelines
TourGuide is open source and contributions are encouraged!

The release above is a compiled version of the development version, which can be found by checking out https://github.com/Loathing-Associates-Scripting-Society/TourGuide. The release is compiled via Compile ASH script.rb, which collects many scripts into one for ease of release.

This script, as well as its support scripts, are in the public domain.

This is a fork of https://github.com/cdrock/TourGuide, which is in turn a fork of Ezandora's Guide.

For support, questions, and comments visit the Ascension Speed Society discord channel.
