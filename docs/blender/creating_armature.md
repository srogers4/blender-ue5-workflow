# Overview
Creating an armature for your model allows the mesh to move. It uses `bones` that are parented
to each other in order to move the mesh.

## Create the Armature
`Shift+A` to open the add menu. `Armature` to add an armature to the scene. 

![add](assets/images/mesh_add_armature.png)

Once it's added, move it to the top level of the `Scene` so you your collection and armature separate.

![separate](assets/images/mesh_armature_menu.png)

## Make the Bones
Now we add bones to the armature where bones would exist in the mesh. When you create an armature
it will create a single bone where you cursor is currently.

???+ tip "Bones in Front"
    Enable the `In Front` option under `Data -> Viewport Display` so that the bones are always
    displayed in front of the mesh. 

    ![bones_in_front](assets/images/mesh_bones_in_front.png)

???+ tip "Symmetrize"
    You only need to make bones on the `+Y` side of the mesh. You can mirror the bones across the `X` axis
    in the Bone `Edit Mode` under `Armature -> Symmetrize`.

    ![symmetrize](assets/images/mesh_bone_symmetrize.png)