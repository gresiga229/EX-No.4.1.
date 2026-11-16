# EX No.4.1. CUT SECTION OF SOLIDS
## DATE:9/11/26

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
3. <img width="216" height="171" alt="Screenshot 2026-11-11 204524" src="https://github.com/user-attachments/assets/2c27e459-5443-4ebd-8871-208176dbb0fd" />

4. Choose **Sketch → Line** and draw the central portion of the base plate.
5. <img width="542" height="767" alt="Screenshot 2026-11-11 204541 - Copy (2)" src="https://github.com/user-attachments/assets/2db1b289-7b63-4951-b462-dec0bf733f2f" />

6. Draw two semicircular ends using **Sketch → Arc → 3-Point Arc**, each having a radius of 15 mm (R15).
7. <img width="448" height="347" alt="Screenshot 2026-11-16 091632" src="https://github.com/user-attachments/assets/1689d56f-f128-4acd-a6ca-702e8efdf27a" />

8. Connect the rounded ends using straight lines to form the outer boundary of the base plate.
9. Maintain a distance of 70 mm between the centres of the two rounded ends.
10. Maintain a distance of 15 mm from each mounting-hole centre to its corresponding outer end.
11. Use the **Trim** command to remove unwanted sketch portions and complete the closed profile.
12. <img width="530" height="430" alt="Screenshot 2026-11-11 204601" src="https://github.com/user-attachments/assets/8f013600-331b-4fcd-a47a-c237ecc2bf13" />

13. Click **Finish Sketch**.
14. Select **Extrude**, choose the base plate profile and enter 10 mm as the extrusion distance.
15. Press Enter to create the base plate.

### Step 2: Create the central cylindrical support

12. Select the top face of the base plate and click **Create Sketch**.
13. Choose **Sketch → Circle → Center Diameter Circle**.
14. <img width="517" height="395" alt="Screenshot 2026-11-11 204552 - Copy" src="https://github.com/user-attachments/assets/ede4bd38-6673-448a-9f48-40cd6641b56d" />

15. Place the circle at the centre of the base plate.
16. Enter 50 mm as the diameter (Ø50).
17. Click **Finish Sketch**.
18. Select **Extrude** and choose the circular profile.
19. Enter 28 mm as the extrusion distance.
20. Select **Join** as the operation to combine the cylindrical support with the base plate.
21. Press Enter to create the central cylindrical support.

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
49. <img width="562" height="513" alt="Screenshot 2026-11-11 204618" src="https://github.com/user-attachments/assets/bd61a308-dd2e-48d6-a067-b7a17841ffd7" />

50. Click **Finish Sketch**.
51. <img width="436" height="421" alt="Screenshot 2026-11-11 210017" src="https://github.com/user-attachments/assets/c63c83f3-d316-489b-ac9f-b52a97bb7853" />

52. Select **Extrude**, choose the required profile and select **Cut** as the operation.
53. <img width="460" height="617" alt="Screenshot 2026-11-11 212828" src="https://github.com/user-attachments/assets/92d1a2ca-f1c2-43c7-904d-abaa542a31f9" />

54. Apply the cut according to the hidden-line representation in the drawing.

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

