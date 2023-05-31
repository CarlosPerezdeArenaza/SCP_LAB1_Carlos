# Simulation Study of Cochlear Implants Stimulation Protocols and Its Application to Surgical Planning
## Scientifical communication project Lab1: Code publication

Welcome to the repository for the bachelor's degree thesis titled "Simulation Study of Cochlear Implants Stimulation Protocols and Its Application to Surgical Planning.", that was performed by Hector Dejea i Velardo on 2015.
This readme file provides an overview of the project, its goals, and the resources available in this repository.

<a name="Introduction" />

## Introduction
Cochlear implants have revolutionized the field of auditory prosthetics by providing a solution for individuals with severe to profound hearing loss. These implantable devices bypass the damaged parts of the inner ear and stimulate the auditory nerve directly, allowing users to perceive sound. However, the optimal stimulation protocols for cochlear implants can vary among individuals, and determining the most effective parameters for each patient remains a challenge.


The goal of this thesis project is to conduct a comprehensive simulation study of different cochlear implant stimulation protocols. By using computational models and simulations, we aim to investigate the impact of various parameters, such as electrode placement, stimulation levels, and pulse characteristics, on the perception of sound in cochlear implant users. Furthermore, we will explore how these findings can be applied to improve surgical planning for cochlear implantation procedures.

![image](https://github.com/CarlosPerezdeArenaza/SCP_LAB1_Carlos/assets/132482596/8c12b328-103b-4ab2-a4d6-c2061df92f4b)
![image](https://github.com/CarlosPerezdeArenaza/SCP_LAB1_Carlos/assets/132482596/7668d2eb-0d22-475f-ba36-a49952e7c241)


## State of the art
The procedure followed to obtain the simulation and results on this work was:

**Design of the models of the cochlea from cadaverical samples:** Hector firstly modelled the chocleas from different cadaveric simples, since we are all different the structures of our choclea may be diverse, so he tried to obtain the máximum number of samples that he could get.




 **Mesh**: Once Hèctor obatined all the models he did the emsh of the different structures that form the cochlea and also he designed the boundary conditions to perform the simulations by using the finite element methodology.
 Here we have some of the equations that Hèctor used, in this case the Maxwell's equations.
 
 
![image](https://github.com/CarlosPerezdeArenaza/SCP_LAB1_Carlos/assets/132482596/8b405860-0356-4b1c-a858-5c95001f0cb9)

**Implementation of the nerves into the model**:Once we had his geometry properly defined he implemented 1000 nerves into his model that were the objects of his stimulation. This number of nerves were the bare mínimum to obtain reliable results on his simulations since there are more tan 30000 nerves on our chocleas he couldn’t modell all of them.

![image](https://github.com/CarlosPerezdeArenaza/SCP_LAB1_Carlos/assets/132482596/f523f4a6-e704-4b79-a056-7532d4624576)
![image](https://github.com/CarlosPerezdeArenaza/SCP_LAB1_Carlos/assets/132482596/06f9d53a-6dd3-4970-a3a0-390679cec509)



 
 
**Results**: For the last part of the Project he generated 3 different types of electrical stimulations and verified his work using other articles, and obtained a cocnlusion by the comparison of his results with the other studies, The conclusions that Hector came up with after his TFG were that his simulation produced great results with the monopolar stimuli but the other stimulation protocols didn’t produced the expected results in comparison with the results in phD tesis of Rami Saba.
His final conclusión was that his monopolar results were good enough to try to work on other projects by following hus protocol but also that he needed to find another approach to simulate correctly the bipolar and tripolar electrical stimulations.

## Code
The code that is published on this repository is the sample code that we can find on the home page of Github, since I couldn't have any access to the code used for performing the different simulations.

## License
This project is licensed under the CC-BY-NC or CC-BY-NC-SA also known as Creative Commons Attribution-NonCommercial-ShareAlike 4.0. Please review the license file for more details.


## References
![image](https://github.com/CarlosPerezdeArenaza/SCP_LAB1_Carlos/assets/132482596/175104f4-effa-4874-bf03-3ce559a21068)
![image](https://github.com/CarlosPerezdeArenaza/SCP_LAB1_Carlos/assets/132482596/07ade8d5-5f65-4a90-b9c4-c0e7f56570a4)
![image](https://github.com/CarlosPerezdeArenaza/SCP_LAB1_Carlos/assets/132482596/28c683fe-3a1d-422d-bfa3-05dc01e238c1)
![image](https://github.com/CarlosPerezdeArenaza/SCP_LAB1_Carlos/assets/132482596/c61ee69f-ab5c-4802-a9d8-52096bbf00bc)





## Contact
If you have any questions or inquiries regarding this project, please don't hesitate to contact me at carlos.perezdearenaza01@estudiant.upf.edu. I am more than happy to discuss any aspects of this research.

Thank you for your interest in this project.

Your support and engagement are greatly appreciated.

Best regards,

Carlos.







