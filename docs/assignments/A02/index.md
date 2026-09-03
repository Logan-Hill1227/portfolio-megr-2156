# A2 – Truss Stress Analysis

## Objective
<img width="456" height="270" alt="image" src="https://github.com/user-attachments/assets/3e349138-143c-4511-940a-ab972c2133df" />
  

 For assignment 2, I was tasked with designing a truss with given loads and constraints.The truss is to be made out of A500 structural steel with identical cross sectional areas and for the pins to have identical geometry and cross-sectional values. After brainstorming I came up with the design below.


<img width="1640" height="2017" alt="IMG_0066" src="https://github.com/user-attachments/assets/a25b6f62-5c67-457b-8835-1936052177aa" />


## Analyze
Following this step, I used my knowledge of statics and begun calcultions of all external forces in order to find internal forces of the geometry.

<img width="1640" height="2016" alt="IMG_0067" src="https://github.com/user-attachments/assets/c5e4eed9-a2a1-4aa4-9499-396fda0d0589" />


Once I finalized my calcultions, I then used method of Joints and free-body diagrams to solve for my internal forces which is demonstrated below.

<img width="1640" height="2003" alt="IMG_0068" src="https://github.com/user-attachments/assets/2098f435-66b5-4232-8159-fdae27294e62" />




Finializing my calculations I was able to move on to the next step. This step included calculating the cross-sectional area for all members using a given safety factor of 3.5 and given yield strength. To do this, I first had to list all the knowns and unkowns to set up my symbolic calcultion to then spring forward my numerical equations. Once this was completed I was able to succesfully approximate the total weight of the truss.



<img width="1640" height="1991" alt="IMG_0069" src="https://github.com/user-attachments/assets/ef2d1fdd-bf7f-4c3c-b2ef-9366a2a63d24" />
<img width="1640" height="2005" alt="IMG_0070" src="https://github.com/user-attachments/assets/097f9f32-6cd3-4b37-9447-f9486de8c574" />





Next step of this assignment was to find the cross-sectional area of the pins connecting the truss together. In my case I have 5 pins that are needed. The given shear stregth was 170 ksi and a density of 0.278lb/in^3. We can assume the elements are in compression and therefore won't fail in buckling. Just like the above step listing the known and unknown qualities came first. After solving symbollically and numerically, I was then able to determine the combined weight of the pins which is represented in N. My calculations are recorded below.


<img width="1640" height="2115" alt="IMG_0071" src="https://github.com/user-attachments/assets/2f0cae07-c79a-48ab-bd6d-11947a041681" />



Once completing all the necessary calculations, I moved on to the CAD portion of this assignment. I decided to use Fusion for this as I am very familiar witht he software. Since Fusion does not have A500 Steel I decided to use regular steel as it and A500 share very similar if not the same core properties. In the image below I provided an example of one of the member beams. In this instance I decided to use a 18.55mm x 10.00mm square extruded out to 6m to construct a beam that will both provided suffiecnt area for holes for the pins, and as well to get the proper cross-sectional area in.


<img width="1807" height="903" alt="Screenshot 2026-09-02 234026" src="https://github.com/user-attachments/assets/9192de5a-57ba-4c72-be16-45d7cf41f99a" />




On each end of the beam I attatched two holes, each with a diameter of 6.02mm. This allows for the pins to slot in perfectly. Once I completed this step I created 6 more beams as my truss has 7 members.

Following this step I had to construct the pins for my truss. I used the dimensions of 6.02mm x 8.02mm for my pins, these dimensions allowed for my truss to be structurally sound and effiecent, all while ensuring identical cross-sectional geometry was implemented.
<img width="1547" height="1070" alt="Screenshot 2026-09-02 235135" src="https://github.com/user-attachments/assets/ae5b2255-60ba-47e8-a8e9-6a18e5dfd1a8" />
<img width="1877" height="963" alt="Screenshot 2026-09-02 235345" src="https://github.com/user-attachments/assets/8b55ffe7-8ba4-4076-8315-620c9f531004" />




Once this was all completed I had to compare the CAD calculations to my hand. As said since A500 was not available Steel has slighlty different values which could be one reason why my values were slightly off. But, my answers were only differnt by a few hundreths which makes my truss ensure that the safety factor, weight optimazation, and geometric constraints were satasfied while maintaining structural integrity and stability.

<img width="377" height="512" alt="Screenshot 2026-09-03 001830" src="https://github.com/user-attachments/assets/1f0e4539-c446-4294-b5bd-cc9231b6f9ed" />
<img width="377" height="510" alt="Screenshot 2026-09-03 002803" src="https://github.com/user-attachments/assets/147227af-0abf-4a9a-af46-5f5165b2e93e" />


## Decide
_Which geometry did you select, and why? This is your first open design choice in the course — defend it._
I chose the geometry of 3 triangles because from my prior knowledge I know triangles are the strongest and most structurally sound shapes there is. Also with 3 equillateral triangles it ensured identical angles and even matching forces which made caclulations a lot smoother.
## Communicate
Through out this process I was able to learn many new qualities and experince some hardship and challenges as well. One of the main lessons I learned was that it is very important o verify your work and assumptions. It sounds generic but it is essential to succesfully produicng a stable engineering design. In this project in specific, the truss calculations, CAD model, FBD's and other calculatopns all depended on the accuracy of the properties. So if an inaccuracy occured it would skew the whole process.

In total for this assignment I took about 13-14 hours. It was very time consuming with most of the time coming from research and the CAD modeling as well as verifying my calcultions. I started early which was a major key in this so I wouldn't rush through and make any uneccesary mistakes.

## Likelihood of Failure Modes in Truss Components

Part 1 – Truss Members
Each truss member is under either tension or compression and may fail due to the applied loading. For each member:

**1-Identify the expected failure mode (yielding, fracture, or buckling).**
For members, AE, BC, CE they are all in compression, which in result would make buckling the expected failure mode. WHile members AD, BE, DE are in tension having yielidng as the expected failure mode. CD is a zero-force member so in result no failure mode is expected.
**2-State whether the material is ductile or brittle.**
The material is brittle.
**3-Support your choice using stress comparisons and simple reasoning.**
For the members in compression, they are assumed to not fail under buckling. Meaning they are agaisnt compressive stress, also having the calculated stresses being below the alowable stress ensuring they are stable. For the members in tension, the calculated stressesa are below the ablowable amount, meanig they are against yielding stress.
**4-Propose a design modification that could reduce the likelihood of this failure.**
One modification I would propose would be to add additional diagnol support memebrs. This adds another load for the applied forces causing the load to be evenly distributed, reducing the possibility of overload.


## Part 2 – Pin Connections

**1-Identify the expected failure mode of the pin.**
For the pin, expected failure mode would be shear yielding. The connection is designed as only a single-shear connection this results in shear stress across one plane of the pin.
**2-Support your answer with data from credible, known sources.**
Using data from https://engineeringlibrary.org/reference/lug-analysis-air-force-stress-manual
The author explains that having a single-shear joint, increases the likelihood of shear yielding occuring due to the fact in their alculations with a single pin in place the risk of yielding and bending are more likely to occur.
**3-Propose a design modification to reduce the likelihood of this failure**
One modification to make would to be to increase the diameter of the pin which would then decrease the shear stress further below the allowed.

## CAD Files



