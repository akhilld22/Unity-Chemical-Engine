# Unity Chemical Engine
A VR Chemical Reaction & Experiments Simulation Application Developed by Unity3D

## Introduction
The chemical simulation system consists of 2 parts, the engine and a virtual chemical lab. The engine is based on simplified chemical reaction principle, which could analysis and simulate real-time chemical reactions within one reaction system. The lab is built with Unity3D, where user could conduct a virtual experiment like producing Oxygen with heated KMnO4 through HoloLens.

## Preview
Part of the reactions we support and the experient can be viewed from the [video](https://github.com/zrdumped/Unity-Chemical-Engine/releases/download/v1.0/demo.mp4). Some screenshots are as followed:
(Yes, we did miswrite a character in our project)
* Use a  Thermometer
<p align="center">
    <img src="https://github.com/zrdumped/Unity-Chemical-Engine/blob/master/ReadmeImage/2.png" alt="Sample"  width="575" height="384">
</p>
* Strike a Match
<p align="center">
    <img src="https://github.com/zrdumped/Unity-Chemical-Engine/blob/master/ReadmeImage/3.png" alt="Sample"  width="575" height="384">
</p>
* Fetch the substances with spoon and test tube
<p align="center">
    <img src="https://github.com/zrdumped/Unity-Chemical-Engine/blob/master/ReadmeImage/4.png" alt="Sample"  width="575" height="384">
</p>
* Prodce Oxygen (Implemented with Fluid)
<p align="center">
    <img src="https://github.com/zrdumped/Unity-Chemical-Engine/blob/master/ReadmeImage/5.png" alt="Sample"  width="683" height="384">
</p>
* Many other reactions
<p align="center">
    <img src="https://github.com/zrdumped/Unity-Chemical-Engine/blob/master/ReadmeImage/7.png" alt="Sample"  width="606" height="242">
</p>
* Burn the Lab
<p align="center">
    <img src="https://github.com/zrdumped/Unity-Chemical-Engine/blob/master/ReadmeImage/6.png" alt="Sample"  width="575" height="384">
</p>



## What can the engine do
This engine support multiple reactions and single experiment with detailed instructions. Besides, the engine has good scalability because all the reactants and reactions are configured in an xml file. All the reacting information (quantity, reactant name, reactions, etc.) will be displayed. 

### Reactions
1. Fe + HCl -> FeCl2 + O2 -> FeCl3 
  The color of the solution will change in accordance to the react process. The Fe in the liquid will dissolve as well. 
 
2. NO2 <-> N2O4
  The color of the system wiil change due to pressure of the system, which can be adjusted by the user.
<p align="center">
    <img src="https://github.com/zrdumped/Unity-Chemical-Engine/blob/master/ReadmeImage/1.png" alt="Sample"  width="575" height="384">
</p>

3. Explode
  It is based on 2 complicated organics and H2SO4.
 
### Experiment
We implement the experiment which we heat KMnO4 to create O2.

* `The details can be viewed clearly in the video`
