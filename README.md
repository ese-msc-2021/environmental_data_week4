# environmental_data_week4
Here you will find resources and core information for week 4 remote sensing, Earth Observation (EO) data and image processing

## Learning outcomes:

On successful completion of this module, students will be able to:
1. Understand the principles of the major types of remote sensing (passive and active) - their strengths and limitations for various applications
2. Demonstrate competancy in executing standard image processing tools and techniques, to extract thematic information from EO data. So you will learn important image processing tools for contrast enhancement, algebraic operations, colour transformations & enhancements, pan-sharpening and principal components analysis (PCA)
3. Develop an understand of the basic principles of the spectral analysis of Earth materials, using multi- and hyper-spectral imagery, as well as of SAR imaging and its benefits
4. Become familar with all the major types and sources of EO data, and their uses

## Course content description:
This course is focused on the understanding of physical principles, maths concepts and data, rather than on coding (the latter you can experiment with and develop by yourselves). There are six lectures and related practical exercises. The practical exercises will use a few simple offline datasets for processing. To maximise the amount we can cover in this time, we will use two ready software tools: 
1. A flexible, powerful and transparent image processing tool called ERDAS 2013 (aka ERMapper). This is available on the Software Hub and runs on Windows only these days. If you are using your own laptop/desktop, you need to check you can access the College SoftwareHub directly from it.           
https://softwarehub.imperial.ac.uk/login                                             

Otherwise, if you are not attending in person, you will need to remotely access the College PC cluster             
https://www.imperial.ac.uk/admin-services/ict/self-service/connect-communicate/remote-access/remotely-access-my-college-computer/remote-desktop-access-for-students/

The optical image datasets for use in this part of the course are here:      

2. ESA SNAP Toolbox which was developed for processing of Copernicus Sentinel datasets - this should be downloaded and installed locally (Win & Mac versions available) 
Practical exercise instructions will appear in pdf form on the EDSML Teams channel.

The S1 SAR SLC image product for the last exercise can be downloaded here (its 4GB!) 


## Supplementary reading and useful resources:

There are plentiful and growing resources (and ready code) available for EO applications in many repositories:
* EO processing framework for ML in Python - extracting information from satellite imagery made easy!
htpps://eo-learn https://pypi.org/project/eo-learn 

* Tons of geospatial and EO recipes, tools and tutorials by colleagues Andrew Cutts & Alistair Graham, which developed from his groundbreaking podcast and blog called #scenefromabove a few years ago                
https://github.com/arcgeospatial/awesome-earthobservation-code 

* A bunch of resources set up for a 2019 conference to link EO and ML                       
https://github.com/sentinel-hub/eo-learn-workshop 

* Python tools for geospatial analysis              
https://github.com/earthlab/earth-analytics-python-env

* ESE Jupyter notebooks (by Raul Adraeinsen)                  
https://primer-computational-mathematics.github.io/book/d_geosciences/remote_sensing/intro.html

* Earth data science & analytics python course                   
https://www.earthdatascience.org/courses/earth-analytics-python

* All the raster data format descriptors and drivers you will ever need at GDAL                 
https://www.gdal.org 

An here is a shameless plug for our book on image processing which is in the College library and has been ripped online in various places
https://onlinelibrary.wiley.com/doi/book/10.1002/9781118687963

## Lecture schedule:
| Date                      | Lecture topic    | Instructor   | Moderators    |
|---------------------------|------------------|--------------|---------------|
| Mon 06/12/21 09.00-12.00  | Physical principles of remote sensing, sensors, resolution and raster data, data sources    | P Mason      | Emma & Sam    |
| Mon 06/12/21 14.00-17.00  | Application of point operations and contrast enhancement techniques    | P Mason      | Emma & Sam    |
| Tue 07/12/21 09.00-12.00  | Application of multi-band algebraic operations to produce spectral indices    | P Mason      | Emma & Sam    |
| Tue 07/12/21 14.00-17.00  | Principles and use of colour coordinate transformations & enhancements    | P Mason      | Emma & Sam    |
| Wed 08/12/21 09.00-12.00  | Principal Component Analysis (PCA) and a brief introduction to hyperspectral data processing    | P Mason      | Emma & Sam    |
| Thu 09/12/21 09.00-12.00  | Essentials of Synthetic Aperture Radar (SAR) imaging and (a brief) introduction to InSAR    | P Mason      | Emma & Sam    |
| Thu 09/12/21 14.00-17.00  | More on GEE      | Shuaib Rasheed            | 

## Assessment:

Assessment will be 100% coursework and open book
The exercise will be released and submitted via GitHub Classroom on Friday 
| Release date/time    | Due date/time         | Topic                 |
|----------------------|-----------------------|-----------------------|
| Fri 10/12/21 13.00   | Fri 10/12/21  17.00   | EO image processing   |
