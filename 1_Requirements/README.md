# PROJECT-1
## Introduction:
An induction motor is an AC Electric motor in which the electric current in the rotor needed
to produce torque is obtained by electromagnetic induction from the magnetic field of the stator
winding.Induction motors are widely used in Industries.The torque-speed characteristic is required in order to predict behavior of induction machines in electrical motor drives and hence modelling of Induction motor is done to determine torque speed characteristics.

## About the project:
Induction motors are widely used in Industries.The torque-speed characteristic is required in order to predict behavior of induction machines in many applications and hence modelling of Induction motor is done to determine torque speed characteristics.For a given motor specification the model will display the torque and speed characteristics of the Induction motor.

## Requirements
# High Level Requirements
| Id          |  High Level Requirements  |    status  |
| :--        | :--          |   :--     |
| HLR1        | Modelling of 3- Phase Induction motor in Matlab Simulink   | Implemented |
| HLR2        |Finding the torque characteristics of the Induction Motor | Implemented |
| HLR3        |Finding the speed characteristics of the Induction Motor |  Implemented|


# Low Level Requirements
| Id          | Low Level Requirements for HLR1   |    status  |
| :--        | :--          |   :--     |
| LLR1.1     | Conversion of three phase volatges to d-q reference frame  | Implemented |
| LLR1.2      |Obtaining the flux linkages in d-q reference frame from the voltage and current in d-q reference frame | Implemented |
| LLR1.3      |Obtaining the current in d-q reference frame from the flux linkages in d-q reference frame | Implemented |



| Id          | Low Level Requirements for HLR2   |    status  |
| :--        | :--          |   :--     |
| LLR2.1        | Obtaining the torque from the current in the d-q reference frame  | Implemented |


| Id          | Low Level Requirements for HLR3   |    status  |
| :--        | :--          |   :--     |
| LLR3.1        |Obtaining the speed from the Torque   | Implemented |

## 5W's & 1H and S.W.O.T analysis is in the below table 
SWOT analysis
![SWOTANALYSISAMBD](https://user-images.githubusercontent.com/99065925/160078696-48e2d8bd-ec0c-42ad-a67b-06fdc2ffad97.PNG)
5W's & 1H
How-






## Test Plan and Output
# High Level Test Plan:
|Test Id|Description|Expected input|Expected output|Actual output|pass/fail|
|-------|-----------|--------------|---------------|-------------|---------|
|HLT1 | Induction motor model| parameters such as Rs(stator resistance),Rr(rotar resistance),Ls(stator Inductance),Lr(rotar Inductance),Lm(magnetizing Inductance),Jm(Inertia Constant)| Torque ,Speed|Torque,Speed |pass|
|HLT2 | torque characteristics of the Induction Motor|current in d-q reference frame | torque | torque|pass|
|HLT3 | speed characteristics of the Induction Motor |Torque ,Inertia constant,Load torque |electrical speed |electrical speed|pass|



# Low level Test plan:
|Test Id|Description|Expected input|Expected output|Actual output|pass/fail|
|-------|-----------|--------------|---------------|-------------|---------|
|LLT1 |  |  | | |pass|
|LLT2 |  | | | |pass|
|L | || ||pass|





