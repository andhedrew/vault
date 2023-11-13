Name slots all the same in photoshop
highest level folder should be [skin]
use [slot: name][merge] as the folder name prefix

export with JSON

In Spine: Import Data

import into existing skeliton

IGNORE existing attachments

Click "import"

Create skin-target bone
Convert all images of new character into meshes so they're not effected by bone movement

Bind all meshes to root
Create transform constraint (NAME-scale  ) pointing to skin target (we'll be leaving that one alone)
Use this constraint to scale the skeleton down (mix: Scale 100%, offset -0,5 or so)
Drag new transform constraint, and drag under the new skin

Bind the images to the new bones

https://www.youtube.com/watch?v=T2vO7Gnr074 


