# Anveshak_IK_model
* This repository contains my attempt to implement Inverse Kinematics on a 3R arm in Simulink
* It contains the files, scripts and links I used to generate the model

## CAD_model
  * contains the CAD model which was imported into matlab
  
## simulink model
  * contains the simulink model used with IK implemented with Newton Rhapson method
  
## urdf_data
  * contains the urdf data generated from CAD model using https://github.com/syuntoku14/fusion2urdf.git
  * Though do note the urdf model generated is not configured to be used out of the box in matlab and requires addition of joint frame set correctly and specifying the path of the stl files in the visual blocks in MATLAB


  * stl files in: urdf_data > meshes > .stl files
  * urdf file is basically the .xacro file generated in: urdf_data > urdf > rover_arms_learn_1.xacro
  * .xacro file has almost same syntax as .urdf and with slight modification can be used
