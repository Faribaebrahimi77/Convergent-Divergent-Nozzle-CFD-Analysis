Convergent-Divergent-Nozzle-CFD-Analysis
 
Comprehensive CFD simulation of compressible flow through a convergent-divergent (C-D) nozzle to investigate flow characteristics, shock wave formation, and pressure distribution across various operating conditions.

<img width="651" height="169" alt="image" src="https://github.com/user-attachments/assets/bd9878d0-0237-40ed-ab59-c1cb896bcee4" />


# Nozzle Geometry Specifications

Inlet Height: 15.41 mm
Throat Height: 5.58 mm
Exit Height: 12.75 mm
Total Length: 27.91 mm
Throat Location: 6.01 mm from inlet
Convergent Angle: 30°
Divergent Angle: 15°
Area Ratio (Ae/At): 2.28

<img width="608" height="160" alt="image" src="https://github.com/user-attachments/assets/e923630f-9388-4a5d-be14-61e267532165" />
<img width="600" height="151" alt="image" src="https://github.com/user-attachments/assets/00012d3d-945a-4c64-b0d9-582244424e8b" />
<img width="601" height="147" alt="image" src="https://github.com/user-attachments/assets/6383cb89-ff46-4a4f-a32e-9cb4164447eb" />

# Flow Physics Investigation
Compressible Flow Phenomena

Subsonic Convergent Section: Acceleration and pressure drop
Sonic Throat Conditions: Choked flow at minimum area
Supersonic Divergent Section: Further acceleration or shock formation
Shock Wave Analysis: Normal/oblique shocks depending on back pressure

# Operating Conditions Study

Under-expanded Flow: Low back pressure, supersonic exit
Perfectly Expanded Flow: Design condition matching
Over-expanded Flow: High back pressure, shock in divergent section
Shock in Nozzle: Internal shock wave formation

#  Key Analysis Parameters
Flow Properties

 Mach Number Distribution: Subsonic to supersonic transition

 Pressure Ratio: Total to static pressure variations

 Temperature Distribution: Compressibility effects

 Density Changes: Compressible flow characteristics

 Velocity Profiles: Flow acceleration through nozzle

# Performance Metrics

 Mass Flow Rate: Choked flow calculations

 Discharge Coefficient: Actual vs. theoretical flow

 Thrust Coefficient: Propulsive performance

 Pressure Recovery: Diffuser performance (if applicable)

# CFD Methodology
Solver Configuration

Flow Type: Steady, compressible, inviscid/viscous
Working Fluid: Air (ideal gas)
Turbulence Model: k-ω SST for viscous cases
Boundary Conditions:

Inlet: Total pressure and temperature
Outlet: Static pressure (back pressure variation)
Walls: Adiabatic no-slip/slip conditions



# Numerical Setup

Mesh: Structured quad/hex mesh with throat refinement
Solver: Density-based compressible solver
Discretization: Second-order upwind schemes
Convergence: Residuals < 10^-6

# Expected Results
Flow Field Visualization

Mach Number Contours: Supersonic flow development
Pressure Distribution: Wall pressure measurements
Density Gradients: Shock wave identification
Streamline Patterns: Flow acceleration visualization
<img width="591" height="270" alt="image" src="https://github.com/user-attachments/assets/f825225b-a639-4437-9ccb-9418d7d8d8e0" />

Performance Analysis

Nozzle Efficiency: Actual vs. ideal performance
Back Pressure Effects: Operating map development
Shock Wave Characterization: Location and strength
Design Optimization: Geometry sensitivity analysis**
