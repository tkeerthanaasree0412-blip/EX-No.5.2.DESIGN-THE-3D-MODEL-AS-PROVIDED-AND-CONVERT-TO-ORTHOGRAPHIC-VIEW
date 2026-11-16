# EX No.5.2.DESIGN THE 3D MODEL AS PROVIDED AND CONVERT TO ORTHOGRAPHIC VIEW
## DATE:

## AIM: 
To create orthographic view of given 3D model

## REQUIREMENTS: 
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:

Step 1: Switch to Hybrid Design Mode

1. Open Autodesk Fusion 360 and start a new design file.

2. Look at the Browser panel on the left side of the screen.

3. Right-click the top-level root component (shown as  Unsaved in a new file).

<img width="347" height="321" alt="image" src="https://github.com/user-attachments/assets/cdcdb89c-91e7-4fa3-9488-53f9fc284844" />


4. Select Switch to Hybrid Design from the menu (if it is currently set to Part Design).

<img width="550" height="239" alt="image" src="https://github.com/user-attachments/assets/b3223d4a-36c3-404f-a845-b4eaf6742204" />


Step 2: Create the Tabletop (Base) with Corner Slots

1. Click Create Sketch (top-left toolbar) and select the horizontal XY (Bottom) Plane.

<img width="606" height="682" alt="image" src="https://github.com/user-attachments/assets/f5e42a9b-158a-4777-96cc-89b2fa7efddd" />


2. Select the 2-Point Rectangle tool (R), click the origin point, and draw a square with dimensions 30 mm × 30 mm. Click Finish Sketch.

<img width="363" height="461" alt="image" src="https://github.com/user-attachments/assets/969e6a9c-e3eb-48e1-bb5f-01a53f51b5a4" />


3. Click Extrude (E), select the square profile, and set the distance to 4 mm (Operation: New component). Click OK.

<img width="503" height="605" alt="Screenshot 2026-11-03 211338" src="https://github.com/user-attachments/assets/80284cfa-044b-486f-b022-820bff039712" />
<img width="526" height="444" alt="image" src="https://github.com/user-attachments/assets/b7663dbc-a08f-44b8-8a97-a5f2251a655c" />


4. Orbit to look at the bottom face of the tabletop, click Create Sketch, and select that bottom face.

5. Using the 2-Point Rectangle tool (R), draw four 2 mm × 2 mm squares snapped cleanly into each of the four outer corners of the bottom face. Click Finish Sketch.

6. Click Extrude (E), select all four 2 mm × 2 mm corner squares, set the distance to -1 mm (pointing inward into the tabletop) with Operation set to Cut, and click OK.


7. Look at the Browser panel on the left side of the screen.Right click on new component and choose rename option and rename it as base

<img width="395" height="849" alt="image" src="https://github.com/user-attachments/assets/fa3ad966-2bc0-4881-a266-512fab4d61f2" />

8.Close the view button near the base(new component) so that it is hidden
Step 3: Create One Table Leg (Leg)

1. Click Create Sketch (top-left toolbar) and select the vertical Front Plane (XZ plane)

2. Select the 2-Point Rectangle tool (R) and draw a rectangle with a length (height) of 30 mm and a width of 2 mm. Click Finish Sketch.

3. Click Extrude (E), select the 30 mm × 2 mm rectangular profile, and set the distance to 2 mm.

<img width="503" height="605" alt="Screenshot 2026-11-03 211338" src="https://github.com/user-attachments/assets/80284cfa-044b-486f-b022-820bff039712" />
<img width="526" height="444" alt="image" src="https://github.com/user-attachments/assets/b7663dbc-a08f-44b8-8a97-a5f2251a655c" />


4. In the Extrude dialog box, change the Operation dropdown to New Component and click OK. (You can double-click the newly created component in the Browser to rename it Leg).

Step 4: Duplicate the Legs

1. Activate the top-level root component in the Browser.

2. Right-click the Leg component in the Browser and select Copy.

<img width="230" height="863" alt="image" src="https://github.com/user-attachments/assets/b25c714e-090f-4741-9ebd-9fc5d1d0a687" />


3. Right-click the top-level root component again and select Paste new.

<img width="242" height="694" alt="image" src="https://github.com/user-attachments/assets/d25fb482-36b4-4aad-80b3-33936952fd87" />

4. Drag the directional arrow slightly to move the copied leg aside and click OK.

<img width="704" height="492" alt="image" src="https://github.com/user-attachments/assets/6bd7da88-6df6-4daf-b8d6-de260e08641f" />
<img width="491" height="528" alt="image" src="https://github.com/user-attachments/assets/dc9c2e07-9810-498d-b156-1ef4607e8164" />

5. Repeat the Paste step two more times until you have 4 identical leg components (Leg:1, Leg:2, Leg:3, Leg:4).

Step 5: Assemble Using Rigid Joints

1. Click Assemble > Joint (J) on the top toolbar.

<img width="577" height="657" alt="image" src="https://github.com/user-attachments/assets/81d0e437-8af4-48b7-989a-aeb72f644c8d" />


2. Hover over the top face of the first leg and click its outer corner vertex to set Component 1.

3. Hover over the recessed inner face of one of the 1 mm corner pockets on the bottom of the tabletop (Base) and click its matching outer corner vertex to set Component 2.

4. In the Joint dialog box and click OK.

5. Repeat the Joint (J) command for the remaining three legs, snapping each leg's top outer corner into the remaining three recessed pockets.

Step 6:Convert it into a drawing file 

Save the file (Ctrl + S), switch workspaces via DESIGN > Drawing > From Design, place your Base and Projected Views on the sheet, add dimensions using the Dimension (D) tool, and export as a PDF.

<img width="284" height="453" alt="Screenshot 2026-10-11 172436" src="https://github.com/user-attachments/assets/791a7848-79b6-48fa-96ec-eda30dd4ffe9" />
<img width="415" height="462" alt="Screenshot 2026-10-11 172509" src="https://github.com/user-attachments/assets/1aa05324-408b-4662-8023-ad03cfe4a88e" />


## INPUT

<img width="838" height="607" alt="image" src="https://github.com/user-attachments/assets/e05baa35-b41b-47a0-be9f-f3bd6b329547" />


## OUTPUT

<img width="1527" height="696" alt="Screenshot 2026-11-16 131804" src="https://github.com/user-attachments/assets/0106d02f-7127-47e0-bde8-8cf57b03d5cb" />
<img width="838" height="607" alt="image" src="https://github.com/user-attachments/assets/e6a6dba5-29b1-40c0-8cc1-b909568ddbd9" />


## RESULT:
Thus, the given 3D model is converted into orthographic view.
