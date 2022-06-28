# Foobar

Foobar is a Python library for dealing with word pluralization.

## Installation

Download the Template files, and open Godot.
Select "Import" and import the project. 


## Usage
Watch this video or follow the steps below:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://youtu.be/GQ96m3ZBLY0)


In the Scene menu, delete the "GodotSouls" KinematicBody and children.

Drag the "player\PlayerTemplate.tscn" file into the world scene. 
Open your own character, and copy/paste your Mesh and AnimationPlayer containing your character's animatinos. This template expects to see an Idle, Walk, Run, Roll, Jump, Attack1, Attack2, and Big Attack, although all these aren't necessary, jump and roll could be the same really, or each attack could be the same animation. 

Copy and paste into your Mesh and AnimationPlayer into the PlayerTemplate scene.

In the Scene menu, click on the KinematicBody node, and in the inspector click the "Player Animation Tree" button, and select the AnimationTree. 

Click the "Player Character Mesh" button and select any parent node of your 3D character mesh. Additional physics options are below if you want to speed up or slow down your character's actions.

In the Scene menu, select the Camroot spatial node. In the inspector click the "Player Character Mesh" button and select any parent node of your 3d Character mesh. 

In the Scene menu, select AnimationTree and click the "Anim Player" button and select your 3D meshes AnimationPlayer.

Inside the AnimationTree state machine node window, click on each action node.
For Idle, in the inspector click the dropdown and select your Idle-loop animatino
For Walk, Run, Etc, do the same, matching your animations with the actions of each node.

Save and run the game, all animations and controls should work.

License
[MIT](https://choosealicense.com/licenses/mit/)
