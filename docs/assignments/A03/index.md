# A3 – Parametric and FEA

## OBJECTIVE

* Use axial deflection modeling to to design the dimensions

* Parametric design to determine a bars length

* Introduce us to FEA (Finite Element Analysis)

* Introduce us to linking dimensions to appropriate parameters in CAD

* Compare and contrast the different analysis

<img width="665" height="267" alt="Screenshot 2026-09-09 232327" src="https://github.com/user-attachments/assets/d192b710-e79b-475d-a774-60207b8d50e1" />


## 1. DESIGN


**Initial Design**

Assignment #3 is a Parametric and FEA circular beam design project. I was required to create a support that can withstand an applied direct load between 300 lbs and 500 lbs. The bar must be designed from Aluminum with a range of Youn's Modulus from (8.5 - 11.5) x 10^6 psi with a maximum axial deflection of the bar at .009 incheas. I used 1060 Alloy Aluminum and selected 400 lb force for my direct load, and 10x10^6 psi. I choose to just use a standard .5in diameter. The yield psi was 40000 psi.

<img width="1164" height="821" alt="IMG_0135" src="https://github.com/user-attachments/assets/d7873559-80c3-4f96-9f41-4cd9e075b56c" />


**CAD Design**

I then inputted the parameters in SolidWorks and created equations for Area and Length.

<img width="602" height="157" alt="Screenshot 2026-09-09 223540" src="https://github.com/user-attachments/assets/20d09f4d-da9b-4906-b72e-9885225ca1d9" />

I then started the design of the rod by creating a circle and linking the diameter to the global variable.

<img width="667" height="512" alt="Screenshot 2026-09-09 222913" src="https://github.com/user-attachments/assets/3bb8531e-8fc5-48e9-997e-9544b69d3001" />

I extruded the length and linked it to the global equation.

<img width="632" height="275" alt="Screenshot 2026-09-09 223002" src="https://github.com/user-attachments/assets/f7400398-450e-4aa5-b92d-052d3188eb0c" />

I then chose the material 1060 Alloy (Aluminum) below are the properties of the material.

<img width="587" height="307" alt="Screenshot 2026-09-09 223106" src="https://github.com/user-attachments/assets/cbf701bd-ade2-4898-8128-f22194f67e7a" />


## 2. SOLIDWORKS FEA

Below is the FEA design with the applied external force set to 400lbf on the opposite end from the fixture. I then turned the bar into a mesh and completed the following FEA Tests.


*Stress*

<img width="1436" height="540" alt="Screenshot 2026-09-09 225922" src="https://github.com/user-attachments/assets/d30cfb06-d2d9-4406-b984-146b234dfd96" />


*Strain*

<img width="1372" height="516" alt="Screenshot 2026-09-09 230058" src="https://github.com/user-attachments/assets/dacf5f84-0802-4fe1-a98d-d047daecaf69" />


*Displacement*

<img width="1347" height="502" alt="Screenshot 2026-09-09 230127" src="https://github.com/user-attachments/assets/b66d1e27-05b2-47c9-9b07-2f39a67ce392" />

## 3. DESIGN REFLECTION

All the tests have been completed, I checked to make sure the maximum stress was lower than the strength of aluminum and calculated the safety factor below. I then calculated the difference in deflection from the data gathered in my tets.

<img width="832" height="293" alt="IMG_0136" src="https://github.com/user-attachments/assets/1a4b017b-1678-4444-9834-547ee1471e31" />


## 4. LEARNING LESSONS

Through this project I learned about the in-depth capabilities of SolidWorks. I learned that through FEA testing we are able to observe stress, strain, and displacement on an object. This allows me to tests parts without actually having to create them and wasting material. This process is both economical and efficient. This assignment took me about 2 hours.

## 5. MODIFY DESIGN PARAMETERS



**CAD LINKS:**

[SOPH-DESIGN-A03-PART.SLDPRT](SOPH-DESIGN-A03-PART.SLDPRT)

