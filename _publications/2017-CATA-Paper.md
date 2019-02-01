---
title: "Best Paper Award: Pipeline for Reconstruction and Visualization of Underwater Marine Archaeology Sites using Photogrammetry"
collection: publications
permalink: /publication/Pipeline-for-Reconstruction
excerpt: 'This paper is about generating photogrammetric reconstructions from video footage collected by an AUV.'
date: 2017-03-21
venue: 'International Conference on Computers and Their Applications (CATA)'
---
This paper presents a method for constructing 3D maps of marine archaeological sites using deployments of Autonomous Underwater Vehicles (AUV) equipped with sonar and cameras. The method requires multiple AUV missions in which the first mission directs the AUV to conduct a high altitude lawnmower scan over the area to create a course bathymetry map using sonar. Subsequent AUV missions then direct the AUV to make low altitude fly-overs just above the wreck with the goal of obtaining camera images from multiple viewpoints of the wreck to enable offboard 3D mapping via photogrammetric reconstruction. This approach uses a coarse map generated after the first mission to construct AUV paths that attempt to maximize information gain, i.e. maximize the number of viewpoints of the wreck within a time limit. Presented is a motion planner derived from Rapidly-Exploring Random Trees (RRT) that have sampling strategies modified for this problem. Specifically, the random node selection and new node generation are designed to consider the kinematics of an AUV and the information gain associated with each flyover. Simulation results demonstrate improvements of up to 152% when these sampling strategies are used. Experiment results, involving deployments for mapping two known wrecks located along the coast of Malta, validate the system’s ability to construct 3D maps and associated visualizations.

[Download paper here](http://JLupanow.github.io/files/CATA-Paper.pdf)

Recommended citation: S. von Fock, et al., "Pipeline for Reconstruction and Visualization of Underwater Marine Archaeology Sites using Photogrammetry," *International Conference on Computers and Their Applications (CATA)*, Mar 2017.
