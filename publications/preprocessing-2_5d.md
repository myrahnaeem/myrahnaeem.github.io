---
layout: single
title: "Preprocessing of 2.5D Facial Images from Stereo Camera"
permalink: /publications/preprocessing-2_5d/
---

<p style="text-align:center; margin-bottom: 30px;">
  <img src="/images/preprocessing-2_5d.png" alt="Preprocessing of 2.5D Facial Images" 
       style="max-width: 100%; border-radius: 10px; box-shadow: 0 2px 12px rgba(0,0,0,0.18);">
</p>

<p style="font-size: 15px; line-height: 1.6; margin-bottom: 4px;">
<strong>Authors:</strong> Myrah Naeem, (add co-authors here if needed)
</p>

<p style="font-size: 15px; line-height: 1.6; margin-bottom: 20px;">
<strong>Affiliation:</strong> Sejong University / Kyung Hee University
</p>

<hr style="margin-top: 25px; margin-bottom: 25px;">

## Short Overview

This work focuses on improving the quality of 2.5D facial images captured from a stereo camera
for downstream face recognition tasks. The preprocessing pipeline includes median filtering,
Laplacian smoothing, hole filling, cropping, and geometric alignment of point clouds. These
operations remove spikes, reduce noise, smooth surface irregularities, fill missing data, and
produce consistent 2.5D facial mesh maps suitable for curvature-based 3D facial feature
extraction.

<p style="margin-top:15px;">
<a href="https://myrahnaeem.github.io/files/Preprocessing_of_2.5D_facial_images_from_stereo_camera.pdf" 
   style="font-size: 16px; font-weight: bold; color:#0077b6;">
📄 Download Full Paper
</a>
</p>

<hr style="margin-top: 30px; margin-bottom: 30px;">

## Abstract

This paper presents a preprocessing pipeline for 2.5D facial images acquired using a stereo camera.
The goal is to enhance mesh quality and prepare surface data for 3D facial recognition. The
pipeline applies median filtering to eliminate noise, Laplacian smoothing to remove spikes and
surface irregularities, and hole filling to address missing depth information. Additionally,
cropping and facial alignment techniques are applied to isolate the face region and normalize its
orientation. The resulting 2.5D facial meshes exhibit improved surface consistency and structural
accuracy, enabling reliable curvature-based analysis in 3D face recognition applications.
