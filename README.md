# Supplementary Data for Thesis on Lactose Fermentation Modeling

This repository contains supplementary data associated with the thesis on lactose fermentation modeling with *Streptococcus* (*strep*). The thesis focuses on improving the accuracy of fermentation models by incorporating cell proliferation dynamics into models, using the COPASI software [1].

---

For more information about the thesis and its findings, please contact the author.

Thank you for accessing and using this supplementary data for your research on lactose fermentation modeling!

## Repository Contents

The repository includes objective function values obtained from parameter estimation of different metabolic models at varying pH values. The data is provided in three files:

1. **`simple_no_constraints`**
   - **Description**: Contains objective function values from parameter estimation for a simplified metabolic model. This model has parameter estimation upper bounds set at $10^2$ and $10^4$, without any constraints on internal metabolites.


2. **`simple_with_constraints`**
   - **Description**: Contains objective function values from parameter estimation for a simplified metabolic model. This model includes parameter estimation upper bounds of $10^4$ and constraints on all internal metabolites with lower bounds of 0 mM and upper bounds of $10^2$, $10^3$, and $10^4$.


3. **`extended_with_constraints`**
   - **Description**: Contains objective function values from parameter estimation for an extended metabolic model. This model includes parameter estimation upper bounds of $10^4$ and constraints on all internal metabolites with lower bounds of 0 mM and upper bounds of $10^2$, $10^3$, and $10^4$.

## License

This data is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) License. You are free to use, share, and adapt this data for any purpose, including commercial use, as long as you provide appropriate credit to the original author. For more details, see [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).


---

[1] Hoops, Stefan, et al. "COPASI—a Complex Pathway Simulator." *Bioinformatics*, vol. 22, no. 24, 2006, pp. 3067-3074. Oxford University Press.
