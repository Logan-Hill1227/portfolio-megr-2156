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

Just like for the first mesh I will run the calculations with these results.


Although these answers are better, I will run a final finer mesh, to see if I can get with the 7%.

Here I use 0.10in per unit.

<img width="1855" height="901" alt="Screenshot 2026-10-21 233349" src="https://github.com/user-attachments/assets/a1c4a02b-8638-4678-bf42-0dd4905c33fa" />
<img width="1882" height="962" alt="Screenshot 2026-10-21 233400" src="https://github.com/user-attachments/assets/0ef090fc-bb26-40d7-9f51-da42697f8990" />
<img width="1872" height="987" alt="Screenshot 2026-10-21 233413" src="https://github.com/user-attachments/assets/2b3feb67-18ab-461f-9549-f14f5e8296a8" />



# Design 2

For my second design I decided to increase the thickness of Section B as I saw from my simulations that a majority of all stress was coming from this area. Below are the intial results. As in my first design all of the steps were repeated using same mesh values as well. They are shown below. 


<img width="762" height="428" alt="Screenshot 2026-10-21 233452" src="https://github.com/user-attachments/assets/91eb598e-0d90-472a-8aaf-3f34343b5d0a" />
Here I made the total thickness 0.50in to increase strength and stability.

<img width="1396" height="866" alt="Screenshot 2026-10-21 235107" src="https://github.com/user-attachments/assets/8a0fb98f-2c48-44a7-a1e4-0d097ece5cf7" />
<img width="1220" height="841" alt="Screenshot 2026-10-21 235126" src="https://github.com/user-attachments/assets/29ef343f-0e8f-4642-8982-d5fbf8760917" />
<img width="1307" height="837" alt="Screenshot 2026-10-21 235139" src="https://github.com/user-attachments/assets/d9d9d06b-6491-4ff5-aa7f-700dbf6cd560" />




















## CAD File
https://a360.co/4BkJOiO

