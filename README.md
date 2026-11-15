# Ex.No.-1.1-Design and Draft the given 2D Sketches in modelling software.
### Tharun Bala R
### 26018925
## AIM

To sketch the given drawing with dimensions using fusion 360 tool.

## REQUIREMENTS

  1. Autodesk fusion 360
  2. Windows 10
  3. 16 GB of RAM (integrated graphics recommend 2 GB or more)
  4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
  

 # **PROCEDURE**

## **STEP 1: Create a New Sketch and Construction Reference**

1. Click Create Sketch and select the XY Plane.
2. Select the Line tool (L) and enable Construction mode (X).
3. Draw a vertical construction centerline passing through the origin.
4. Draw horizontal construction lines to mark key height positions relative to the main center origin:
   - **Top Center:** Vertical offset of 65 mm above the center origin.
   - **Side Centers:** Vertical offset of 26 mm below the center origin.
   - **Bottom Center:** Vertical offset of 26 mm + 24 mm = 50 mm below the center origin.
   - Add horizontal construction dimensions for the side centers: 47 mm left and right of the vertical centerline.

## **STEP 2: Draw Central Geometry**

Switch back to normal lines (X to toggle off Construction).

### **Central Pitch Circles & Slots**

1. Draw two concentric reference circles from the main center: Ø40 mm and Ø66 mm.
2. Create the internal cutout feature with internal rounded slots of radius R6 mm arrayed centrally around the Ø40 mm / Ø66 mm reference geometry using Circular Pattern.

### **Tools shown in the Fusion 360 menu:**

- Line (L)
- Midpoint Line
- Rectangle
- Circle
- Arc
- Polygon
- Ellipse
- Slot
- Spline
- Conic Curve
- Point
- Text
- Mirror
- Circular Pattern
- Rectangular Pattern
- Project / Include

![image](https://user-images.githubusercontent.com/113594316/198206497-ca83d495-119b-45cd-b43d-8ca3ea7e9544.png)

# **STEP 3: Draw Top, Bottom, and Side Circular Hubs**

**Top Circles:**

Center at (0, 65):

- Inner hole: Ø20 mm
- Outer arc/circle: Ø32 mm (Radius 16 mm)

**Bottom Circles:**

Center at (0, -50):

- Inner hole: Ø10 mm
- Outer arc/circle: Ø20 mm (Radius 10 mm)

**Left & Right Side Circles:**

Centers at (-47, -26) and (47, -26):

- Inner holes: Ø7 mm (Radius 3.5 mm / labelled as R7 on inner circle)
- Outer arcs/circles: R10 mm (Ø20 mm)

# **STEP 4: Add Connecting Tangent Arcs**

**Upper Outer Arcs:**

1. Use the 3-Point Arc or Circle tool to draw arcs connecting the top outer circle (Ø32) to the central body region on both sides.
2. Apply a Tangent Constraint between each arc and the adjacent circles/arcs.
3. Dimension both upper connecting arcs to R64 mm.

**Lower Outer Arcs (Side to Bottom):**

1. Draw arcs connecting the side outer circles (R10) to the bottom outer circle (Ø20).
2. Apply Tangent Constraints to all intersections.
3. Dimension both lower connecting arcs to R20 mm.

**Mid Outer Arcs (Side to Central Body):**

Connect the side outer arcs (R10) upward towards the main body with arcs of R20 mm, maintaining Tangent relationships on both sides.

**Constraints shown in the Fusion 360 menu:**

- Horizontal/Vertical
- Coincident
- Tangent
- Equal
- Parallel
- Perpendicular
- Fix/UnFix
- MidPoint
- Concentric
- Collinear
- Symmetry
- Curvature
- Polygon
 
![image](https://user-images.githubusercontent.com/113594316/198206562-68463016-3f32-4a87-aa5b-7a17dd023b31.png)

 # **STEP 5: Trim and Finalize**

1. Select the Trim tool (T).
2. Trim away all internal overlapping circular arc segments so that only the outer boundary and specified inner profile holes remain.

**Tools shown in the Fusion 360 menu:**

- Fillet
- Chamfer
- Blend Curve
- Offset
- Trim (T)
- Extend
- Break
- Sketch Scale
- Move/Copy (M)
- Change Parameters

![image](https://user-images.githubusercontent.com/113594316/198206621-6348e8a3-4bbd-4a1f-96d3-db16fbf933d9.png)

 # **STEP 6: Finish Sketch**

After finishing the sketch, use the Finish Sketch option to finalize the sketch.

![image](https://user-images.githubusercontent.com/113594316/198206639-31c4bdb5-b13e-4106-bcf5-125c294aa03e.png)

 # **STEP 7: Create Drawing**

After finishing the sketch, switch to Drawing mode to plot the sketch in ISO standard.

**Drawing Settings:**

- Drawing Type: Automatic / Manual
- Contents: Select the required contents.
- Destination: Create New
- Base Document: Select the base document.
- Standard: ISO
- Units: mm
- Sheet Size: A3
- Width: 420 mm
- Height: 297 mm
- Orientation: Landscape / Portrait

Click OK to create the drawing.


![image](https://user-images.githubusercontent.com/113594316/198206697-2e3ead2b-7d1e-436e-bc36-aa2e73c1e78e.png)

 

![image](https://user-images.githubusercontent.com/113594316/198206721-8ad45462-2675-4be2-964f-621c8fc4490e.png)


## SKETCHS
![image](https://user-images.githubusercontent.com/113594316/198208087-87ed794e-5f1c-4583-82e0-f29699dfc305.png)

## OUTPUT
<img width="1506" height="1064" alt="{7643AACE-1E0F-4AD9-BA55-EC7ACEE029A3}" src="https://github.com/user-attachments/assets/0bdb04dc-79b0-44ac-932e-a9d4ec9f819d" />


## RESULT
Thus the given sketch is drawn and drafted using fusion 360 tool.
