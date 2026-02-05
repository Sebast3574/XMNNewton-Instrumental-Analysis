# XMM-Newton Instrumental Analysis

This project was done by Sebastian Alvarez Mercado.

# Goal
This project will look into how the X-ray instrument (EPIC-pn) aboard the XMM-Newton sattelite transforms a physical photon spectrum into counts that we observe. It will also
investigate how this functionality affects scientific conclusions about what we observe. At the end of this project I want to be able to explain how a given spectrum is
shaped and distorted to make it observable and how this can limit what we can infer about the data.

To perform the project, I have downloaded .fits data files from the HEASARCH XMM-Newton archive that contain observations of Active Galactic Nuclei Mrk279. Those data files 
will not be uploaded on this github, as I am afraid of any issues in regards to copyright or anything else I am unaware of. I will give at the bottom of this README file a
notice of what data I used to still promote transparency in my project.

# Motivation
My reason for undertaking this project is to learn more about the sort of work performed at ESA. As a current (2026) master student in Astronomy and Astrophysics at the University
of Amsterdam I wish to learn more in-depth about the development of space equipment and satellites. Furthermore, I also wish to develop my programming skills as well as learn
more about the instrumental aspect in physics, as I find the current curriculum at the UvA lacking in that regard.

# Project Stages
To accomplish my goal, I will divide my project in five stages (Note that this is subject to change). 

## Stage 1: 
Understand the data contained in each fit file and verify that the data I am using is of the correct instrument. I will also plot basic count spectrum and aim to understand 
PPS products.

## Stage 2: 
Understand the Instrument response. I aim to plot the effective area vs energy and energy redistribution matrix of the instrument while trying to understand and explain what
they mean physically.

## Stage 3:
Spectral modelling. I will fit a power-law model to the Mrk279 data. I will also apply the RMF (Energy redistribution matrix) and ARF (effective area vs energy). Finally,
I will compare the intrinsic model to the folded (observed) model.

## Stage 4:
Investigating sensitivity and potential trade-offs to consider. I will vary the exposure time, binning and background and demonstrate how parameter uncertainty changes
given a variation in one of these variables or combined.

## Stage 5:
I will interpret the data analysis I have conducted and answer my research question. I will also reflect on my work and what potential improvememts I could have deployed for
a higher work quality. Finally, I will suggest potential future project ideas that I could undertake, should I have the time. Of course, Anyone is free to take inspiration
or use one of my ideas, although I'd be very surprised if someone was reading this github page.

# Data validation
I have taken data from the HEASARC archive. I browsed for data of Mrk279 observed using XMM-Newton. I have chosen the xmmmaster master log and public archive. From there,
I have taken the dataset with obsid: 0953011701 which was observed for 52.7ks on the 22th September of 2024. The data was made public on 27th march of 2025 and the principal
investigator was Norbert Schartel.
