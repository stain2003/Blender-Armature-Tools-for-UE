# Blender-Armature-Tools-for-UE
A simple tool can help you rename bones, generate ik bones and reparent them to match UE typical skeleton, which allows you to use the new auto retarget feature

Usage:
Open the file via blender text editor, hit run the script.
You will see a new panel "UE Renamer" in the context bar.


**Armature:**

  Select the target armature you are renaming


**Bones to rename:**

  Chose which bone/bone chain you are renaming


**With metacarpal:**

  Is the current armature has metacarpal for fingers?
  auto: auto detect


**Side:**

  Which side of the bone you are renaming if it has mirror bone, e.g. hand_l and hand_r


**Rename selected bone:**

  Enter edit mode, you have three ways to rename bones:
  1. if you are renaming a single bone, not chain, select it and hit button
  2. if you are renaming a chain, select the top bone of this chain, e.g. select the clavicle bone to rename arm_chain
  3. if you are renaming a chain, select the whole chain, e.g. select bone from clavicle to hand(there should be 4 bones) to rename arm_chain


**Generate ik bones:**

  Generate ik bones.


**Reparent ue bones:**

  Require rename the bones first.
  Helpful if your bones are not connected or not the way as they should, 
  this feature helps you connect and parent bones that generally used in UE, prevent UE auto Retargetor not recognize the bone chains correctly.
  You will still need to reparent some extra bones yourself for example the hip bone mostly used in blender but not UE.
