---
title: Introduction
teaching: 27
exercises: 6
duration: 0
summary: ""
questions: null
objectives: null
keypoints: null
is-break: false
ukrn_wb_rules: []
day: 1
order: 155000

---
> ## Workshop aims 
The aim of this workshop is to share the workflow and the analysis pipeline to for the fluorescence lifetime imaging data that I developed to measure the intensity-independent changes in fluorescence lifetimes of imaged objects. 

> ## About you
First, I would like to get an idea about your backgrownd. Please go to the *link* to answer whether you
::: hljs-left 
    work/plan to work with FLIM (yes/no)
    analyse/plan to analyse FLIM data series (yes/no)
    what software do you use for the analysis (please list)

> ## What is FLIM?
Fluorescence lifetime is the time between excitation and emission of a fluorescent molecule, and FLIM (fluorescence lifetime imaging) is the method that allows to measure it in each pixel of the image. Fluorescence lifetime is usually very short, in a range between 0.5 and 5 nanoseconds, and one of the common approach to measure it based on exciting you samples with ultra-high frequency laser pulses and measuring the exact time between the laser pulse and the emission of each photon. This is called Time-Correlated Single Photon Counting, or TCSPC.

> ## What parameters are measured in TCSPC FLIM?
Depending on the complexity of the model (that is, whether there is one or several fluorescence lifetime components that contribute to teh final measured value), FLIM data can report one or several fluorescence lifetimes, and (in case of multicomponent analysis) the relative fraction of each component