# Engineering Software

## 1. Overview

Engineering software supports computer-aided design (CAD), engineering calculations, data analysis, numerical modeling, and simulation. This section documents software relevant to mechanical engineering, HVAC systems, industrial utilities, equipment maintenance, and energy-efficiency analysis.

The tools listed below should be described according to actual experience. Software used for completed project work is distinguished from software being learned or considered for future applications.

## 2. Software and Applications

### 2.1 SolidWorks — Computer-Aided Design (CAD)

**Primary application:** 3D mechanical modeling, component design, assemblies, and engineering drawings.

Typical applications:
- Creating 3D models of mechanical components and equipment.
- Designing brackets, frames, shafts, supports, and mechanical assemblies.
- Preparing 2D engineering drawings with dimensions.
- Checking assembly fit and identifying potential interference.
- Supporting fabrication and prototype development.
- Developing conceptual layouts for mechanical and HVAC-related components.

**Example applications in this repository:**
- Mechanical structures and project components.
- Equipment mounting arrangements.
- Prototype design and fabrication documentation.

**Documentation:** https://www.solidworks.com/

### 2.2 Microsoft Excel — Engineering Calculations and Data Analysis

**Primary application:** Spreadsheet-based calculations, maintenance records, equipment-performance analysis, and reporting.

Typical applications:
- Organizing HVAC equipment specifications and operating data.
- Calculating temperature differences, energy consumption, and operating hours.
- Recording chiller, compressor, pump, and boiler performance.
- Comparing equipment readings before and after maintenance.
- Creating charts, tables, and maintenance dashboards.
- Tracking preventive-maintenance schedules and equipment history.

Useful Excel functions include:
- `SUM` and `AVERAGE` for basic calculations.
- `IF` for condition-based checks.
- `MIN` and `MAX` for operating-range reviews.
- `XLOOKUP` for retrieving equipment information.
- Charts and pivot tables for trend analysis.

**Example calculation — Energy consumption**

\[
E=P\times t
\]

Where:
- \(E\) = electrical energy consumed (kWh)
- \(P\) = electrical power (kW)
- \(t\) = operating time (hours)

For example, equipment operating at 5 kW for 8 hours consumes 40 kWh, assuming constant power.

**Documentation:** https://support.microsoft.com/excel

### 2.3 MATLAB — Numerical and Engineering Analysis

**Primary application:** Numerical calculations, mathematical modeling, data visualization, and engineering analysis.

Potential applications:
- Solving engineering equations and systems of equations.
- Analyzing temperature, pressure, airflow, and energy data.
- Plotting equipment operating trends.
- Evaluating mathematical models of mechanical systems.
- Performing numerical calculations for thermodynamics and heat transfer.
- Comparing analytical results with experimental measurements.

MATLAB should be listed as a completed-project tool only where it was actually used. Otherwise, describe it as a learning or planned analysis tool.

**Official resources:**
- MATLAB: https://www.mathworks.com/products/matlab.html
- MATLAB documentation: https://www.mathworks.com/help/matlab/

### 2.4 Python — Data Processing and Automation

**Primary application:** Data analysis, engineering calculations, visualization, and automation.

Useful libraries include:

| Library | Typical application |
|---|---|
| NumPy | Numerical calculations and array operations |
| pandas | Organizing and analyzing equipment data |
| Matplotlib | Creating engineering graphs |
| SciPy | Scientific and numerical computations |
| Jupyter | Interactive analysis and technical documentation |
| scikit-learn | Machine-learning experiments and predictive-maintenance research |

Potential HVAC applications:
- Processing equipment inspection records.
- Analyzing chiller and compressor operating trends.
- Plotting energy consumption and temperature variation.
- Identifying unusual measurements for further inspection.
- Developing basic maintenance-data analysis scripts.
- Exploring predictive-maintenance methods using historical sensor data.

**Official resources:**
- Python: https://www.python.org/
- Python tutorial: https://docs.python.org/3/tutorial/
- NumPy: https://numpy.org/doc/
- pandas: https://pandas.pydata.org/docs/
- Matplotlib: https://matplotlib.org/stable/
- SciPy: https://docs.scipy.org/doc/scipy/
- Jupyter: https://jupyter.org/
- scikit-learn: https://scikit-learn.org/stable/

### 2.5 ANSYS — Engineering Simulation

**Primary application:** Numerical simulation of physical systems, where the appropriate module, model, and boundary conditions are available.

