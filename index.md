# Snow Simulation
Chang Yoon Park, Kelly Shen

### Summary
Our project focuses on simulating the physical behavior of materials using the Material Point Method (MPM), and rendering the results with volumetric rendering techniques. Various numerical experiments, including snow simulations, are performed to visualize the effectiveness of the method.

### Problem Description
In modern 3D animations, simulations of continuum models such as fluids, solids, and granular materials through methods that can handle wide-ranging properties are crucial to achieve realistic effects. Specialized solvers are often used to handle a single behavior, but are inaequate for materials like snow that have varying phases. The challenge we face is correctly implementing a numerical scheme that will handle fracture and large nonlinear behaviors. We implement a MPM framework to tackle such problems, and ray-trace the final results to obtain realistic looking animations. 

### Goals & Deliverables
We plan to deliver basic (but correctly implemented) snow simulation results, such as snowball smashing. We will create a high resolution animation of the snowball trajectory including while it is flying in air, when it smashes, and the pieces of snow breaking apart/falling. This involves a correctly implemented MPM framework as well as a functioning volumetric rendering setup.

We hope to deliver:
1. More materials, such as viscoelastic fluids. 
2. Camera movements / notion blur in animations. 
3. Experiments by tweaking the constitutive model of snow.

The results will be benchmarked by comparing the results to real-life videos.

### Schedule
_April 14_ 
- Complete explicit time stepping MPM framework.
- Render a static snowball with hypothetical data (setting up volumetric rendering system).

_April 21_
- Complete implicit time stepping MPM framework.
- Produce snowball smashing animations.

_April 28_
- Produce some more scenes, such as rigid-body interactions.
- Implement camera movement and more involved lighting effects.

_May 5_
- (If ahead of schedule) Produce other material models, such as viscoelastic fluids.
- Compile the presentation.

### Resources 

Snow simulation by Stomakhin et al:
https://disney-animation.s3.amazonaws.com/uploads/production/publication_asset/94/asset/SSCTS13_2.pdf 

Technical paper regarding the constitutive equation of snow:
https://disney-animation.s3.amazonaws.com/uploads/production/publication_asset/96/asset/siggraph2013_tech_report.pdf

POVRay Raytracer:
http://www.povray.org/

### Computing hardware
- Linux Desktop Machine / Macbooks for code development/debugging.
- AWS instance for animation rendering / high resolution numerical simulations.
