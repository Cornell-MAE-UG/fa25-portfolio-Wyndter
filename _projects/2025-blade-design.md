---
layout: project
title: Wind Turbine Blade Design
description: Class Project with CAD
technologies: [Autodesk Fusion, Matlab]
image: /assets/images/cad-file-blade-design.png
---

Project Overview:
In my MAE 4272 class, titled "Fluids and Heat Transfer," we were tasked to design a CAD file of 6in long wind turbine blades to be later 3D-printed and tested in a physical wind tunnel. For this blade design project, we utilized principles of fluid mechanics, structural mechanics, and wind tunnel operation to design a wind turbine blade with the goal of optimizing power extraction at a specified design RPM for a given distribution of free stream wind velocities. We also developed an experimental protocol to evaluate the true performance of our design and compare our experimental results with the predicted results from our analytical model. 

Design Process:
We created equations to model the changing chord length, pitch and twist angles of the blade as we move radially outward from the nose of the blades in the center of the turbine. We did significant research into the usefulness of different airfoil cross-sections for what we wanted to achieve, and we ended up deciding to use the NACA 7412 airfoil for each cross section. We chose this airfoil because it had a great coefficient of lift at the angles of attack which designed the blades to rotate at, and overall it had a great ratio of lift to drag which would allow us to generate much more power.

Testing Summary:
During testing, we achieved an optimal operational rotation rate of 590 RPM and a maximum power extraction of 0.04W at that RPM for a free stream velocity of 5.97 m/s. At the maximum wind tunnel fan frequency of 20 Hz, our blade was able to produce 0.85W of power at a 12.2 m/s wind speed. Our design achieved a low  power extraction efficiency of 3%, likely due to the twist of our blade being oriented oppositely from the incoming wind, but the blade neither failed structurally nor exceeded the maximum operating conditions of the turbine’s torque break.
---
image: /assets/images/power-curves.png
---

My Contribution:
I worked on every part of this project with my three teammates. Primarily, I helped during the design process by finding all the possible equations we could use to optimize the chord lengths and pitch angles for power generation. I also did significant research into the optimal airfoils we could use for different possible gains, and pitched these airfoils to the rest of my group, so we could collectively decide on one method to base the equations off of. In addition, I formulated the experimental design process which we used to test the blades after they had been printed. Using these methods we achieved a power generation of 0.88W, which was higher than any other group had accomplished.


