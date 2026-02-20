# Structural-Analysis-Study---1D-vs-3D-Element-Visualization
This project documents my initial exploration of Finite Element Analysis (FEA) using Ansys, specifically focusing on the limitations of 1D line elements compared to 3D solid elements.

The Core Comparison: 1D vs 3D
The primary focus of these simulations was to observe how nodal distribution affects stress visualization.

1D Elements: While efficient, 1D elements lack nodes on the cross-section. This results in an inability to accurately display stress gradients at fixed supports.

3D Elements: By utilizing a 3D mesh, the increased number of nodes across the cross-section allows for a precise representation of direct stress, especially at boundary conditions where 1D models fall short.

Featured Simulations

1.Direct Stress Comparison: Highlighting how 3D models solve the "missing node" issue found in 1D formulations.

2.Central Bending: Testing the response of a beam under a centered load.

3.Directional Bending: Analyzing the beam's behavior when forces are applied through different vectors.
