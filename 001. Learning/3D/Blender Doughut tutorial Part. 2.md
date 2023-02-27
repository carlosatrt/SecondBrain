- [ ] # Blender Doughut tutorial Part. 2

**Tags:** #Blender, #BlenderGuru
**Date:** 13-01-2022

---

## Learnings

##### Commands learned
- *Select Item* + **N** --> Open Properties details pane
- *Select Item* + **S** --> Transform Scale Object
- **Control** + **Tab** --> Open mode selector
- *Select Item* + **G** --> Transform Move Object
- *Select Item* + **R** -- Transform Rotate Object
- *Shift* + *Select Item*
- Click the command icon in top view of the viewport --> Proportional editing 
- *Click on Select menu & Choose Select Random option*--> Select rabndom
- *Use the Icon present in the viewport* --> Fall of Type

##### Shortcuts learned
- **Shift** + **A** --> Add Object
- **F9** --> Re-Open the ***Add Mesh Properties***
- *Control* + **A** --> Apply change 
- *Tab* --> Jump from Object mode to Edit mode and viceversa
- **O** --> Proportional editing
- *Alt* + **S** --> Shink & Fatten, Move along Normals

##### Theory
- A Single point of a 3D object is called a ***Vertex***.
- Multiple points of a 3D object are called ***Vertices***.
- 4 ***Vertices*** make a Face.
- A Group of more the 3 faces joined together make a mesh.


---
## Tips
- Most of the time we use the Mesh function.
- Click **F9** to bring the ***Add Mesh Submenu*** or Delete & Re-Add the Torus Mesh
- Try to keep the segments as squres.
- Keep Scale to one by applying your scale.
- Keep the SubSurf low on Viewport and a Max of 2 in render.
- Make sure to change from edit mode when unnable to select another object like camera

---
## Process
1. Create a torus mesh.
	```
	Shift + A and select Mesh > Torus
	```
2. Modify innitial Object Parameters for Mesh (Modify Resolution).
	```
    40 Major segments
    16 Menor segments
	```
3. Scale torus properties to around *10cm* for real world meassurments.
	```
   Use N when Item is selected to open the Obejct Properties pane.
	Use S to scale to around 10cm
	```
4. Aplpy scale.
	```
	Use control A to open the apply pane and select Scale.
	```
5. Remove jagged lines.(Illusion)
	```
	Right click with the object selected and select Shade Smooth
	```
6. Apply Subdivision Surface.
	```
	With the object selected click the Wrench icon "Modifiers Panel" & add the Modifier called "Subdivision Surface (SubSuf)".
	```
7. Go into Edit mode.
	```
	Use Tab to jump from Object mode to Edit mode.
	```
8. Enable Proportional editing.
	```
	Click O with the object selected to activate proportional edition or use the viewport icon. Scroll Up to lower the proportion until you see .04, you should see the gray cricle when you move.
	```
9. Adjust vetexs to create imperfections on the Donut.
	```
	Use "Shrink & Fatten tool(Alt + S)" to scale the vertex according to which direction the faces are pointing to.
	Jump between Object and Edit mode
	```
10. If you go to the Select menu you can use "Select random" to atumatically select multiple random verticies to alter, you can now use the Shrink & Fatten tool to alter all at the same time.

