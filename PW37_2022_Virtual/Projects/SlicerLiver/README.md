Back to [Projects List](../../README.md#ProjectsList)

# Slicer-Liver

## Key Investigators

- Rafael Palomar (Oslo Unviersity Hospital/NTNU, Norway)
- Gabriella d'Albenzio (Oslo University Hospital, Norway)
- Ruoyan Meng (NTNU, Norway)
- Ole Vegard Solberg (SINTEF, Norway)
- Geir Arne Tangen (SINTEF, Norway)
- Javier Pérez de Frutos (SINTEF, Norway)

# Project Description

This project will continue the development of the *Slicer-Liver* extension
that will be developed through the [ALive project](https://alive-research.no).
The objective of the Slicer-Liver extension is to provide researchers
with tools to perform liver analytics towards planning of liver interventions
(resections, ablations). At this point in the project we need to port early
prototypes of our resection planning algorithms into 3D Slicer.

![3D Bezier Surface Markup](screenshot.png)

[Early prototype of the resection planning module](https://youtu.be/7M3DULQp81k)

## Objectives

   - Liver resection planning:
   
      1. Integration of volumetric analysis for resections
      2. Improve the UI for managing resections
     
   - Computation of vascular territories:
   
      1. Calculation of vascular liver-segments based on multiple vascular systems (hepatic arterial/vein, portal vein) 
      2. Structuring of data for the liver module – implementing object hierarchy
      3. Storing and reloading of module data
      4. User-friendly GUI for liver module – optimize for clinical use.

## Approach and Plan

For this Project week we will build on the advances obtained in the las project
week. Some of the objectives are based on new functionality that has been tested
but not integrated yet, while some other objectives are refinement of
functionality previusly integrated in [Slicer-Liver
PW36](https://github.com/NA-MIC/ProjectWeek/tree/master/PW36_2022_Virtual/Projects/Slicer-Liver
 
## Illustrations

![3D Bezier Surface Markup](bezier_surface_markup.png)

![Resection initialization](resection_initialization.png)

![Resection planning](resection_planning.png)

## Progress and Next Steps

# Background and References
1. [Slicer-Liver PW36](https://github.com/NA-MIC/ProjectWeek/tree/master/PW36_2022_Virtual/Projects/Slicer-Liver
1. [Slicer-Liver PW35](https://github.com/NA-MIC/ProjectWeek/tree/master/PW35_2021_Virtual/Projects/Slicer-Liver
   "Slicer-Liver in the last ProjectWeek") (June 2021)
1. [NorMIT-Plan at NA-MIC project week](https://projectweek.na-mic.org/PW33_2020_GranCanaria/Projects/NorMIT-Plan/) (january 2020)
1. [NorMIT-Plan at NA-MIC project week](https://projectweek.na-mic.org/PW34_2020_Virtual/Projects/SlicerLiverAnalysis/) (December 2020)
1. Palomar, Rafael, et al. "A novel method for planning liver resections using deformable Bézier surfaces and distance maps." Computer Methods and Programs in Biomedicine 144 (2017): 135-45.
1. Palomar, Rafael, et al. "Surface reconstruction for planning and navigation of liver resections." Computerized Medical Imaging and Graphics 53 (2016): 30-42.
