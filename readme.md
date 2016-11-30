Edit video using blender
------------------------------------------

[French version](http://github.com/tutoblender/videoEdit/blob/master/readme.fr.md)    

[Blender](http://blender.org) is not only a 3D application, it can be use to edit video.   
We are going to learn how to do a simple edit.

* Download blender : http://blender.org
* Video : ******TOADD******

# Setup the interface
We need to setup blender interface.   
The easiest way is to download a ready-to-use session and make it the default session.

* Download this file : http://vse.madnerd.org
* Click on **minimal_vse.blend**
* Save the session as default : **CTRL-U** puis **ENTER**

When you restart blender, the interface will stay on **Video Editing**    

Let's take a look at the interface.   

![Blender VSE](https://github.com/tutoblender/videoEdit/raw/master/doc/interface.jpg)    
* At the **top**, We can see the **video preview**
* At the **bottom**, We can see the **sequence editor**
* At the **right**, We can see the properties of our project

# Add a video sequence

![Sequence Editor](https://github.com/tutoblender/videoEdit/raw/master/doc/sequence.jpg)    
To add a video/audio sequence, just **drag and drop** the file into the sequencer editor
Two strips will be created:
* **Dark blue** : Video
* **Cyan** : Audio 

# Play the video
* Key **ALT-A** : Play the video
* Key **P** : Set preview zone

# Cut a sequence
* **Right** Click : Select the sequence
* **Left** Click : Move the **green bar**
* Key **K** : Cut the sequence

# Move a sequence 
* **Right** Click : Select a sequence
* Key **G** : Move the selected sequence
* Key **B** : Select multiple sequences 

# Save your movie
Once, you have edit your video, You will have to render it.   
Before this, save your project (**File/Save As** at the **top**).    
You should saved the .blend file in the same folder than the videos.

![Render movie](https://github.com/tutoblender/videoEdit/raw/master/doc/render.jpg)    
## Set the duration 
* With the **green bar** move at the **beginning** / **end** of the movie
* Take note of the **start** frame and the **end** frame (**At the bottom**)
* Copy this value on the **right** in **Frame Range** (Start Frame/End Frame)

## Save
![Video save path](https://github.com/tutoblender/videoEdit/raw/master/doc/save.jpg)    
* **On the left** in **Output**, check the path where the video will be saved    
* Click on **Animation** 
* The video will be saved on **c:\videos**

The sequence editor will be replaced by a **video player**.
To put the sequence editor back, click on the icon at the **Bottom Left** with a picture icon and change it to **Video Sequence Editor** 
![VSE Icon](https://github.com/tutoblender/videoEdit/raw/master/doc/vseicon.jpg)

## Shortcuts
![VSE Icon](https://github.com/tutoblender/videoEdit/raw/master/doc/shortcuts.png)    


