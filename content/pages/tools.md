---
content_type: page
learning_resource_types:
- Tools
ocw_type: CourseSection
title: Tools
uid: 713b619d-ad80-8a4a-69c3-88a205f93170
---

Software
--------

The 2.672 lab uses the ME computer network system under Window NT. Computer software packages have been installed in the lab computers for data acquisition, data processing, and word processing. The following is a brief overview of these packages.

1.  **LabView**: There are several icons here: CHART, WAVEFORM and VBENCH. **CHART is the package we use the most**; it is a general data logging program and displays the data on the fly. You can select which segment of the data you want to store afterwards. WAVEFORM acquires data in the usual way but you cannot display the data until the whole set is taken. VBENCH is a data acquisition virtual bench, which provides simulated oscilloscope, signal generators etc.
2.  **MATLAB**: Data processing, data plotting, and numerical simulation software. It has built-in programs for solving differential equations, curve fitting, and signal analysis. Below, you can find scripts developed for various experiments in this course.
3.  **Microsoft Word**: Word processing software.
4.  **Microsoft Excel**: Spreadsheet software.
5.  **Microsoft PowerPoint**: Presentation software.
6.  **FTP**: There is an icon based file transfer program for porting files between the lab computer and the MIT server.

Supporting Files
----------------

The following MATLAB '.m' files may be useful to you as you massage the data you collect in the various experiments. If you develop other '.m' files that you think would be useful in this course, please send them to the course instructors.

fitplot.m ([M]({{< baseurl >}}/resources/fitplot))  
Fits n degree polynomial to input vectors xin, yin; fit coefficients in coeff.

getdata.m ([M]({{< baseurl >}}/resources/getdata))  
Utility to get the time and voltage trace from a data file.

powerfit.m ([M]({{< baseurl >}}/resources/powerfit))  
Least square fit of data using linear combination of powers.

pwrspect.m ([M]({{< baseurl >}}/resources/pwrspect))  
Analysis of power spectrum.

steam\_p.m ([M]({{< baseurl >}}/resources/steam_p))  
Saturation properties for H{{< sub "2" >}}O; output saturation pressure.

steam\_t.m ([M]({{< baseurl >}}/resources/steam_t))  
Saturation properties for H{{< sub "2" >}}O; output saturation temperature.

fig\_h.m ([M]({{< baseurl >}}/resources/fig_h))  
Utility to make MATLAB plots better for importing into reports.

H2Oprop.m ([M]({{< baseurl >}}/resources/h2oprop))  
Thermodynamic properties for water; general-purpose function

A brief guide to MATLAB as used in this course is provided: ([PDF]({{< baseurl >}}/resources/labmanual-1))