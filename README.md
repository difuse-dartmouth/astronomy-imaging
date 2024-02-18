# Astronomy: Imaging Data Science Module 

## Contributors: Andy Bean ('23), Carolynn Harris (GR), Philip Choi (Professor of Physics and Astronomy, Pomona College), Professor Petra Bonfert-Taylor (PI), Professor Lorie Loeb (PI), Taylor Hickey ('23, PM), and Ben Levesque ('24, PM)  

![Title slide for ASTR 51 DIFUSE module.](repository-assets/DIFUSE_ASTR51.png)

This module was developed through the DIFUSE project at Dartmouth College and funded by the National Science Foundation award IUSE-1917002.


| <a href="https://github.com/difuse-dartmouth/public-module-template/archive/refs/heads/main.zip"><img src="https://github.com/difuse-dartmouth/.github/blob/main/profile/images/download-all.png" alt="Download the entire module" align="center" style="width: 4in;"></a>| <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="width=2in" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /><br></a>This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>. |
|---------|----------|


# Module Overview
## Module Objective 
Our objective was to redesign an existing lab assignment to introduce students to Python coding and data error. This would better prepare students to use Python and other coding languages in future astronomy or physics courses.


## Student Learning Objectives
1. Perform astrometric CCD measurements of Uranus and its moons from archival Slooh images using DS9 program (completed outside of module components shown here).
2. Determine the orbital parameters (period, orbital radius) of Uranus’ main moons from observations.
3. Estimate the mass of Uranus using these parameters and Newton’s law of gravity by executing basic python commands in a notebook environment
4. (New goal with this upgrade:) Measure uncertainty in orbital curve fitting and discuss sources of error.

## Module Description
This DIFUSE Module provides the second half of an existing lab assignment for Astronomy. In the first half, student will analyze images of Uranus and its two largest moons in the program DS9 (a collection of sample images is included in this repository). From this, they extract the Right Ascension (RA) and Declination (Dec) angles which describe the position of Uranus and its moons. Students then enter this into a spreadsheet and calculate the $\Delta$RA and $\Delta$Dec by subtracting the position of Uranus from the moon positions. The DIFUSE portion of the assignment begins when students use the spreadsheet format contained in the module materials so that the data can be imported into the Colab file. 

In the second half, students make a copy of the Colab code file and upload their data for analysis. The Colab walks them through steps to verify and investigate their data; most importantly, the Colab assists students in making a sinusoidal fit of the moons' motion to find the period and amplitude. They can then use these parameters to estimate the Mass of Uranus given the distance between the Earth and Uranus and Keplerian and Newtonian equations. Finally, the code investigates the effects of error by performing a Monte Carlo simulation of the distance distribution between the Earth and Uranus and allowing students to test the effects of adding further error.

### Data
Students generally produce their own datasets for use in this module. This can be done by taking new telescope images of Uranus and its Moons or by using an existing set of images from telescopes in Chile, and students then analyze these images in the astronomy program DS9. The existing images are contained in this repository, and a "test" set of data is also contained in this repository if instructors want to skip this step.

### Platform
The module is hosted on Google Colab. Instructors should download the Google Colab file to their own Google Drive and share this copy with students to make their own editable copies of. 

## Schedule and Links
Use this table to get an idea of the timeline of the module, what components are involved, and what documents are related to each component. This is the schedule intended for module deployment by the DIFUSE team, though instructors are welcome to modify the timeline to fit their course environment.

| Date             |  In/Out of Class | Assignment Description                     | Assignment Files (Linked to Repository Contents) |
|------------------|-----------------|--------------------------------------------------|--------------------------------------------------|
| Lab 1   | In class      | Image and Data Acquisition  | [Telescope Images](completed_module/data/Chile_canary_astron_2021/) • [Blank Data File](completed_module/data/Blank_Uranus_Data.csv/) • [Test Data File](completed_module/data/Test_VG_Uranus_Data.csv/) |
| Lab 2   | In class      | Data Analysis in Colab      | [Colab File](completed_module/components/assignment2/DIFUSE_Astro_Imaging_Colab_v_1_4.ipynb/) • [Colab Instructions](completed_module/components/assignment2/Astro-Imaging%20Colab%20Instructions.pdf/) |

## Course Information
This course was developed for an Astronomy course, <a href="https://catalog.pomona.edu/content.php?catoid=43&catoid=43&navoid=8669&filter%5Bitem_type%5D=3&filter%5Bonly_active%5D=1&filter%5B3%5D=1&filter%5Bcpage%5D=3#/usr/local/webroot/acalog-legacy/shared/htdocs_gateway/ajax/preview_course.php:~:text=ASTR051%20PO%20%2D%20Advanced%20Introductory%20Astronomy">ASTR 51</a>, at Pomona College which explores introductory concepts of Astronomy and includes laboratory assignments. The course is intended for prospective majors in the Astronomy or Physics Departments. AP Physics or equivalent College-Level Physics is a prequisite for this course, but incoming students may or may not have any experience in coding.

---

| <a href="https://github.com/difuse-dartmouth/public-module-template/archive/refs/heads/main.zip"><img src="https://github.com/difuse-dartmouth/.github/blob/main/profile/images/download-all.png" alt="Download the entire module" align="center" style="width: 4in;"></a>| <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="width=2in" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /><br></a>This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>. |
|---------|----------|

For instructors and interested parties, the history of this repository (with detailed commits), can be found [here](https://github.com/difuse-dartmouth/SOCY34_F21/commits/main/).
