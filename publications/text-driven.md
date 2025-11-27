---
layout: single
title: "Text-Driven Generative Framework for Multimodal Visual and Haptic Texture Synthesis"
permalink: /publications/text-driven/
---

<!-- <p style="text-align:center; margin-bottom: 30px;">
  <img src="/images/text-driven.png" alt="Text-Driven Generative Framework Overview" 
       style="max-width: 100%; border-radius: 10px; box-shadow: 0 2px 12px rgba(0,0,0,0.18);">
</p> -->
<div style="width: 100%; display: flex; justify-content: center; margin-bottom: 30px;">
  <img src="/images/text-driven.png"
       alt="Text-Driven Generative Framework Overview"
       style="width: 100%; max-width: 1400px; height: auto; max-height: 900px; border-radius: 12px; box-shadow: 0 4px 18px rgba(0,0,0,0.2);">
</div>


<p style="font-size: 15px; line-height: 1.6; margin-bottom: 4px;">
<strong>Authors:</strong> Myrah Naeem

<p style="font-size: 15px; line-height: 1.6; margin-bottom: 20px;">
<strong>Affiliation:</strong> Kyung Hee University, Haptics and Virtual Reality Lab
</p>

<hr style="margin-top: 25px; margin-bottom: 25px;">

## Short Overview

This work proposes a text-to-haptic generative framework that creates both visual textures and
vibrotactile feedback directly from natural language descriptions. The pipeline combines a
text-to-image model (Stable Diffusion), a regression-based perceptual predictor (AttributeNet),
and an interpolation-based texture authoring algorithm to synthesize haptic signals aligned with
the generated visual textures.

<p style="margin-top:15px;">
<a href="https://myrahnaeem.github.io/files/Text_Driven_Generative_Framework_for_Multimodal_Visual_and_Haptic.pdf" 
   style="font-size: 16px; font-weight: bold; color:#0077b6;">
📄 Download Full Paper
</a>
</p>

<hr style="margin-top: 30px; margin-bottom: 30px;">

## Abstract

This paper presents a novel framework for generating both visual and haptic textures from
user-provided text descriptions. The proposed text-to-haptic pipeline combines generative AI
with data-driven tactile rendering to enable intuitive and perceptually accurate texture
synthesis. A text-to-image model (i.e., Stable Diffusion) generates high-quality visual
representations of textures from descriptive text prompts. These visual textures are processed
through a regression-based deep learning architecture, termed AttributeNet, which predicts
perceptual attributes, such as roughness and softness, mapping them onto continuous perceptual
scales. Finally, an interpolation-based texture authoring algorithm synthesizes vibrotactile
signals based on the predicted attributes, enabling us to render haptic feedback aligned with
the visual and textual input. To the best of our knowledge, this is the first complete framework
to generate visual and haptic texture signals based on text-based inputs. AttributeNet’s haptic
attribute predictions achieved improved accuracy over existing methods, and a user study further
validated the framework, with participants favoring its quality and usability.
