# GN-Procedural-Modelling
Tests &amp; Drafts for Procedural Geometry Node Modelling Add-ons in Blender 3.3.1

## Plant growth simulator in geometry nodes 

### Dependencies
bpy
rna_prop_ui,  PropertyPanel
bmesh

### Input

- Procedural model (Geometry Nodes model in Blender (3.3.1)),

> Active object with mapped instances. In this example, procedural bezier curves mapped on a mesh (likewise procedural bezier).

- Transformation scale based on 'Combine XYZ'

> Bezier transformation vectors splitted, otherwise provide vector (X, Y, Z)

### Output

Add-on to adjust variables (world-space linked properties and unlinked independent properties - Reftools)

> A direct link to light intensity (worldspace)
> A direct link to external object properties (scale)
> Several direct links to internal, unlinked properties ('Environmental variables')

#### Blender add-on for growth simulation based on given variables in a growth model
Simulation based on entirely procedural 3D-model, i.e., depends on geometry node model.

### In progress

A transfer of this system to other simulations 
(e.g. volumetric clouds, and particle systems) is possible. 

Currently, the add-on works for a given procedural model based on a bezier curve,
with a custom set of interlinked sub-geometries. Hence, this setup can be easily
transferred to other procedural models. 

### General

This addon generates an animation, start- and end-position of keyframes is adjustable
via pre-sets of 250 and 500 frames, with respective resolution of the resulting animation.


![Image](https://user-images.githubusercontent.com/114761519/236008286-747ae868-5698-423f-8e08-ae7084b8c712.png)


![Image](https://user-images.githubusercontent.com/114761519/236008857-3055740f-9e23-4ad9-ad46-d4349a49ef40.png)



