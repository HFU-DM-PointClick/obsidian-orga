Lockpick mini game should be in the style of the lockpicking mechanik in skyrim or fallout 4 (its the same)

![[Pasted image 20250111151656.png]] (Skyrim)
![[Pasted image 20250111151739.png]]
(Fallout 4)
only diffrence is the design mechanically speaking its the same 
Finished design from pierre
![[lock_pick_background.png]]
Background that will rotate when picking the lock

![[lock_pick_layer.png]]
foreground overlays over the lock

![[lock_pick_gear.png]]
this is the lock pick that will rotate with the lock when hitting the right spot


About the Bug that occurs when starting the game and Godot recreating the deleted tscn files
Godot recreates them when saving godot not on testing the game
apperntly to my understanding the .gd and .tscn file need to be in the folder
when testing this issue whit this so called fix didn´t work when testing Godot was still recreating the files

perhaps the checkbox as said in this forum post: https://forum.godotengine.org/t/ghost-scripts-unnecessary-duplicate-gd-files-ending-in-tscn-1/3271/2 
was active when creating the files i couldn´t find the save option in the inspektor to try this approach maybe someone eles has more luck then me 
on the otherhand i do not understand why we try to fix this issue for so long it dosnt break the game and the scenes will probably never be used again 
