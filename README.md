# EX.No.-2.2 CREATE A 3D SOLID MODEL FROM ISOMETRIC DRAWING
## Date :13.10.26

## AIM: 

To create a 3Dmodel from the given isometric drawing using fusion 360 tool. 

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload
____________________________________________________________________________________________________________________________________________________________________________
PROCEDURE:

1.Initially, open Autodesk Fusion 360 and create a new design. Select the Create Sketch option from the toolbar and choose the Top (XY) Plane as the working plane.



<img width="543" height="298" alt="Screenshot 2026-11-15 212519" src="https://github.com/user-attachments/assets/1513709e-a9da-4361-bef4-cfd4d78bf899" />



2.Select the Center Rectangle tool and draw a rectangle at the origin. Set the required dimensions as 56 mm × 18 mm. Make sure that the rectangle is properly positioned on the sketch plane.


<img width="343" height="261" alt="Screenshot 2026-11-13 205442" src="https://github.com/user-attachments/assets/344306f2-d72d-45b9-a79c-3edae9f715db" />


3.Choose the Center Point Arc tool and draw the required curved portion with a radius of 18 mm. Next, select the Center Point Circle tool and create a circle with a diameter of 16 mm at the specified position.



<img width="380" height="260" alt="Screenshot 2026-11-13 205240" src="https://github.com/user-attachments/assets/a9ac1542-9203-4c00-8542-6ef68eea767b" />



4.After completing the required profiles, check the dimensions and select Finish Sketch. Select the completed sketch and use the Extrude command from the Solid toolbar.
  Enter an extrusion distance of 8 mm and confirm the operation to form the base solid.


5.Select the Mirror option from the Sketch toolbar. Choose the first circle as the object and the vertical centre axis as the mirror line. This creates an identical circle    on the opposite side with equal spacing.


<img width="283" height="217" alt="Screenshot 2026-10-08 212119" src="https://github.com/user-attachments/assets/73c1f5f3-d48a-4736-bbdb-9f9b5abf0ebb" />




6.Choose Line and draw two straight lines that touch the top and the bottom of both R18 circles. Make them tangent to the circles so that the outline looks like a slot.

7.Now use the Trim option. Click the inner halves of the two R18 circles (the parts lying between the circle centres) and trim them away, so that only the outer arcs          remain. This is where the trim option is used. 



<img width="140" height="234" alt="Screenshot 2026-10-08 212657" src="https://github.com/user-attachments/assets/c1968022-313f-4376-bdaa-f2c7586a3c04" />



8.Click Finish Sketch. The base outline with two Ø16 holes is now complete.

9.Select the Extrude command and click the base profile (the area between the outer outline and the two holes). Enter the distance 8 mm and press Enter. This creates the      base plate. 

10.Select Extrude, click the rectangle, enter 32 mm, and press Enter. This forms the vertical block.


<img width="209" height="287" alt="Screenshot 2026-11-11 213604" src="https://github.com/user-attachments/assets/23805242-5c55-4a40-9af8-b7ccf0be6d4b" />



11.Create a new sketch on the YZ plane through the centre of the block. Choose Line and draw a right-angled triangle with a vertical side of 32 mm along the front face of      the block, and with its base lying along the top surface of the base plate. Take the base length of the triangle from the drawing. Click Finish Sketch. 

12.Inside the Ø30 circle, draw one more concentric circle of Ø20 mm. Click Finish Sketch. 


13.Select Extrude and click the arm profile together with the ring between Ø20 and Ø30. Enter 10 mm and set the direction downward from the top face so that the arm stays      level with the top of the block. Press Enter. The Ø20 hole stays open because it was left out of the selection. 

14.Finally, inspect the completed model using the Isometric View. Check the shape, dimensions and alignment of all the features. Save the completed 3D solid model using the    Save option in Fusion 360.


<img width="818" height="340" alt="Screenshot 2026-11-13 213358" src="https://github.com/user-attachments/assets/55bce000-752e-4bdc-ab79-636181509626" />




## RESULT: 

<img width="433" height="297" alt="Screenshot 2026-11-13 223921" src="https://github.com/user-attachments/assets/63e81bbb-d87b-4044-ae72-234a9a10311b" />




<img width="549" height="382" alt="Screenshot 2026-11-13 200034" src="https://github.com/user-attachments/assets/386f2f1d-a5b1-4d85-a9d9-07ddae01dc3c" />



____________________________________________________________________________________________________________________________________________________________________________
OUTPUT:


Thus, the 3D model is created from given isometric drawing.
