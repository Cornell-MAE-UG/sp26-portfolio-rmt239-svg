**ENGRD 2020 OLHW 5b: Portfolio Project - Rohan Tonmoy**

**Problem Statement + Objective (Find):**
- Design a feasible simple-lever nutcracker and determine its necessary dimensions in order to crack open a macadamia nut by hand.

**Constraints and Input Parameters (Given):**
- The average grip strength of an adult male can be assumed to be 50kg, which falls in the range of mean values for men aged 30-39 according to [(https://www.racmn.com/blog/get-a-grip-your-health-is-in-your-hands-really#:~:text=Men:%20Ages%2030%2D39:%20Average%20grip%20strength%20ranges,strength%20ranges%20from%2085%2D99%20lbs%20(39%2D45%20kg).].

- The average macadamia nut diameter is approximately 20 mm according to [(https://alohafarmshawaii.com/services/macadamia-nuts/#:~:text=A1%20%E2%80%93%20This%20is%20the%20largest,food%20service%2C%20and%20confectionary%20applications.)].

- The average load required to crack a macadamia nut is 222.18 kg (Schrauf et al. Do capuchin monkeys use weight to select hammer tools, Anim Cogn 11, 413–422 (2008).https://doi.org/10.1007/s10071-007-0131-2).


**Free Body Diagram of Nutcracker Design + Calculations:**

<img width="837" height="314" alt="Screenshot 2026-03-04 at 2 51 37 AM" src="https://github.com/user-attachments/assets/d6dc9455-e5d8-47dd-a33c-648ccfd6f967" />

  In order to solve for the dimensions of the nutcracker design, the very first assumption made was that the top handle (ABC) would symmetric to the bottom handle (ADE), and so both handles would have the same dimensions. Next, I modeled handle ABC with the following dimensions:
  Length l<sub>1</sub> represents the length from the pivot point A to the center of the macadamia nut holder (in line with point B).
  Length l<sub>2</sub> represents the lenghth from the pivot point A to the opposite end of the handle (in line with point C).
  Length L represents the total length of the handle, represented as l<sub>1</sub> + l<sub>2</sub>.
  Height h<sub>1</sub> represents the vertical distance between the center of the macadamia nut holder to point B
  Height h<sub>2</sub> represents the vertical distance between the horizontal line extended from pivot point A and point C.

  Also, the reaction force at point A was represented with a x-component force (A<sub>x</sub>) and a y-component force (A<sub>y</sub>). The upward pointing force at point B of 222.18 kg represents the normal force exerted from the macadamia nut on the handle, and the downward pointing force at point C of 50 kg represents the grip force applied from the hand using the nutcracker.

  The first calculation done was setting up an equation of the net moment about point A in handle ABC, from which a proportional relationship between L and l<sub>1</sub> was determined (L = 4.44 l<sub>1</sub>). Then, this relationship was applied to the similar triangles that can be formed from all the denoted dimensions in the free body diagram of handle ABC, as can be seen on the right of the image above.
  
  From the geometric relationship between these similar triangles, the equation L / l<sub>1</sub> = h<sub>2</sub> / h<sub>1</sub> can be determined. Substituting the value L = 4.44 l<sub>1</sub> from the previous net moment equation about point A, it can be determined that 4.44 h<sub>1</sub> = h<sub>2</sub>. Next, a value of h<sub>1</sub> = 3.0 cm was assigned, from which h<sub>2</sub> was then calculated to be 13.32 cm.
  
  Then, the length l<sub>1</sub> was assigned a value of 5.0 cm, from which L was calculated to be 22.2 cm from the previously attained equation L = 4.44 l<sub>1</sub>. Lastly, since both L and l<sub>1</sub> were already determined, the remaining length l<sub>2</sub> was determined from the equation L = l<sub>1</sub> + l<sub>2</sub>. This led to the result that l<sub>2</sub> = 17.2 cm.

  Thus, the final results for the dimensions were:
  **L = 22.2 cm
  l<sub>1</sub> = 5.0 cm
  l<sub>2</sub> = 17.2 cm
  h<sub>1</sub> = 3.0 cm
  h<sub>2</sub> = 13.32 cm**

**Discussion on Usability of Design:**
  This designed nutcracker should be usable, as the dimensions permit for the complete enclosing of a macadamia nut in the allocated macadamia nut holder. This restraint was ensured by setting the height h<sub>2</sub> to be greater than the 2.0 cm average diameter of a macadamia nut. The 1.0 cm difference between these two values would account for the vertical thickness of the handle between point B and the upper edge as seen from the free body diagram axes in the image above. Also, when these calculated dimensions are substitued back into the net moment equation about point A, the result is that the net moment about point A is 0, ensuring static equilibrium. Thus, the calculated dimensions in this simple macadamia nutcracker design should be usable.
