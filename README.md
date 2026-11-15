# EX No.4.1. CUT SECTION OF SOLIDS
## DATE:

## AIM
To create the solid model from given drawing and section the solid model

## REQUIREMENTS: 
1. Autodesk fusion 360
2. Windows 10
3.16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:
# PROCEDURE

### Step 1: Create the base plate

1. Open Fusion 360 and select the **Design → Solid** workspace.
2. Click **Create Sketch** and select the Top (XY) plane.
3. Choose **Sketch → Line** and draw the central portion of the base plate.
4. Draw two semicircular ends using **Sketch → Arc → 3-Point Arc**, each having a radius of 15 mm (R15).
5. Connect the rounded ends using straight lines to form the outer boundary of the base plate.
6. Maintain a distance of 70 mm between the centres of the two rounded ends.
7. Maintain a distance of 15 mm from each mounting-hole centre to its corresponding outer end.
8. Use the **Trim** command to remove unwanted sketch portions and complete the closed profile.
9. Click **Finish Sketch**.
10. Select **Extrude**, choose the base plate profile and enter 10 mm as the extrusion distance.
11. Press Enter to create the base plate.

### Step 2: Create the central cylindrical support

12. Select the top face of the base plate and click **Create Sketch**.
13. Choose **Sketch → Circle → Center Diameter Circle**.
14. Place the circle at the centre of the base plate.
15. Enter 50 mm as the diameter (Ø50).
16. Click **Finish Sketch**.
17. Select **Extrude** and choose the circular profile.
18. Enter 28 mm as the extrusion distance.
19. Select **Join** as the operation to combine the cylindrical support with the base plate.
20. Press Enter to create the central cylindrical support.

### Step 3: Create the central circular opening

21. Select the top face of the cylindrical support and click **Create Sketch**.
22. Choose **Sketch → Circle → Center Diameter Circle**.
23. Place the circle at the centre of the cylindrical support.
24. Enter 20 mm as the diameter (Ø20).
25. Click **Finish Sketch**.
26. Select **Extrude**, choose the circular profile and select **Cut** as the operation.
27. Set the cut extent to pass through the entire cylindrical support and the base plate.
28. Press Enter to create the central through-hole.

### Step 4: Create the upper circular recess

29. Select the top face of the cylindrical support and click **Create Sketch**.
30. Choose **Sketch → Circle → Center Diameter Circle**.
31. Draw a concentric circle with a diameter of 30 mm (Ø30).
32. Click **Finish Sketch**.
33. Select **Extrude**, choose the circular profile and select **Cut** as the operation.
34. Enter 6 mm as the cutting depth.
35. Press Enter to create the circular recessed portion around the central opening.

### Step 5: Create the two mounting holes

36. Select the top face of the left mounting end and click **Create Sketch**.
37. Choose **Sketch → Circle → Center Diameter Circle**.
38. Place the circle at the centre of the left rounded end.
39. Enter 12 mm as the diameter (Ø12).
40. Click **Finish Sketch**.
41. Select **Extrude**, choose the circular profile and select **Cut** as the operation.
42. Extend the cut through the entire 10 mm thickness of the base plate.
43. Repeat the same procedure on the right mounting end to create the second Ø12 hole.
44. Ensure that both mounting holes are aligned along the same centre line.

### Step 6: Create the additional opening in the support

45. Select the appropriate front face of the cylindrical support and click **Create Sketch**.
46. Use **Sketch → Line** to draw the required rectangular profile according to the front view.
47. Maintain the specified 50 mm overall width and 30 mm internal width shown in the drawing.
48. Use the **Dimension** tool to position the profile correctly.
49. Click **Finish Sketch**.
50. Select **Extrude**, choose the required profile and select **Cut** as the operation.
51. Apply the cut according to the hidden-line representation in the drawing.

### Step 7: Final inspection and drawing

52. Use the **Orbit** tool to inspect the completed model from different directions.
53. Verify the base plate thickness of 10 mm and the central support height of 28 mm.
54. Check the central support diameter of 50 mm.
55. Verify the central hole diameter of 20 mm and the recessed diameter of 30 mm.
56. Check that the recessed portion has a depth of 6 mm.
57. Verify both mounting holes have a diameter of 12 mm and the rounded ends have a radius of 15 mm.
58. Use the **UNION** operation wherever necessary to combine the solid features.
59. Save the completed 3D model.
60. Generate the front, top and side views along with the isometric view using the Drawing workspace.
61. Add the required dimensions, centre lines and hidden lines to complete the engineering drawing.

## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198825351-b514a4e7-06af-4ee0-8197-e8267749f8a8.png)

## OUTPUT:
<img width="1010" height="717" alt="Screenshot 2026-11-15 185455" src="https://github.com/user-attachments/assets/7ceef730-c30e-43d1-af0b-411f50cdc148" />

## RESULT:

Thus, the cut section for solid model is created.

