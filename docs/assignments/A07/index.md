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
 For my first design, it was my inital design for A5,6. For the mesh as above, I used the deafault fusion mesh with it listed at 0.30in going to 0.20in, 0.10in. Below are images of the first simulation. The total amount of elements are shown in each cooresponding image.



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

As in the first design the calculations are repeated using the found values:



To contunue to reach the 7% threshold, I ran my simulation again with a finer mesh. (Elements are shown on side bar).


<img width="1242" height="825" alt="Screenshot 2026-10-21 235517" src="https://github.com/user-attachments/assets/4e13a3ea-8916-4769-a8b4-378c5e4efa42" />
<img width="1027" height="813" alt="Screenshot 2026-10-21 235533" src="https://github.com/user-attachments/assets/c9fc718d-d9a6-4438-a75d-e1e3a5465832" />
<img width="1107" height="817" alt="Screenshot 2026-10-21 235542" src="https://github.com/user-attachments/assets/e53a0fcf-04e0-4863-86c5-119aee97b700" />


Following previous steps I calculated the results to see if I can get 3/3 values in the 7% range.


To conclude I ran one more precautionary, finer mesh to compare results.

<img width="1058" height="810" alt="Screenshot 2026-10-21 235850" src="https://github.com/user-attachments/assets/55d1381c-7f9d-4443-8112-2bb7c588a487" />
<img width="942" height="801" alt="Screenshot 2026-10-21 235901" src="https://github.com/user-attachments/assets/77c575a9-3a8d-4d04-996a-ecf9b4a9dda9" />
<img width="1017" height="832" alt="Screenshot 2026-10-21 235910" src="https://github.com/user-attachments/assets/76e320b7-2678-4e7c-b3f9-5d39db22670d" />

And again I computed results:




# Design 3

Following the above iterations, I made one final design change in hopes of improving the strength and stability even more. The change I chose was to increase the thickness of the sidewalls and top as they were very thin and would easiy collapse under too much pressure and were a major contributor of the stress. Changes can be seen below.

<img width="1335" height="782" alt="Screenshot 2026-10-22 001216" src="https://github.com/user-attachments/assets/77ea50a7-ee78-48c0-a826-c109f50d8524" />


Following this, just as in the above steps I did my preliminary simulation to get my base values for the intial mesh. 



<img width="1292" height="867" alt="Screenshot 2026-10-22 001528" src="https://github.com/user-attachments/assets/3a4e0af3-7cf1-4518-ab69-fa347e4c91f9" />
<img width="1307" height="853" alt="Screenshot 2026-10-22 001538" src="https://github.com/user-attachments/assets/4ff10ea0-872f-4bf4-904a-c027ec472e96" />
<img width="1377" height="857" alt="Screenshot 2026-10-22 001550" src="https://github.com/user-attachments/assets/a8bc0628-be0c-4eea-8169-3338fcbdfa0d" />


Using the values given by the simulation I calculated to see if I was within range:



Following these results I ran a finer mesh to see if this would improve results.


<img width="1233" height="836" alt="Screenshot 2026-10-22 002001" src="https://github.com/user-attachments/assets/91488207-c1c5-40e4-b426-48a9973dda7c" />
<img width="1327" height="927" alt="Screenshot 2026-10-22 002010" src="https://github.com/user-attachments/assets/faf9e8e7-f79e-4b82-a337-2cde3f4bce34" />
<img width="1363" height="885" alt="Screenshot 2026-10-22 002026" src="https://github.com/user-attachments/assets/d2f8b987-8259-4859-9938-10b70b023ac1" />

Again, I computed my resluts:


I ran a third, final mesh to see if I could optimize results.



<img width="1512" height="847" alt="Screenshot 2026-10-22 002300" src="https://github.com/user-attachments/assets/2faa8f5d-7065-4138-8423-a53b65432a39" />
<img width="1360" height="847" alt="Screenshot 2026-10-22 002312" src="https://github.com/user-attachments/assets/a27ee4e2-658e-403c-9173-38a0535cd506" />
<img width="1398" height="881" alt="Screenshot 2026-10-22 002322" src="https://github.com/user-attachments/assets/912e30b3-5105-4398-a33c-fa4840bb0fe1" />

With this being my third design, and third mesh ran these are my final results.



## Reflection

Throughout this whole assignment it really improved my engineering mindset in continous improvement. By using FEA to determine where members were the weakest and using the information computed to help make a decsion on where I could improve the structural design of my part to improve strength helps me tie all these processes together. I really appreciated this assignment as it provided me with much needed expereince and exposed me to new solutins and how to go about certain challenges I may encounter in the engineering world. In total for this project I spent right around 8 hours to complete all parts. 


## 2157 Only




## CAD File
https://a360.co/4BkJOiO
https://a360.co/47sxxee

