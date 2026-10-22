# A7 – [F.E.A on Bracket]

## Objectives
-Use Finite Element Analysis (FEA) to improve the bracket design from previous assignments.
-Ensure high stiffness, strength, and lightweight optimization through iterative design.
-Conduct multiple FEA simulations, refining geometry based on results.
-Perform static stress analysis, including constraints, loading, and meshing selection.
-Interpret data by identifying max stress, displacement, and safety factors.
-Optimize the design by modifying geometry to enhance performance.
-Document the entire process with images, calculations, and insights.

## Analyze
In this process, the initial step is to use the bracket design from the A5 and run FEA on it. Following this create a mesh upon the bracket, run test, identify stress, strain, displacment, and the safety factor.


<img width="958" height="483" alt="image" src="https://github.com/user-attachments/assets/9bfb6652-3cf7-461c-92c9-9806c7431dd2" />


I first started by doing my FEA using 3 different meshes on Fusion 360. I started with a mesh size of 0.30 in per unit and went to 0.20 in, then to 0.10 in per unit. I also added fixed geometry to the feature where the beam itself will hold the bracket. The images show below give a physical representation of the steps listed.

<img width="1642" height="807" alt="Screenshot 2026-10-21 230912" src="https://github.com/user-attachments/assets/e4ce43ca-347f-45a3-bf30-2bcbf17c5821" />





## Design Iterations

# Design 1
 For my first design, it was my inital design for A5,6. For the mesh as above, I used the deafault fusion mesh with it listed at 0.30in going to 0.20in, 0.10in. Below are images of the first simulation.



<img width="1840" height="902" alt="Screenshot 2026-10-21 231742" src="https://github.com/user-attachments/assets/35506e0c-26fe-41f7-bb12-27f208c322b9" />
<img width="1792" height="900" alt="Screenshot 2026-10-21 231817" src="https://github.com/user-attachments/assets/5faf993b-c468-4f82-991e-f1a6601fdc49" />
<img width="1752" height="817" alt="Screenshot 2026-10-21 231840" src="https://github.com/user-attachments/assets/a773f89f-8e35-4cdc-9639-e4c5ea1dab4d" />

With this simulation giving me my first values needed for calculation I will now perform them using the equation, Convergance = ((Old-New)/New)*100%

After calculating I see need to use a finer mesh which I will demonstrate below.

Using 0.20in per unit now here are the results of my simulation.
<img width="1877" height="970" alt="Screenshot 2026-10-21 233042" src="https://github.com/user-attachments/assets/4381bc18-a327-4947-bbeb-9964ed2bb334" />
<img width="1847" height="952" alt="Screenshot 2026-10-21 233101" src="https://github.com/user-attachments/assets/65670ea6-4dab-4f86-8999-78bac33bfe81" />
<img width="1897" height="947" alt="Screenshot 2026-10-21 233139" src="https://github.com/user-attachments/assets/3ef640cc-97fa-446f-9fd6-ea811b7e3b7d" />



## CAD File
https://a360.co/4BkJOiO

