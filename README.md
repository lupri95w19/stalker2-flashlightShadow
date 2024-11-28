# stalker2-flashlightShadow

If you like this guide, you can:
- 🌟 **Add a Star** to my [GitHub Repo]([#](https://github.com/lupri95w19/stalker2-flashlightShadow)) (I really appreciate it!)
- ⭐ **Endorse this mod** on [Nexus Mods](https://www.nexusmods.com/stalker2heartofchornobyl/mods/447)


---

## **Disclaimer**
I am not the creator of these two mods. I just wanted to write a guide to help you activate flashlight-casted shadows.

---

## **Required Mods**
1. [Flashlight Customizer](#)
2. [Simple ModLoader and Console Enabler](#)

---

## **Installation Instructions**

1. Download and extract both mods.
2. Move the mod files into the `Paks` folder. Example path:
C:\Program Files (x86)\Steam\steamapps\common\S.T.A.L.K.E.R. 2 Heart of Chornobyl\Stalker2\Content\Paks

3. **If the game crashes**, delete the following files:
- `pakchunk99.*`
- `pakchunk221.*`
- `pakchunk222.*`

---

## **Enabling Flashlight Shadows**

### **Step 1: Open the Developer Console**
1. Launch the game and open the developer console using `~` (tilde) or `` ` `` (backtick).
2. If it doesn't work, configure the console key by editing the `Input.ini` file:
- Path:
  ```
  C:\Users\yourUser\AppData\Local\Stalker2\Saved\Config\Windows\Input.ini
  ```
- Add or modify the following section:
  ```ini
  [/script/engine.inputsettings]
  ConsoleKeys=Tilde
  ConsoleKeys=RightBracket
  ConsoleKeys=Backslash
  ; ConsoleKeys=addYourKey ; this is a commented line
  ```
- [Find all key codes here](https://nerivec.github.io/old-ue4-wiki/pages/list-of-keygamepad-input-names.html).

---

### **Step 2: Load the Mod**
Type this command in the console (without quotes):
"mod add /Game/Mods/FLCustomizer/BP_MOD_FLCustomizer.BP_MOD_FLCustomizer_C"

---

### **Step 3: Activate Flashlight Shadows**
Enter the following commands in the console (without quotes):
"fl_shadows normal true fl_shadows volume true"

---

## **Conclusion**
Congratulations! Your game now looks more like a 2024 release. 🎉

To make things easier, I’ve uploaded my `Input.ini` file with my command history. Feel free to use it!
