# Construction_Ergonomic_Data_Library (CEL dataset)
This dataset is developed from CML (Construction Motion Data Library), which is a public and integrated motion dataset for on-site activity. In specific, we employed the constructed angle calculator (released on GitHub also) and the 20 joints system-based skeleton data from CML. The motion data storaged in the CML dataset contains over 4333 samples and 53 types of activities tightly related to construction operations, ensuring that the calculation result, i.e., this Construction Angle Data Library, is capable for the representation of major activities in construction from the perspective of body segments angle.
The CAL dataset is mainly developed for the automated ergonomic assessment under the REBA (Rapid Entire Body Assessment) framework by Sue Hignett in 2000 (DOI:10.1016/S0003-6870(99)00039-3). This dataset contains 17 submodules (angle/height difference in detail) of the 6 major assessment modules (body segment) in the original REBA framework.
The 6 major modules are: Trunk, Neck, Legs, Upper_arms, Lower_arms, and Wrists.
The 17 submodules under the 6 major modules are: Trunk_flexion_angle, Trunk_bending_angle, Neck_flexion_angle, Neck_bending_angle, Neck_twisting_angle, Height_difference_between_feet, Left_leg_flexion_angle, Right_leg_flexion_angle, Raising_gap_between_shoulders, Left_upper_arm_flexion_angle, Right_upper_arm_flexion_angle, Left_lower_arm_flexion_angle, Right_lower_arm_flexion_angle, Left_wrist_flexion_angle, Right_wrist_flexion_angle.
For the calculator, you can switch to our previous work released on GitHub (https://github.com/LIZR58/Angle_calculator_for_ergonomic_assessment)
In addition, we only share the calculation result by our developed angle calculator based on the public version of CML database, which contains skeleton data highly related to construction industries among the four fundamental categories of activities: Production Activities(12 types), Unsafe Activities(38 types), Awkward Activities(10 types), and Common Activities(13 types). The CML database can be download from the website below: https://figshare.com/articles/dataset/Construction_Motion_Data_Library_An_Integrated_Motion_Dataset_for_On-Site_Activity_Recognition/20480787/3. You can find out the folder "20_nodes" from the first zip "Construction_Related_Data" for use.
If any institution or individual is goint to use CEL database for commercial activity or research, please inform me by Email for permission first and properly add citation.
