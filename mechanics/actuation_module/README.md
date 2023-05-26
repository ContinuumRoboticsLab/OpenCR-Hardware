# OpenCR-Hardware Actuation Module


## Electronics Overview

WIP

## Mechanics Overview

WIP

### 3D Printed Parts

WIP


### Off-the-shelf Components

WIP


### Step-by-Step Instructions

WIP

## Bill of Materials for one Actuation Module

<img src="images/actuation_module.png" alt="catchy overview" width="400"/>


| Part Name                          | Quantity | Notes                                                                | File/Link                                                                                                   |  
|------------------------------------|----------|----------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|   
| ActuationUnit_MotorSide_Cube       | 1        | 3D printed part ([drawing](drawings/Motor_Frame.pdf))                | [STL file](stl_files/ActuationUnit_EncoderCouplingSide.stl)                                                 |
| Motor                              | 1        | T-Motor MN4004                                                       | [Link](https://store.tmotor.com/goods-438-Antigravity+MN4004+KV300+-+2PCSSET.html)                          |
| Gear_Motor                         | 1        | McMaster Carr (P/N 2662N313)                                         | [Link](https://www.mcmaster.com/2662N313/)                                                                  |
| Gear_Encoder                       | 1        | McMaster Carr (P/N 2662N321)                                         | [Link](https://www.mcmaster.com/2662N321/)                                                                  |
| ActuationUnit_EncoderCouplingSide  | 1        | 3D printed part ([drawing](drawings/Encoder_Frame.pdf))              | [STL file](stl_files/ActuationUnit_MotorSide_Cube.stl)                                                      |
| Ball Bearing                       | 2        | McMaster Carr (P/N 5972K910)                                         | [Link](https://www.mcmaster.com/5972K91/)                                                                   |
| Shaft_GearCoupling                 | 1        | 3D printed part ([drawing](drawings/Shaft_GearCoupling_Drawing.pdf)) | [STL file](stl_files/Shaft_GearCoupling.stl)                                                                |
| Shaft_MotorEncoder                 | 1        | 3D printed part ([drawing](Shaft_MotorEncoder_Drawing.pdf))          | [STL file](stl_files/Shaft_MotorEncoder.stl)                                                                |
| Screw M3x10                        | 2        | McMaster Carr (P/N 91290A115)                                        | [Link](https://www.mcmaster.com/91290A115/)                                                                 |
| Nut M3                             | 2        | McMaster Carr (P/N 90593A001)                                        | [Link](https://www.mcmaster.com/90593A001/)                                                                 |
| Encoder                            | 1        | Avago AEDM-5810                                                      | [Link](https://www.mouser.ca/ProductDetail/Broadcom-Avago/AEDM-5810-Z12?qs=nm95cbFn36yryX%2Fd2Onjlw%3D%3D ) |



## More Information

### Further Links

[OpenCR Project](http://opencontinuumrobotics.ca)
<br/>
[Back to Top of Page](README.md)
<br/>
[Electronic Overview](electronics/README.md)
<br/>
[Hardware Overview](mechanics/README.md)

### Authors

Authors are listed in alphabetic order.

- Puspita Triana Dewi
- Reinhard M. Grassmann


### License

BSD 3-Clause License

Copyright (c) 2023, Continuum Robotics Laboratory, University of Toronto


### BibTeX

This design is part of the [OpenCR Project](http://www.opencontinuumrobotics.ca/).
If you want to reference this design, you can use the following citation:

```bibtex
    @article{GrassmannBurgner-Kahrs_et_al_arXiv_2023,
        title       =   {Open Continuum Robotics – One Actuation Module to Create them All},
        author      =   {Grassmann, Reinhard M. and Shentu, Chengnan and Hamoda, Taqi and Triana Dewi, Puspita and Burgner-Kahrs, Jessica},
        journal     =   {arXiv preprint arXiv:2304.11850},
        year        =   {2023},
        doi         =   {10.48550/arXiv.2304.11850}
    }
```

### Trivia

LOTR stands for Lord of the Ring, in reference to the title of the paper. Yes, the movie.
