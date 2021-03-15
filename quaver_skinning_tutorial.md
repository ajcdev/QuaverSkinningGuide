# Quaver Skinning Tutorial

## Table of Contents
- Getting Started
  - What is skinning?
  - Some Frequently Asked Questions

- Creating the Gameplay Elements
  - Notes
  - Receptors
  - Lightings
  - Stage
  - Grades
  - Numbers
  - Scoreboard
  - Multiplayer
  - skin.ini values

- Creating the Main Menu and Song Select Interface
  - Main Menu
    - Navigation Buttons
    - Panels
    - Background
    - skin.ini values
  - Song Select
    - Mapset Selection Panels
    - Leaderboards & Personal Best Panel
    - Key and Game Modes
    - skin.ini values

- Uploading the skin in Steam Workshop
  - Requirements for uploading the skin
  - How to revert the updates of your skin
  - How to update your skin properly

---

# Getting Started

## What is skinning?

- Skinning is one of features in Quaver where you can customize the client interface, gameplay interface, and the sound effects of the game.

## Some FAQs

### Is there an osu!mania skin to Quaver converter?

> Yes, there is a converter available made by Adri.

- You can download it here: https://rhythmgamers.net/QBC/

- Tutorial on how to convert mania skins to Quaver: https://www.youtube.com/watch?v=pWeLbx48NVI

- Changelogs: https://gitlab.com/Adri-/quaverskinconverter#changelog

> Note: The converted skin may not have the exact same gameplay in Quaver as it is in osu!mania. You will have to configure the elements and the skin.ini after converting.

### Is there a default skin template to begin with?

> Yes. The new default skins can be found in Janko's Steam Workshop.

- Link to Janko's Steam Workshop: https://steamcommunity.com/id/janko5/myworkshopfiles/?appid=980610

    - In order to get the skins, you must subscribe to them. After subscribing, they can be found in the workshop folder.
      - Quaver Steam Workshop Folder Location: `/Steam/steamapps/workshop/content/980610`
      - New Default Skin Steam ID Numbers:
        - Arrow: `2163713057`
        - Bar: `2162713645`
        - Circle: `2163546266`
      - Note: This is also where you can find the rest of the skins you're currently subscribed on the Steam Workshop.

    - You must copy these folders and paste them to your own Quaver Skin Folder in order to be able to edit because the workshop folder does not support updating local changes.
      - Quaver Skin Folder Location: `/Steam/steamapps/common/Quaver/Skins`

> However, if you want the old default/legacy skins, you can download it here below:

 - [Arrow Skin](https://github.com/chirijidev/QuaverSkinningGuide/raw/main/assets/Default_Arrow_Skin_New_Theme.qs)
 - [Bar Skin](https://github.com/chirijidev/QuaverSkinningGuide/raw/main/assets/Default_Bar_Skin_New_Theme.qs)
 - [Circle Skin](https://github.com/chirijidev/QuaverSkinningGuide/raw/main/assets/Default_Circle_Skin_New_Theme.qs)

After downloading one of the old default skins, you should drag the files in the game in order to load the skins. They will be located in your local Skin folder.

### Which programs should I use for making a skin?

- An image-editing software(just use one of them):
  - List of my recommendations:
      - [Adobe Photoshop](https://www.photoshop.com/en)(paid)
      - [GIMP](https://www.gimp.org)(free)
      - [paint.net](https://www.getpaint.net/index.html)(free)
      - [Photopea](https://www.photopea.com)(free)
      - [Figma](https://www.figma.com)(free)

- A text editor(you can still use Notepad, but this can help you do better for skin.ini editing.):
  - [Notepad++](https://notepad-plus-plus.org)(free)
  - [Sublime Text](https://www.sublimetext.com)(free)
  - [Visual Studio Code](https://code.visualstudio.com)(free)

- An audio-editing software(that is if you want to add custom SFX for your skin):
  - [Audacity](https://www.audacityteam.org)
  - [FL Studio](https://www.image-line.com)