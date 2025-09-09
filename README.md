# ELM FSPRO Recreation
[![fspro-banner.png](https://i.postimg.cc/mgZbrHKj/fspro-banner.png)](https://postimg.cc/fJF42JzS)

A recreation of the FSPRO for the Pizza Tower mod [**Egg's Lap Mod**](https://gamebanana.com/mods/464912) for those who want to use custom music and sounds or make their own ELM mods.
# How it works
It is practically the same as the original [PT-FSPRO-Recreation](https://github.com/Raltyro/PT-FSPRO-Recreation).  The same set-up applies to this one,  otherwise you'll have some missing sound effects, so make sure you import the assets from the base Pizza Tower banks like you would the normal FSPRO.

If you want to customize the music in the mod I have set it up for sideloading an extra master/music bank.

> Note: This guide uses material from the Double Yolked branch of the recreation,  but it will all work the same.

0. To ensure this works,  **BUILD THE BANKS ATLEAST ONCE BEFORE EDITING THEM** and put them in your ELM's `sound\Desktop\EggsLapMod` FOLDER.  Alternatively do your editing on a different branch/fork.

1. Inside of the project is a folder called `LapMusic`,  this folder features all the events referenced in-game by the events outside the folder.  For this example I will be editing the `lap3` and `Lap4Songs/Peppino/Absurziti` events.

![](https://i.postimg.cc/gkXpV0ty/LapMusic.png)

2. Once done editing,  assign the banks you are editing to the `ELMCustom/music` bank (Feel free to rename the folder if you want but this is what it'll come as by default).
   
![](https://i.postimg.cc/QdG2cJTs/Assigning.png)

3. Build the banks included in ELMCustom and place the folder in your ELM's `sound\Desktop\` folder.
   
![](https://i.postimg.cc/3w9z5MbJ/Folder-placement.png)

4. Open up UTMT and go to the `obj_fmod`'s create event (`gml_Object_obj_fmod_Create_0`)
    
![](https://i.postimg.cc/tT6qX40N/fmod-create.png)

5. Edit the banks array to include your custom banks and master *alongside* the ELM ones. (I adjusted the format of the array in this image to make it easier to edit)
    
![](https://i.postimg.cc/1tjTXGQk/Bank-array.png)

6. And thus your custom music should work now. In the event that this guide was pure nonsense to you,  I have also recorded and edited a visual guide of me setting the project up below.  The video also has a demonstration of the banks in action.
   
[![Click Me!!!](https://i.postimg.cc/GpjP41tq/setupguide2x.png)](https://youtu.be/F71KLrEZzxs)

# Music Credits (FSPRO)
- Vozaxhi - [Pillar John's Revenge](https://www.youtube.com/watch?v=MSzReOhnxXg)
- Inceptradom - [Absolute Absurziti V2](https://www.youtube.com/watch?v=8Vqa5lfr8Sk)
- Green2141 - [Absolute Absurziti - Legacy Edition [WORSE REUPLOAD]](https://www.youtube.com/watch?v=ESp0gOiYRpM) (& _sillicate - [How to Self Destruct](https://www.youtube.com/watch?v=NA5yxiphq74))

# Music Credits (Set-Up Guide)
- River347 - [Pillar John's Revenge (Remix)](https://www.youtube.com/watch?v=CUUn6xCTT7U)
- Ronach & SeagullBruh - [Spotlight's Thievery](https://www.youtube.com/watch?v=_ddAAz30ats)
- BilkShaked - [Universe Wide Destruction](https://www.youtube.com/watch?v=Xv7MzDaixP4)
