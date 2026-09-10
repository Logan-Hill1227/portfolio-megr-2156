# A3 – [Topic]

## Objective
I was tasked with designing a bar where I had to determine the minimum geometry through parametric design while under direct tension. Following this I had to verify my calculations through Finite Element Analysis

## Analyze
In this assignment certain parameters were up to me to choose which are show below. I chose these numbers because I figuredit would keep calculations relatively simple allowing me to allocate more time to the CAD and FEA.



<img width="2529" height="1199" alt="IMG_7190" src="https://github.com/user-attachments/assets/8cea91e0-e2a0-435a-8dba-a830ddd96aff" />



Following this step I moved onto the CAD portion where I used the software Fusion 360. Once in Fusion I set my parameters as shown below. 



<img width="1753" height="777" alt="Screenshot 2026-09-10 002436" src="https://github.com/user-attachments/assets/9a664f09-6b09-4467-9324-82dd28d67387" />


After this I went ahead and drew up my cross sectional area, then I exx=truded it by using the length I found in my calculations.




<img width="2322" height="1467" alt="IMG_7191" src="https://github.com/user-attachments/assets/dc45b1b5-570d-4ce7-b09b-b573e5a41c9e" />

<img width="527" height="401" alt="Screenshot 2026-09-09 235558" src="https://github.com/user-attachments/assets/3b68a50f-84b4-42f5-a0ee-0399901e8e00" />
<img width="1818" height="977" alt="Screenshot 2026-09-10 003300" src="https://github.com/user-attachments/assets/b6492f70-9761-438b-82f7-9c62a0a8c722" />



In this instance I decided to use Aluminium 6061 as it had the closest values to the parameters given to us. Once I did this I started the FEA portion where I first chose the back face as the fixed geometry and set the 400 lbf force on the other face. Photos of my results and process are below. 

<img width="1676" height="667" alt="Screenshot 2026-09-10 004421" src="https://github.com/user-attachments/assets/2e58cda9-3faa-477b-87b9-b63f30e55cdf" />

<img width="1848" height="761" alt="Screenshot 2026-09-10 010127" src="https://github.com/user-attachments/assets/a0513f8d-a545-4413-8992-09e2dee1282d" />


Displacement



<img width="1762" height="797" alt="Screenshot 2026-09-10 010406" src="https://github.com/user-attachments/assets/f5d4fee5-1a33-417c-9f44-f9348ab93081" />

Von Mises

As shown in the displacement graph, the maximum deflection was 0.009 in which coorespons exactly to the given. Using the data from my Von Mises map I resulted in a maximum stress of 1.992 ksi and from here I caclulated my safety factor whihc proves my baris more then suffiecnt for such load.



<img width="3024" height="4032" alt="IMG_7193" src="https://github.com/user-attachments/assets/6fec4a46-2b81-47f2-866c-26d4aeefc12e" />

## Reflection
As shown above I compared my calculation from my hand  to fusions calculation and I resulted in a percent error of 0%. This was expected due to the similarities of the formulas and physical properties between fusion (aluminium 6061) and my own parameters. Had I have used a differing mesh my calculations propably wouln't have matched due to the simplicity of my own simulation wheer they were altered. In this case I would still however trust the CAD software as I am a human and humans are open to mistakes where the computer has precise formulas and knows the exact values as well.

## Pin Hole
 Following this assignment we were asked to imagine if a substantial pin hole were on the left side of this par. Using the given (Kt) for this hole in a flat bar in tension as well as our FEA's nominal stress from the hole we need to estimate peak stress and if it will pass the safety factor as well. The formula for the stress concentration factor of K would be K=1+q(kt-1). USing knowledge of the ductility of aluminum we can assume q=0. From this assumption and calculation we end up with identical peak stress and the Kt the same, meaning it would pass the safety factor.

## Lessons Learned 

Some lessons I learned includ how to do FEA in CAD. I have never done a test like this before so getting to use this software with real application was a great lesson in and of itself. One mistake I did make was at first having the load act on the top face of the bar which would have really skewed my results. All in all I spent roughly 4.5 hours from start to finish.

## 2157 Only

When changing parameters to see if the length will differ I assume thelength would get longer if each were increased. To check I switched the height and width to 0.75 in each, the load to 500 lbf and the modulus to 11x10^6. My orginal length was 56.25 inches and my new length is 111.37 which validates my prediction. 


## CAD File
https://a360.co/4xhI0Um

