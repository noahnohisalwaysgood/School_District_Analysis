# School_District_Analysis

## Overview of the school district analysis
The school board has notified Maria and her supervisor that the report shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Even though the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

# Distrit Summary DataFrame
![image](https://user-images.githubusercontent.com/105985796/176998395-c44da9e0-f908-4cd1-a340-13b2e099725f.png)
There are total 15 schools along with toal number of students 39170. 
  Average math score 78.9 
  Average reading 81.9
  Passing math rate 74.8%
  Passing reading rate 85.7%
  Overall passing rate 64.9%
 
# Thomas High School
![image](https://user-images.githubusercontent.com/105985796/176998620-1ab70c71-e692-4f33-ac5c-236b9a031c10.png)
Thomas High School's overall passing rate is above district's overall passing rate.

# School Summary 2 images
![image](https://user-images.githubusercontent.com/105985796/177023278-de911c1b-fb86-4700-aa2e-54e1e089447a.png)
![image](https://user-images.githubusercontent.com/105985796/177023288-16f67740-38db-4ca5-9193-4905c68e5ef8.png)

# Spending Summary
![image](https://user-images.githubusercontent.com/105985796/176999147-434d65b8-3885-40b5-a6a1-cf9405a8e6a3.png)

# School Size
![image](https://user-images.githubusercontent.com/105985796/176999194-95261e57-b7b9-42bc-b7d2-de8fd0f2197d.png)

# School Type
![image](https://user-images.githubusercontent.com/105985796/177088064-9d6808a7-6c5b-4423-bacb-650c3cc1bf19.png)

# Result
 # How is the district summary affected?
Original Data
![image](https://user-images.githubusercontent.com/105985796/177150306-94ca3cf5-68c1-43c4-ab18-8ec7784c4735.png)
Adjusted Data
![image](https://user-images.githubusercontent.com/105985796/177149874-681cd58a-7eca-46cc-abaa-5456d6c6000e.png)

It does not make siginificant change.

# How is the school summary affected?
Grade Data without 9th graders
![image](https://user-images.githubusercontent.com/105985796/177153176-b64fcc40-0b30-4724-9df8-8c9886e88920.png)
![image](https://user-images.githubusercontent.com/105985796/177153271-4b0d7c12-9a66-43b7-ade4-b240b5967850.png)
Grade Data with 9th graders
![image](https://user-images.githubusercontent.com/105985796/177153824-854bd001-d040-4721-9271-d1911fe45366.png)
![image](https://user-images.githubusercontent.com/105985796/177153893-07c6e01f-e46c-42ac-951c-beca3d26dae3.png)

It does not make significant change on averge math and reading scores. However, it makes significant change on passing math and reading rates as well as overall passing rate.
Passing math 93% to 66.9%
Passing reading 97% to 69.7%
Overall passing 90.6% to 65.1%

# Scores by School Spending
![image](https://user-images.githubusercontent.com/105985796/177155576-305ded5c-37b7-4f6d-880d-fae2bfc75239.png)

School spending has not significant impact on improving grades. Spending money does not equal to studnets' grades.

# Score by School Size
![image](https://user-images.githubusercontent.com/105985796/177205542-95687120-7854-4864-9b34-47fe92356330.png)

School size does not have significant impact on improving grades.

# School Type
![image](https://user-images.githubusercontent.com/105985796/177205820-1786a06f-5535-4839-99e6-51e3d9272637.png)
Charter has overwhelmingly better grades over District.


# Summary

The overall passing rate for Thomas High School decreases significantly from 91% to 65%.

Thomas High School's ranking dropped from 2nd to 8th in the district of 15 campuses.

Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School