Potential applications include:
- Finite element analysis (FEA) for structural behavior.
- Evaluating stress, deformation, and factor of safety.
- Computational fluid dynamics (CFD) for airflow and fluid-flow studies.
- Investigating heat transfer and temperature distribution.
- Comparing simulation results with analytical calculations or experimental measurements.

For simulation work, document the model geometry, material properties, loads, boundary conditions, mesh settings, solver settings, and results.

**Example reporting parameters:**
- Maximum von Mises stress (MPa).
- Maximum deformation (mm).
- Factor of safety, where applicable.
- Mesh quality and convergence checks.
- Assumptions and limitations of the model.

**Official resources:**
- ANSYS: https://www.ansys.com/
- ANSYS learning resources: https://www.ansys.com/academic/learning-resources

> **Important:** Include ANSYS in a completed-project workflow only when the simulation was actually performed. Do not present proposed or illustrative results as verified simulation outputs.

## 3. Engineering Workflow

A typical workflow may combine multiple tools:

1. **Define the problem:** Identify the equipment, engineering objective, operating conditions, and constraints.
2. **Collect data:** Record measurements, equipment specifications, and relevant operating history.
3. **Perform calculations:** Use hand calculations or Excel to establish baseline results.
4. **Create a model:** Use SolidWorks when mechanical CAD is required.
5. **Analyze the data:** Use Python or MATLAB where numerical processing or visualization is beneficial.
6. **Simulate, if required:** Use ANSYS only when the problem warrants simulation and the necessary modeling work is completed.
7. **Validate:** Compare results with engineering calculations, measured data, manufacturer specifications, or suitable references.
8. **Document:** Record assumptions, units, methods, results, and limitations.

Not every project requires every software package. Select tools according to the engineering problem.

## 4. Example Applications in HVAC and Industrial Utilities

| Engineering task | Suitable tool |
|---|---|
| Mechanical component design | SolidWorks |
| Equipment-data records and calculations | Excel |
| Energy-consumption analysis | Excel or Python |
| Temperature and pressure trend visualization | Excel, Python, or MATLAB |
| Numerical engineering calculations | Python or MATLAB |
| Structural stress and deformation analysis | ANSYS, when used |
| Airflow or heat-transfer simulation | ANSYS, when appropriate |
| Maintenance-data analysis | Excel or Python |
| Exploratory predictive-maintenance research | Python and scikit-learn |

These are recommended applications, not a claim that every task has already been completed.

## 5. Good Engineering Documentation Practices

For reproducible and reliable work:

- Use consistent SI units unless another unit system is required.
- Record assumptions and the source of equipment data.
- Keep raw measurements separate from calculated results.
- Include formulas and intermediate steps where practical.
- Label graphs with units, axes, and meaningful titles.
- Check calculations against independent methods when possible.
- Record software versions and important model settings.
- State uncertainties, limitations, and validation methods.
- Avoid publishing confidential employer information or proprietary drawings.

## 6. Future Development

Potential extensions for this repository include:

- Python scripts for HVAC engineering calculations.
- Excel templates for energy and maintenance analysis.
- SolidWorks models of mechanical components.
- MATLAB examples for heat-transfer and thermodynamic calculations.
- Verified ANSYS case studies with clearly documented assumptions.
- Data-analysis notebooks for HVAC performance and predictive-maintenance research.

Each example should include its objective, input data, methodology, results, and limitations.

## 7. References

- [SolidWorks](https://www.solidworks.com/)
- [Microsoft Excel Support](https://support.microsoft.com/excel)
- [MATLAB Documentation](https://www.mathworks.com/help/matlab/)
- [Python Documentation](https://docs.python.org/3/)
- [NumPy Documentation](https://numpy.org/doc/)
- [pandas Documentation](https://pandas.pydata.org/docs/)
- [SciPy Documentation](https://docs.scipy.org/doc/scipy/)
- [Matplotlib Documentation](https://matplotlib.org/stable/)
- [Jupyter](https://jupyter.org/)
- [scikit-learn Documentation](https://scikit-learn.org/stable/)
- [ANSYS Learning Resources](https://www.ansys.com/academic/learning-resources)

---

**Repository:** `HVAC.projects`  
**Suggested filename:** `Engineering software.md`

**Note:** This document describes typical engineering applications of these tools. Individual project files should identify which software was actually used, what work was completed, and which results were verified.
