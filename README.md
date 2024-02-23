
**A planar neuromuscular controller to simulate compensation strategies in the sit-to-walk movement.**   

*Eline van der Kruk & Thomas Geijtenbeek*  

https://doi.org/10.1101/2023.11.24.568552

Standing up from a chair is a key daily life activity that is sensitive to functional limitations as we age and  therefore associated with falls, frailty, and institutional living. Predictive neuromusculoskeletal models can potentially shed light on the interconnectivity and interdependency of age-related changes in neuromuscular capacity, reinforcement schemes, sensory integration, and adaptation strategies during stand up. Most stand-up movements transfer directly into walking (sit-to-walk). The aim of this study was to develop and validate a neuromusculoskeletal model with reflex-based muscle control that enables simulation of the sit-to-walk movement under various conditions (seat height, foot placement). We developed a planar sit-to-walk musculoskeletal model (11 degrees-of-freedom, 20 muscles) and neuromuscular controller, consisting of a two-phase stand-up controller and a reflex-based gait controller. The stand-up controller contains generic neural pathways of delayed proprioceptive feedback from muscle length, force, velocity, and upper-body orientation (vestibular feedback) and includes both monosynaptic an antagonistic feedback pathways. The control parameters where optimized using a shooting-based optimization method.  Simulations were compared to recorded kinematics, ground reaction forces, and muscle activation. The simulated kinematics resemble the measured kinematics and muscle activations. The adaptation strategies, that resulted from alterations in seat height, are comparable to those observed in adults. The simulation framework and model are available and allow to study age-related compensation strategies, including reduced muscular capacity, reduced neural capacity, external perturbations, and altered movement objectives.   

**Normal Seat Condition**

https://github.com/BODIES-Lab-TU-Delft/Sit-to-walk-predictive-simulations/assets/18257841/94a10040-2fc6-4604-8d87-83dc06ff6eef

**Low Seat Condition**

https://github.com/BODIES-Lab-TU-Delft/Sit-to-walk-predictive-simulations/assets/18257841/5f2e721c-09bc-4daa-bc7e-6d507917fba3

**Asymmetric Foot Position**


https://github.com/BODIES-Lab-TU-Delft/Sit-to-walk-predictive-simulations/assets/18257841/341d5a52-2f8c-4dab-b598-5b6bf286e451

**Alternative simulations**
We have performed several simulations that were not included in the original manuscript. 

*Tilted Seat Condition*

https://github.com/BODIES-Lab-TU-Delft/Sit-to-walk-predictive-simulations/assets/18257841/a1cdc7e9-b389-440f-9bae-1c5d3cf56522

*lower foot stiffness*


https://github.com/BODIES-Lab-TU-Delft/Sit-to-walk-predictive-simulations/assets/18257841/e8545820-f5a6-4201-93ef-4416f8a0f059



The model has been tested in conditions with reduced muscular vasti strength and unloading of the knee joint, which is described in more detail at:
https://github.com/BODIES-Lab-TU-Delft/STW-case-study-unilateral-pain


https://github.com/BODIES-Lab-TU-Delft/Sit-to-walk-predictive-simulations/assets/18257841/1e8289a7-4b6d-4513-a3c6-1d175d47db3b





