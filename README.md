
<img width="200" height="100" alt="image" src="https://github.com/user-attachments/assets/0b48bba6-7e16-47b2-9500-cb45ee62a030" /> <img width="390" height="219.18" alt="GALLANT Logo (Primary)" src="https://github.com/user-attachments/assets/1a287b6e-83aa-4057-a0a7-ee156ddaef52" />


# CATHeaPS
**C**entralisation **A**nalysis **T**ool for **Hea**t **P**ump **S**ystems.

This repository contains **CATHeaPS-FatCat** (CATHeaPS v3), which represents the mature evolution of the **CATHeaPS-Kitten** (v1/2) framework, adding robust modules for integrating openly accessible Energy Performance Certificate (EPC) data to provide stakeholders with preliminary insights into the direct impacts of property retrofitting. CATHeaPS is an open-access modeling tool designed to assess the techno-environmental-economic impacts of decarbonising thermal systems. Developed through a collaboration between the **University of Glasgow** and the **University of Edinburgh**, the tool empowers local councils, community energy groups, and stakeholders to evaluate heat network feasibility and retrofit strategies using publicly available data.

## Model overview

This project enhanced the original CATHeaPS framework to evaluate how retrofitting impacts the performance of various thermal systems. The model evaluates four primary heating configurations:
- **4th Generation District Heating:** Low-temperature centralised heat distribution.
- **Ambient Networks:** Decentralised booster heat pumps integrated into a shared ambient temperature network with a centralised balancing unit.
- **Individual Air Source Heat Pumps (ASHP):** Standalone property-level ASHPs with calorifiers for residential properties.
- **Conventional Gas Boilers:** Used as a baseline for techno-economic comparison.

The model is split into two parts: A. Property data processing and B. CATHeaPS Simulation Model which should be use in turn.

## Demonstration videos

To help new users get up and running with **CATHeaPS-FatCat**, we've put together a 5-part video series introducing the model, walking through how to use it, and taking a deeper dive into some of the workings and assumptions behind it. 
Whether you’re completely new CATHeaPS or want to understand what’s happening under the hood, these videos are a great place to start.

  1. **Introduction to CATHeaPS** - an overview of the model and what it can be used for
  2. **Data processing and preparation** - a walk through of part A. Property data processing
  3. **Running the simulation model and interpreting the results** - a walk through of part B. Simulation Model
  4. **Deeper dive on network routing** - looking at how the heat network routing is developed in the model
  5. **Deeper dive on technical and cost database** - looking at the assumption, technical parameters and costs that underpin the model and how to change these

Grab a coffee, pick an episode, and dive in! ☕

## Key updates in this version

CATHeaPS-FatCat is a mature evolution of CATHeaPS-Kitten. The main updates in **FatCat** include:
- **Retrofit analysis:** a comparison of heat decarbonisation scenarios pre and post building retrofit.
- **Incorporation of EPC data:** ability to incorporate open access EPC data, improving ease of application across Scotland and the UK.
- **Non-linear heat networking routing:** improved networking routing for heat network scenarios.

## Key Features & Outputs

CATHeaPS-FatCat provides a holistic breakdown of the impacts of residential retrofitting across several metrics:
- **Economic Analysis:** Detailed breakdown of costs including **CAPEX, OPEX, REPEX** (Replacement Expenditure), **FUELEX** (Fuel Expenditure), and **specific retrofit costs**.
- **Environmental Impact:** Forecasted **CO2 emissions** for each thermal system configuration.
- **Technical Requirements:** Calculation of electrical capacity requirements (in **kVA**) for the local grid.
- **Retrofit Sensitivity:** All metrics are presented in **"Before"** and **"After"** states based on proposed retrofit measures derived from EPC data.

## Pilot Studies: Govanhill, Glasgow and Drumchapel, Glasgow

To demonstrate the model’s replicability and accuracy, worked case studies for two pilot project areas in **Govanhill, Glasgow** and **Drumchapel, Glasgow** are included in the repository. These case studies serve as a template for other local authorities to assess their bespoke project areas using the same methodology.

## Impact & Just Transition

By lowering the barrier to entry for complex thermal modeling, CATHeaPS facilitates informed decision-making for urban decarbonisation by:

- **Providing community groups** (such as Glasgow Community Energy) with data-driven evidence for heating options.
- **Assisting public sector bodies** in aligning with the Scottish Government’s Community and Renewable Energy Scheme (CARES).
- **Facilitating knowledge exchange** through an entirely open-source, interactive framework.

## Relevant publication and citation of the dataset

For a more detailed analysis of the methodology of CATHeaPS-FatCat and a use case for heating only systems, the following publication in the scientific journal Energy and Buildings can be visited:

Nicola Tait, Orestis Angelidis, Daniel Friedrich, Gioia Falcone, Techno-economic comparison of low-carbon heating solutions and building retrofit using CATHeaPS-FatCat: a case study for two urban neighbourhoods in Glasgow, Energy and Buildings, 2026, 117970, ISSN 0378-7788, https://doi.org/10.1016/j.enbuild.2026.117970.

## Requirements

CATHeaPS is a **Macro enabled workbook** developed on Microsoft Excel.

## License and Commercial Use

The model provided in this repository is made available for research, educational, and non-commercial purposes unless otherwise stated.

The rights to use this model for commercial or financial gain are reserved exclusively by the authors. No individual or organization may use, distribute, sublicense, or incorporate this model into products or services for financial benefit without prior written permission from the authors.

For commercial licensing inquiries, please contact the authors.

## Aknowledgements

CATHeaPS-FatCat is developed by Orestis Angelidis and Nicola Tait with the support of Daniel Friedrich and Gioia Falcone. The project was part of a collaboration between Glasgow as a Living Lab Accelerating Novel Transformation (**GALLANT**) and The Centre for Net Zero High Density Buildings (**CeNZ High-DB**). GALLANT is funded by the Natural Environment Research Council as part of the Changing the Environment Programme [grant number NE/W005042/1]. CeNZ High-DB is a Green Economy Centre funded by UKRI [grant number 2-UOG-018].

<div align="center">
  <img width="370" height="280" alt="CATHeaPS " src="https://github.com/user-attachments/assets/f41cc3d1-6042-4325-94de-b1cb9132cb73" />
</div>
