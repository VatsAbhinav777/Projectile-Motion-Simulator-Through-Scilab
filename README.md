# Projectile Motion Simulator GUI

## Project Description
A modern desktop GUI built in Scilab for interactive simulation and visualization of ideal projectile motion. The application computes critical kinematic parameters- Time of Flight, Maximum Height and Horizontal Range and plots high-resolution live trajectory paths based on customizable initial conditions.

## Software Requirements
* **Scilab**: Version 6.0.0 or higher (Tested on Scilab 2024.1.0 / Windows & Linux)
* Operating System: Windows 10/11, macOS, or Linux

## Toolboxes Used
* Standard Scilab Built-in Libraries (No external ATOMS toolboxes required)

## Steps to Run the Application
1. Open Scilab.
2. Navigate to the project folder containing `projectile_motion.sci`.
3. Load and execute the script in the Scilab console:
   ```scilab
   exec('projectile_motion.sci');
   
## GUI Features
* **Custom Input Controls:** Interactive entry for Initial Velocity ($m/s$) and Launch Angle ($degrees$) with contrast-optimized text styling.
* **Instant Trajectory Visualization:** Live 2D plot showing trajectory curves with peak apex and impact point markers.
* **Key Metric Highlights:** Instant output displays for Time of Flight ($s$), Max Height ($m$) and Horizontal Range ($m$).
* **Robust Input Handling:** In-app error handling catches non-numeric inputs or out-of-bound angles ($0^\circ < \theta < 90^\circ$).

## References
* Halliday, D., Resnick, R., & Walker, J. Fundamentals of Physics. Wiley.
