# intro-HPC-bootcamp-2023
This repository contains information related to the Intro to HPC Bootcamp held in person at Lawrence Berkeley National Laboratory in August 2023. The Bootcamp is hosted by the Department of Energy (DOE) Advanced Scientific Computing Research (ASCR) Computing Facilities at Argonne National Lab (ALCF), Lawrence Berkeley National Lab (NERSC), and Oak Ridge National Lab (OLCF) and organized by Sustainable Horizons Institute.

## Links

* [Bootcamp public page](https://shinstitute.org/intro-to-hpc-bootcamp/)
* [Bootcamp website for participants](https://shinstitute.org/energy-justice-bootcamp-2023/)
* [Join the Slack workspace](https://join.slack.com/t/introtohpcbootcamp/shared_invite/zt-1zib8v8o7-YScKtNaFBoLif2EvdhcYcQ)
* [NERSC user account info](https://docs.google.com/document/d/1LgeRCeqpROkfsQ7hmnPJTmRwooHJkpSRXkFxQr0hQhw/)
* [NERSC JupyterHub](https://jupyter.nersc.gov)

## Presentations
* Monday
  * Tutorial/Talk/Panel title, with link to slides/materials (TBA)
  * Tutorial/Talk/Panel title, with link to slides/materials (TBA)
* Tuesday
* Wednesday
* Thursday
* Friday
  
## Projects
| **Project (and link project description)**                                                                                                                                                                                                                                    | Project Page                                                                              | Institution              | **Lead**                                      |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:-----------------------------------------------------------------------------------------:|:------------------------:|:---------------------------------------------:|
| [Project 1: AI-Powered Equity Analysis of Renewable Energy Laws](https://shinstitute.org/ai-powered-equity-analysis-of-renewable-energy-laws/)                                                                                                                                           | [AI for Energy Justice](https://github.com/AI4EnergyJustice/Tutorials)                                                                                      | ANL                      | Murat Keceli                                  |
| [Project 2: Energy Justice Analysis of Climate Data](https://shinstitute.org/energy-justice-analysis-of-climate-data/)                                                                                                                                                                   | [Climate Analysis](https://saforem2.github.io/climate-analysis)                           | ANL                      | [Sam Foreman](https://samforeman.me)          |
| [Project 3: Solar Power for Affordable Housing through Computational Design of Low-Cost/High-Efficiency Solar Cells](https://shinstitute.org/solar-power-for-affordable-housing-through-computational-design-of-low-cost-high-efficiency-solar-cells/)                                   | [Solar Cell Data](https://github.com/alvarovm/solarcelldata)                                                                                      | ANL                      | [Alvaro Vazquez-Mayagoitia](https://github.com/alvarovm)                     |
| [Project 4: Understanding the Impact of HPC Center Energy Usage on Low-income and Minority Populations](https://shinstitute.org/understanding-the-impact-of-hpc-center-energy-usage-on-low-income-and-minority-populations/)                                                             |  [Energy Justice and Sustainability](https://sites.google.com/lbl.gov/nerschpcbootcamp2023/nerscenergyjustice2023)                                                                                      | NERSC                    | [Charles Lively](http://nersc.gov/charles-lively)                                  |
| [Project 5: Energy Cost for Disadvantaged Populations and Methods of Energy Efficiency and Energy Optimization in Computing Systems](https://shinstitute.org/energy-cost-for-disadvantaged-populations-and-methods-of-energy-efficiency-and-energy-optimization-in-computing-systems/)   | [Energy Efficiency and Optimization for Sustainability](https://sites.google.com/lbl.gov/nerschpcbootcamp2023/nerscenergyjustice2023)                                                                                       | NERSC                    | [Charles Lively](http://nersc.gov/charles-lively)                                |
| [Project 6: Power Outages and Inequities in Energy Access for Medically Vulnerable Populations](https://shinstitute.org/power-outages-and-inequities-in-energy-access-for-medically-vulnerable-populations/)                                                                             | [Github](https://github.com/secondspass/power_outages_medically_vulnerable_populations/)  | OLCF                     | Subil Abraham                                 |
| [Project 7: Socioeconomics of Power Outages and Heatwaves](https://shinstitute.org/socioeconomics-of-power-outages-and-heatwaves/)                                                                                                                                                       | [Github](https://github.com/suzannepk/power_outages_socioeconomics-)                      | OLCF                     | Suzanne Parete-Koon                           |

## Working on Project in Groups

* Besides those projects materials provided via links in the above table, each project has also prepared the project descriptions and data in the m4388 project area on the Community File System (CFS) on Perlmutter at `/global/cfs/cdirs/m4388/Project*-<name>`, such as `Project2-ClimRR`.
* Students who work on Project X Group Y will work in a shared directory in CFS at /global/cfs/cdirs/m4388/Project*-Group*, such as `Prj2-GroupC`.
* Using Prj2-GroupC as an example, you can run this command to copy over the entire Project, after login to Perlmutter:
  ```
  cd /global/cfs/cdirs/m4388/Prj3-GroupC
  cp -r /global/cfs/cdirs/m4388/Project2-ClimRR .
  ```
* Any student who would like to do some individual tests can work in their own scratch directory:
  ```
  cd $SCRATCH
  cp -r /global/cfs/cdirs/m4388/Project2-ClimRR .
  ```
* The following are the compute node reservations available during the boot camp (in Pacific time):
  * Monday, 3 pm - 5 pm, reservation name `intro_hpc_aug7`
  * Tuesday, 10:30 am - 5 pm, reservation name `intro_hpc_aug8`
  * Wednesday, 1:30 pm - 5 pm, reservation name `intro_hpc_aug9`
  * Thursday, 1 pm - 10 pm, reservation name `intro_hpc_aug10`

## Study Materials

* [OLCF Intro to Python repo](https://github.com/olcf/foundational_hpc_skills/tree/master/intro_to_python)
* [Pandas tutorial](https://www.activestate.com/resources/quick-reads/what-is-pandas-in-python-everything-you-need-to-know/)
* [Example interactive Notebooks for data research from Environmental Enforcement Watch](https://www.environmentalenforcementwatch.org/data/notebooks)
