# Mouse skull top

We sometimes have to attach printed structures to the top of the mouse skull. 
To do so precisely, we will get the width, length and height of points on the top of the skull. 

## Procedure

1. Place a skull under the stereotaxic frame.
2. Level bregma and lambda.
3. Create a 3D coordinate grid. 
  * The spacing in the x- and y-axis is 0.2 mm. 
  * The grid extends laterally until the end of the top of the skull. 
  * Posterior, it ends at the end of the cerebellum
  * Anterior, it ends ...
  * Save the coordinates in a text file in `Surgery_procdures/skull/top3d.txt`. 3 columns for x,y,z. 0,0,0 is bregma.

4. We can also create a series of points that follows the edge of the top of the skull.
  * Approximately 0.2 mm spacing between points.
  * Save the coordinates in a text file in `Surgery_procdures/skull/edges3d.txt`. 3 columns for x,y,z. 0,0,0 is bregma.
  
