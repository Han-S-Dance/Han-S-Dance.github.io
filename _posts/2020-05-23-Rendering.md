---
layout: page
title: "Renderman Beauty Sponge"
excerpt: "Using RenderMan and its associated API to model and render a scene containing a beauty sponge."
image: 
    path: /Images/BB2.png
    thumbnail: /Images/BB2.png
date: 2020-05-23 20:17:38 +0100
categories: CATEGORY-1 CATEGORY-2
---

Using RenderMan and its associated API to model and render a scene containing a beauty sponge.
 
This project was undertaken for the Simulation & Rendering unit of the MSc Computer Animation & Visual Effects Course at Bournemouth University. It was implemented directly in RIB, which was used to execute the Open Shading Language (OSL). The RIB file creates the scene and the beauty sponge from simple geometries, whilst the created OSL file applies displacement to the sponge, to create the final shape and the sponge texture. The OSL file incorporates the use of a parabola to displace the sponge into a teared shape and Perlin Noise to create the sponge effects and rips.  
 
The steps to create the beauty sponge are shown below.

![image-centre]({{ '/Images/Progress.png' | absolute_url }}){: .align-centre}

The final renders are shown below, variation between sponges is achieved by changing parameters in the respective OSL files.

![image-centre]({{ '/Images/BB1.png' | absolute_url }}){: .align-centre}

![image-centre]({{ '/Images/BB2.png' | absolute_url }}){: .align-centre} 