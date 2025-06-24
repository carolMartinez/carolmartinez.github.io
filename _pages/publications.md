---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u> 
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


A complete list of my publications is available in [Google Scholar](https://scholar.google.com/citations?user=3XPQq7AAAAAJ&hl=en){:target="_blank"} and and [ORCID](https://orcid.org/0000-0003-3040-6119).


## Under Review
- Passive Delay Mitigation in On-Orbit Emulations: An Experimental Validation, March 2025
- Scaling Law Formulation for Emulating On-Orbit Operations in On-Ground Robot-Assisted Testing Facility, Feb. 2025
- Adhesive-based Soft Gripping System for Space Debris Capture, March 2025
- Curriculum-Based Reinforcement Learning for 6-DoF Pre-Grasp of Rotating Space Debris, March 2025

## Latest Accepted Publications
- [Enabling Intelligent Robotic Manipulation in Space](https://orbilu.uni.lu/bitstream/10993/64586/1/Enabling_Intelligent_Robotic_Manipulation_in_Space_Poster_ERF_2025_Stuttgart.pdf), ERF, Stuttgart, 2025

- [Towards Benchmarking Robotic Manipulation in Space](https://orbilu.uni.lu/handle/10993/62520), A. Orsula, A. Richard, M. Geist, M. Olivares-Mendez and C. Martinez, Conference on Robot Learning (CoRL) Workshop on Mastering Robot Manipulation in a World of Abundant Data (MRM-D), 2024

- [Grasp-O: A Generative system for object-centric 6-DoF grasping of unknown objects](https://kuldeepbrd1.github.io/projects/grasp-o/), Kuldeep R. Barad, Andrej Orsula, Antoine Richard, Jan Dentler, Miguel Olivares-Mendez, Carol Martinez, European Robotics Forum ERF24, Rimini, Italy, 2024

- [GraspLDM: Generative 6-DoF Grasp Synthesis using Latent Difussion Models](https://ieeexplore.ieee.org/document/10744565)
Kuldeep R. Barad, Andrej Orsula, Antoine Richard, Jan Dentler, Miguel Olivares-Mendez, Carol Martinez. IEEE Access, 2024

- [Leveraging Procedural Generation for Learning Autonomous Peg-in-Hole Assembly in Space](https://arxiv.org/abs/2405.01134), A. Orsula, M. Geist, M. Olivares-Mendez and C. Martinez, International Conference on Space Robotics iSpaRo, June 2024, Luxembourg 

- [Visual Servoing for Robotic On-Orbit Servicing: A Survey](https://arxiv.org/abs/2409.02324), Lina Maria Amaya-Mejia, Mohamed Ghita, Jan Dentler, Miguel Olivares-Mendez, Carol Martinez, International Conference on Space Robotics iSpaRo, June 2024, Luxembourg 

- [Impact Behaviour Simulation Model of the Hybrid-Compliant’s Passive Unit for Active Space Debris Removal](https://orbilu.uni.lu/bitstream/10993/64167/1/Impact_Behaviour_Analysis_of_a_Passive_Compliant_Unit_for_Active_Space_Debris_Removal_Final.pdf), Maxime Hubert Delisle, Xiao Li, Barıs C. Yalcın, Miguel Olivares-Mendez and Carol Martinez
IEEE 20th International Conference on Automation Science and Engineering CASE, August 2024, Bari, Italy

- [A Modular High-Fidelity Photorealistic Simulator of Orbital Scenarios: A Space Debris Removal Use Case ](https://ieeexplore.ieee.org/document/10687527), Xiao LI, Antoine Richard, Barıs¸ C. Yalcın, Maxime Hubert Delisle, Miguel Olivares-Mendez, and Carol Martinez, International Conference on Space Robotics iSpaRo, June 2024, Luxembourg 

- [Emulating On-Orbit Interactions Using Forward Dynamics Based Cartesian Motion ](https://arxiv.org/abs/2209.15406), Mohatashem Reyaz Makhdoomi, Vivek Muralidharan, Kuldeep R. Barad, Juan Sandoval, Miguel Olivares-Mendez, and Carol Martinez, Proceedings of the 2024 CEAS EuroGNC conference. Bristol, UK. June 2024. CEAS-GNC-2024-031.

- [Adaptive Control Scheme for Space Debris Capture in the Presence of Mass and Inertia Uncertainty](https://ieeexplore.ieee.org/document/10460573)
Olga-Orsalia Christidi-Loumpasefski, Bariş Can Yalçin, Maxime Hubert Delisle, Xiao Li, Miguel Olivares-Mendez and Carol Martinez, EEE Access, 2024

- [On-Ground Validation of Orbital GNC: Visual Navigation Assessment in Robotic Testbed Facility](https://link-springer-com.proxy.bnl.lu/article/10.1007/s42064-024-0198-4)
Vivek Muralidharan, Mohatashem R. Makhdoomi, Augustinas Zinys, Bronislovas Razgus, 
Marius Klimavicius, Miguel Olivares-Mendez, Carol Martinez, Astrodynamics, 2024

- [Lightweight Floating Platfomr for Ground-Based Emulation of On-Orbit Scenarios](https://ieeexplore.ieee.org/document/10237201)
Baris Yalcin, Carol Martinez, Sofia Coloma, Ernest Skrzypczyk, Miguel Olivares-Mendez, IEEE Access,2023 

- [Hybrid-Compliant System for Soft Capture of Uncooperative Space Debris](https://www.mdpi.com/2076-3417/13/13/7968#:~:text=3.-,Hybrid%2DCompliant%20System%20for%20a%20Soft%20Capture%20of%20Space%20Debris,contact%20time%20for%20the%20capture.)
Maxime Hybert Delisle, Olga-Orsalia Christidi-Loumpasefski, Baris Yalcin, Xiao Li, Miguel Olivares-Mendez, and Carol Martínez
Applied Science Special issue “Recent Advances in Space Debris”, 2023

- [Rendezvous in cislunar halo orbits: Hardware-in-the-loop simulation with coupled orbit and attitude dynamics](https://www.sciencedirect.com/science/article/pii/S0094576523003272)
Vivek Muralidharan, Mohatashem R. Makhdoomi, Kuldeep R. Barad, Lina M. Amaya-Mejia, Kathleen C. Howell, Carol Martinez Luna, and Miguel A. Olivares Mendez
Acta Astronautica, Elsevier, April 2023 

- [Enhancing Rover Teleoperation on the Moon with Proprioceptive Sensors and Machine Learning Techniques](https://ieeexplore-ieee-org.proxy.bnl.lu/document/9857576). Sofia Coloma, Carol Martinez, Baris Yalcin, Miguel Olivares-Mendez
International Conference on Intelligent Robots and Systems, Kyoto. IROS2022

- [Learning to Grasp on the Moon from 3D Octree Observations with Deep Reinforcement Learning](https://arxiv.org/abs/2208.00818). Andrej Orsula, Simon Bogh, Miguel Olivares-Mendez, Carol Martinez
International Conference on Intelligent Robots and Systems, Kyoto. IROS2022

- [Vison-Based Safety System for Barrierless Human-Robot Collaboration](https://arxiv.org/abs/2208.02010) Lina Maria Amaya-Mejia, Nicolas Duque-Suarez, Daniel Jaramillo-Ramirez, Carol Martinez
International Conference on Intelligent Robots and Systems, Kyoto. IROS2022

- [Hardware-in-the-loop Proximity Operations in Cislunar Space](https://orbilu.uni.lu/handle/10993/52141) Vivek Muralidharan, Mohatashem R. Makhdoomi, Kuldeep R. Barad, Lina M. Amaya-Mejia, Kathleen C. Howell, Carol Martinez Luna, and Miguel Angel Olivares Mendez, International Astronautical Congress, September 2022.

- [Autonomous control for satellite rendezvous in near-Earth orbits](https://ieeexplore-ieee-org.proxy.bnl.lu/document/9853882), Vivek Muralidharan, Carol Martinez Luna, Augustinas Zinys, Marius Klimavicius and Miguel Angel Olivares Mendez. IEEE International Conference on Control, Automation and Diagnosis, July 2022. 

- [ET-Class, an Energy Transfer-based Classification of Space Debris Removal Methods and Missions](https://www.frontiersin.org/articles/10.3389/frspt.2022.792944/full)
Baris Yalcin, Carol Martinez, Maxime Hubert, Miguel Olivares-Mendez. 
Frontiers in Space Technologies, section Space Debris, January 2022

<!---
- [Image Features for Quality Analysis of Thick Blood Smears Employed in Malaria Diagnosis](https://malariajournal.biomedcentral.com/articles/10.1186/s12936-022-04064-2)
Wendy Fong Amarís, Carol Martínez, Daniel Suárez Venegas, and Liliana Cortes
Malaria Journal, March 2022,  


- [SORA Methodology for Multi-UAS Airframe Inspections in an Airport](https://doi.org/10.3390/drones5040141), 
Carol Martinez, Pedro Sanchez, Abhishek Bera, Miguel Olivares-Mendez. 
Drones, November 2021


-  [Deep Learning for Safe Human-Robot Collaboration](https://link-springer-com.proxy.bnl.lu/chapter/10.1007/978-3-030-90033-5_26?pds=22620222214216914128346154340684)
Nicolás Duque Suárez, Lina María Amaya Mejía, Carol Martinez, Daniel Jaramillo-Ramirez
Advances in Automation and Robotics Research, Lecture Notes in Networks and Systems, November 2021 

- [Enhancing Lunar Reconnaissance Orbiter Images via Multi-frame Super Resolution for Future Robotic Space Missions](https://ieeexplore-ieee-org.proxy.bnl.lu/document/9488313)
Jose Delgado, Pedro Sanchez, Carol Martinez, Miguel Olivares-Mendez
IEEE Robotics and Automation Letters Submission RA-L, October 2021

- [Machine Learning for Surgical Time Prediction](https://www-sciencedirect-com.proxy.bnl.lu/science/article/pii/S0169260721002947)
Oscar Martinez, Carol Martínez, Carlos Parra, Saul Rugeles, Daniel Suárez
Computer Methods and Programs in Biomedicine, September 2021
--->