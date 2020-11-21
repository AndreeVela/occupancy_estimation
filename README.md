# Estimating Occupancy Levels in Enclosed Spaces Using Environmental Variables: A Fitness Gym andLiving Room as Evaluation Scenarios

This is a repository related to the publication:

-----

Vela, A.; Alvarado-Uribe, J.; Davila, M.; Hernandez-Gress, N.; Ceballos, H.G. Estimating Occupancy Levels in Enclosed Spaces Using Environmental Variables: A Fitness Gym and Living Room as Evaluation Scenarios. Sensors 2020, 20, 6579.

-----

[Abstract](https://www.mdpi.com/1424-8220/20/22/6579) | [Full Text](https://www.mdpi.com/1424-8220/20/22/6579/htm)

Please cite this paper as:
```
@article{ Vela_2020_occupancy, 
  title={Estimating Occupancy Levels in Enclosed Spaces Using Environmental Variables: A Fitness Gym and Living Room as Evaluation Scenarios}, 
  volume={20}, 
  DOI={10.3390/s20226579}, 
  number={22}, 
  journal={Sensors}, 
  author={Vela, Andree and Alvarado-Uribe, Joanna and Davila, Manuel and Hernandez-Gress, Neil and Ceballos, Hector G.}, 
  year={2020}, pages={6579}}
```

## Introduction

The understanding of occupancy patterns has been identified as a key contributor to achieve improvements in energy efficiency in buildings since occupancy information can benefit different systems, such as HVAC (Heating, Ventilation, and Air Conditioners), lighting, security, and emergency. This has meant that in the past decade, researchers have focused on improving the precision of occupancy estimation in enclosed spaces. Although several works have been done, one of the less addressed issues, regarding occupancy research, has been the availability of data for contrasting experimental results. Therefore, the main contributions of this work are: (1) the generation of two robust datasets gathered in enclosed spaces (a fitness gym and a living room) labeled with occupancy levels, and (2) the evaluation of three Machine Learning algorithms using different temporal resolutions. The results show that the prediction of 3–4 occupancy levels using the temperature, humidity, and pressure values provides an accuracy of at least 97%.

Dataset content:

- Original Measurements in a 1 s resolution for the Fitness Gym and the Living Room. 
- Train and test splits for each of the monitored spaces in the following resolutions: 10 s, 10 s avg, 30 s, 30 s avg, 1 min, 1 min avg, 5 min, 5 min avg.
- Datasets with extra features for feature selection.

Do not forget to cite the corresponding publication! Thank you!

**Keywords:** temperature, relative humidity, barometric pressure, occupancy estimation, environmental variables.
