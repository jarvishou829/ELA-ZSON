# ELA-ZSON: Efficient Layout-Aware Zero-Shot Object Navigation Agent with Hierarchical Planning

<p align=“center”> 
<img src=".\teaser.png" width="600"> 
</p>

We introduce ELA-ZSON, an efficient layout-aware zero-shot object navigation (ZSON) approach designed for complex multi-room indoor environments.

## Real-world Experiments

Navigation examples

<img src=".\1.gif"> 
<img src=".\2.gif"> 
<img src=".\3.gif"> 

Obstacle avoidance examples

<img src=".\4.gif"> 

## Abstract

By planning hierarchically leveraging a global topology map with layout information and detailed scene representation memory, ELA-ZSON achieves both efficient and effective navigation. The process is managed by an LLM-powered agent, ensuring seamless operation from exploration to navigation, without the need for human interaction, complex rewards, or costly training. 

Our experimental results on the HM3D benchmark demonstrate a 16.7\% point improvement in navigation success rate and 12\% improvement in success rate weighted by path length compared to SOTA methods. Furthermore, we validate the robustness of our approach through real-world robotic deployment, showcasing its capability in practical scenarios.


The LLM agent takes user instructions as input and manages the optional action choices according to the prompts and data flow. Optional actions include exploring and recording the scene, constructing scene memory representation, planning, and executing navigation. Obstacles and error recognition together with iterative attempts are available.

<img src=".\method.png"> 
