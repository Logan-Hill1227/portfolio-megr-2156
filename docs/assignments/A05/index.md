# A5 – [Topic]

## Objective
I was tasked with designing a bracket by using the concept design(below) to be able to hold a horizontal force that was applied symetrically by a strap outline which was given to me through a resource.  The bracket’s dimensions are designed with different fit classes. Each dimension of the T beam is part of the fit:

“a” intention for use where accuracy is not essential
“b” is about the closest fits that can be expected to run freely
“c” is where accurate location and minimum play is desired

Design using a safety factor of 4 and applied load in between 500 lbf < F < 800 lbf. Choose one of three metals, aluminum 6061 T6, Steel (ASTM A36), or Titanium (Ti-6Al-V4). Furthermore, state assumptions and approximations about the design in order to use fundamental strength of materials analysis. For example, use the proper stress analysis and deflection analysis where appropriate. Assume no failure due to direct shear stress. 

Note: If the bracket is designed symmetrically a lot of work would be cut.


<img width="418" height="300" alt="image" src="https://github.com/user-attachments/assets/4a470ae8-d880-4abc-a64a-a8e4d8348410" />




For this assignment I was tasked with the following objectives. 

-Conduct stress analysis to determine appropriate dimensions for structural features.

-Generate free body diagrams (FBDs) to visualize forces and constraints for each feature.

-Identify and document known and unknown variables, assumptions, and algebraic models for stress calculations.

-Perform stiffness analysis to establish minimum required dimensions based on deflection constraints.

-Compare stress and stiffness analyses to ensure structural integrity and compliance with given constraints.

-Create detailed multiview sketches illustrating dimensions derived from both stress and stiffness analyses.

-Reflect on and document key engineering lessons learned throughout the process.


## Analyze

# Feature A Stress & Stiffness

For feature A I treated it as a solid circular cantilever bean fixed at the base with Feature B. For this I chose ASTM-A36 steel whihc had stress yield of 36,000psi and a modulus(E) of 29,000,000. Below show the steps I took for both the stress, and stiffness analysis to find the minimum required diameter. I treated this material as linear, elastic, and isotropic assuming shear failure was non-governing.



<img width="1431" height="1937" alt="IMG_0080" src="https://github.com/user-attachments/assets/dd54c028-772c-4fd6-a38d-967148c8f249" />



Following this I found that the Stress diameter governed over the stiffness so I chose that value.

# Feature B Stress & Stiffness

Continuing, I designed Feature B. I carried over my values to this aswell and treated it as an axially loaded bar in vertical tension. In order to keep clean parameters I set w=diameter of A, and assumed B was acting as a straight bar in pure uniaxial tension.


<img width="1483" height="1007" alt="IMG_0081" src="https://github.com/user-attachments/assets/f028ba78-af74-440e-825f-bdeb570ef9b3" />



Once again, the tensile stress governed over the stifness. With this I was able to find the minimum thickness required which is shown above. 



# Feature C Stress & Stiffness


For Feature C I designed the bottom flange of the assembly. Here, I acted as this were a support beam with a load concntraited in the center with 800 lbf. As in Feature B I used the same given parameters except switching my length to 4. I kept the same cross-sectional width as the diameter from A. I assumed Feature C negleted shear as well. 


<img width="1435" height="1518" alt="IMG_0082" src="https://github.com/user-attachments/assets/899aa9e4-e935-4d3c-8776-d80fce3b929b" />



Here again Stress governed stiffness. This allowed me to find the minimum flange thickness.


# Feature D Stress & Stiffness 

<img width="1640" height="1522" alt="IMG_0083" src="https://github.com/user-attachments/assets/0df536b7-e740-4839-9c9d-506c836c6203" />


Here I designed Feature D. Since there is two faces that equally split the load I found it to be 400 lbf by simply doing P/2. I carried over my parameters but making the length 3.5. The work is shown above and I then again found stress to preceede over stiffness.


# Feature E




<img width="1640" height="1710" alt="IMG_0084" src="https://github.com/user-attachments/assets/a6647dc7-34d9-44b9-a45f-218e6833ed2d" />



Feature E was pretty simply, just like for D the load was split so it came out to 400 lbf again. My assumption was that it sitting flat against the support with forces transferring due to pure compression (bearing).


<img width="1640" height="1710" alt="IMG_0084" src="https://github.com/user-attachments/assets/140df039-d569-48d8-9d03-a73e48d53127" />




Here again I found the stress to be greater than stifness allowing me to easily choose the minimum thickness. 

## Decide
 I created a multiview for each design, they are both similar except the dimensions whihc are slighlty differetn which can be found in the work shown above. 


 <img width="1345" height="1743" alt="IMG_0079" src="https://github.com/user-attachments/assets/33bc7f63-8e6d-4e0b-ae94-5436a905fc61" />


## Lessons Learned

1-Governing Failure Mode analysis

Throughout this whole assignment stress trumped over the stiffness in every single feature.

In Feature A the diameter required through stress was 1.219 in while the diameter from stiffness was 0.7398 in. This is almost a 65% difference. THis highlights the importance of finding the governing factor. 

2-Error Propogation

For parts b,c,d,e I used my stress diameter from A. This in itself didn't cause any issues but if I were to make a change and ue the stiffness the minimum thicknesses would all rise. This would then create a thicker, more stable part which would balance out the thin modulus (z).


3-Assumption Sensitivity Analysis

One assumption I made was was the load distributon and negligble bending moments at Feature B. Since we assumed this was a cantilever beam, this showed the load was a Moment calculated by Force times length instead of pure tension. If bendning were taken into accountability, the thickness would be greater than what it was to prevent yield.


## Link & Fits analysis



<img width="1640" height="1679" alt="IMG_0085" src="https://github.com/user-attachments/assets/9993c1c0-f01e-44cc-84ee-ed72e8a1297b" />


For this analysis I used the same parameters as my above features except changing a few which are shown above. Following the analysis and calculations I found the stress area was the only one greater than the yield strength . Just for percation I rounded up to values of 1.3 in and .5 and 4.0 in. 


For feature A I chose the Close Running Fit coming from page 646-660 in the handbook. My reasoning for this is because of the precise location allowing for seamless motion under load. For my diameter from A I chose Class H8 for the link hole, and Class F7 tolerance.

In order to get these fits, precsion reaming is needed for the link hole as well turning for the pin. All coming from ANSI B4.1 1st table.

In shaft two for my diameter I slected FN 1 from pages 646-660 due to the small amount of force required to produce, while creating a trustable joint. 



In all I spent ambout 5.5-6.0 hours working on this assignment including calculations, writng, and researching. From this assignment I learned valubale insights into how the math goes into maching such as finding correct dimensions and why we should choose certain dimensions for certain features in order to create tolerances that allow stable functonal fits.


