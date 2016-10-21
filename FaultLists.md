#Fault list in our Experiment.
[![experimental](http://badges.github.io/stability-badges/dist/experimental.svg)](http://github.com/badges/stability-badges)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badge/)    
 


##Fault types:

* ###Type1: wrong value. 
A wrong value in a Simulink constant block or a wrong threshold value in a Simulink block (e.g. control blocks).

* ###Type2: wrong function. 
A mistake in a Simulink function block, e.g. a function block chooses '>' instead of '>='.

* ###Type3: wrong connection. 
A wrong connection/link between two blocks, e.g. connect a signal A to input 2 instead of input 1 of the target block.

##Fault details:
(Notice:


- Simulink SID is a unique ID for each block in a Simulink model. Because, in   Simulink, several blocks in different subsystems or layers could have the same name, we use Simulink SID to differentiate different blocks in our experiment.  
- Simulink SID is not visible in Simulink window or Simulink block property.
- Simulink blocks with close SIDs **do not** mean their locations are physically close, especially in all our industrial subjects.
- All the faults are realistic, typical in industry practice, and seeded by an experienced engineer from our industry partner.)


| Model Name | Faulty Version | Fault Type | SID |
|------------|----------------|------------|-----|
| MA         | AF1            | Type1      | 42  |
| MA         | AF2            | Type1      | 26  |
| MA         | AF3            | Type2      | 44  |
| MA         | AF4            | Type1      | 391 |
| MA         | AF5            | Type2      | 381 |
| MA         | AF6            | Type1      | 540 |
| MA         | AF7            | Type1      | 579 |
| MA         | AF8            | Type2      | 508 |
| MA         | AF9            | Type1      | 426 |
| MA         | AF10           | Type2      | 448 |
| MA         | AF11           | Type3      | 452 |
| MA         | AF12           | Type1      | 179 |
| MA         | AF13           | Type2      | 165 |
| MA         | AF14           | Type1      | 450 |
| MA         | AF15           | Type1      | 350 |
| MA         | AF16           | Type1      | 243 |
| MA         | AF17           | Type1      | 207 |
| MA         | AF18           | Type2      | 241 |
| MA         | AF19           | Type2      | 245 |
| MA         | AF20           | Type2      | 168 |
| MZ         | AF1            | Type1      | 542 |
| MZ         | AF2            | Type1      |1069 |
| MZ         | AF3            | Type2      | 788 |
| MZ         | AF4            | Type2      | 785 |
| MZ         | AF5            | Type1      | 994 |
| MZ         | AF6            | Type1      | 996 |
| MZ         | AF7            | Type1      | 708 |
| MZ         | AF8            | Type2      | 1015|
| MZ         | AF9            | Type2      |1016 |
| MZ         | AF10           | Type1      | 749 |
| MZ         | AF11           | Type2      | 748 |
| MZ         | AF12           | Type2      | 759 |
| MZ         | AF13           | Type1      | 545 |
| MZ         | AF14           | Type2      | 643 |
| MZ         | AF15           | Type2      | 755 |
| MZ         | AF16           | Type1      | 703 |
| MZ         | AF17           | Type2      |1046 |
| MZ         | AF18           | Type1      | 572 |
| MZ         | AF19           | Type3      | 776 |
| MZ         | AF20           | Type2      | 995 |
| MGL        | AF1            | Type1      | 878 |
| MGL        | AF2            | Type2      | 877 |
| MGL        | AF3            | Type1      | 928 |
| MGL        | AF4            | Type3      | 571 |
| MGL        | AF5            | Type1      | 562 |
| MGL        | AF6            | Type3      | 938 |
| MGL        | AF7            | Type2      | 254 |
| MGL        | AF8            | Type1      | 256 |
| MGL        | AF9            | Type2      | 172 |
| MGL        | AF10           | Type2      | 171 |
| MGL        | AF11           | Type1      | 322 |
| MGL        | AF12           | Type1      | 330 |
| MGL        | AF13           | Type1      | 318 |
| MGL        | AF14           | Type1      | 104 |
| MGL        | AF15           | Type1      | 99  |
| MGL        | AF16           | Type1      | 944 |
| MGL        | AF17           | Type1      | 251 |
| MGL        | AF18           | Type2      | 173 |
| MGL        | AF19           | Type1      | 141 |
| MGL        | AF20           | Type1      | 321 |


Any further questions or discussions, please contact me or leave a msg under this project in github. 