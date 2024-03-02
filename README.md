# Neutron Star Modelling with Python
In this project, we explore the numerical modelling of a neutron star using two different approaches: the Classical Model and the Relativistic Model. We utilize the Runge-Kutta method of 4th order (RK4) to solve the Ordinary Differential Equations (ODEs) governing the hydrostatic equilibrium and the Tolman-Oppenheimer-Volkoff (TOV) equations.

## Problem Statement:
The primary objectives of this project are:

1. Generate mass and pressure profiles of a neutron star.
2. Utilize the RK4 numerical method to solve the ODEs for both Classical and Relativistic models.
3. Compare the results obtained from the Classical and Relativistic models.
## Key Components:
- Initial Number Density Calculation: We determine the initial number density of neutrons per unit volume at the center of the neutron star using the Newton-Raphson method.
- Energy Density Calculation: The energy density of the neutron star at a given pressure is calculated using the TOV equations.
- Pressure Gradient Calculation: We derive the pressure gradient equations for both Classical and Relativistic models to describe the equilibrium structure of the neutron star.
- Mass Gradient Calculation: The change in mass enclosed within a radius with respect to the change in radius at a given pressure is calculated.
- RK4 Solver: We implement the Runge-Kutta method of 4th order to solve the ODEs for pressure and mass gradients.
- Plotting: Visualizations are created to depict the mass and pressure profiles of the neutron star for both Classical and Relativistic models.
## Conclusion:
After conducting simulations using both models, it was observed that the Relativistic Model provided results within the expected range for the mass and radius of a neutron star. In contrast, the Classical Model yielded values that were significantly higher for mass and slightly higher for radius, indicating its inadequacy in accurately describing the properties of neutron stars.

## Future Directions:
Future enhancements to this project could involve exploring more advanced numerical methods or incorporating additional physical phenomena to improve the accuracy of the models. Additionally, comparisons with observational data from real neutron stars could provide further validation and insights into the models' effectiveness.

## References:
- Numerical Recipes: The Art of Scientific Computing
- Astrophysics: Neutron Stars and Pulsars by Prof. Charles Bailyn

For detailed implementation and code, please refer to the provided Python script.
