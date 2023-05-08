# Roblox-IK-R15

Index

1-Preparing Blender.

2-How to animate the Rig.

3-Animating the Rig.

4-Exporting the Animation.

# Preparing Blender.

Before you start, you need to install the “RbxAnimations” Credit to Den_S/@DennisRBLX, first you start Blender, go to “Edit” and go to preferences, now you go to Add-ons and install, select the RbxAnimations.py after the installation, restart the Blender.
Download the R15IK Blender archive and open it, you will see a Roblox Rig and a bunch of others things.

Must be something like this

![Blend](https://user-images.githubusercontent.com/125750057/236719011-2403b6a7-3227-40ed-a91e-03cb17a8da24.png)

Now, let's see how to animate with the Rig.

# How to animate the Rig.

First, go to Object Mode and select the Armature(__Rig) and go to “Animation” if you can't move the bones of the Rig, try to put on the Pose Mode.

How to animate.

Let's start with the IcoSphere:

Use only position, and it rotates the bone that is connected(UpperArm, UpperLeg) based on the position of the IcoSphere and only rotates on the Z

![icosphere](https://user-images.githubusercontent.com/125750057/236720350-80194a15-cf55-4d73-8089-ede4553cc145.png)

Cube:

Use only position, and it rotates the bones of the Upper, Lower and Foot/Hand. Based on the position of the Cube and move to “all” the directions.

![Cube](https://user-images.githubusercontent.com/125750057/236722421-a66f7eb1-f267-4acb-91db-530321b67ec5.png)

Diamond:

Use position and rotation, it moves or rotates the whole model without the Cubes of the legs.

![Diamond](https://user-images.githubusercontent.com/125750057/236723222-2cfd080f-dfd8-453c-8657-136c4e7f85f9.png)

Star:

Use only position, moves the “floor”, move the Cubes of the legs.

![Star](https://user-images.githubusercontent.com/125750057/236723924-fdea0432-4f86-4861-b0f0-4c7fb40fdc5d.png)

SemiSphere:

Use only rotation, it rotates the LowerArm based on the rotation of the SemiSphere

![SemiSphere](https://user-images.githubusercontent.com/125750057/236724212-50c6a16b-8126-4d31-be06-f0fc1c4cfbe3.png)

Don't try to move the position of LowerArm.

If you rotate the UpperArm it will rotate the LowerArm.

You can use some bones normaly 

# Animating the Rig.

First active the AutoKeying.

![autokey](https://user-images.githubusercontent.com/125750057/236725937-69dfa6dd-8740-489f-8e68-ea3a557efdba.png)


And now we have this:

![frame](https://user-images.githubusercontent.com/125750057/236725561-1baf9a86-97cc-498f-a679-7aba30a01662.png)

You can move the blue thing to select which keyframe you want

60 keyframes is 1 second because is 60 fps.

I set 60 fps default, but you can change going to the output properties, frame rate

![framerate](https://user-images.githubusercontent.com/125750057/236726753-037dd4bb-e96f-4529-9672-cff428439db9.png)

Now move the bones and set the frame to make the animation.

Example:

![Blender](https://user-images.githubusercontent.com/125750057/236730077-8f32006a-1ee7-4619-89f5-afc72b62231b.gif)

# Exporting the Animation.

When you finished your animation, press  “N” on the keyboard and select the RbxAnimations tab, if you don't see this tab, try to reinstall the add-on.
and press “Export Animation”.

Now you can close the Blender and open the Roblox Studio

But you need to install the plugin on the Roblox Studio, to do this, use this link https://create.roblox.com/marketplace/asset/716953901 or on toolbox, search “Blender rig exporter/animation importer”

Open a Baseplate and make an R15 Rig, open the BlenderAnimation Plugin and click on the Rig, now click “Import Animation” on the new tab(script) press Ctrl+V.

Now we are done.

Just upload your animation on Roblox and you can already use your animation.
