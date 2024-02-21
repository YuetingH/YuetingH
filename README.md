# Hi there 👋

My name is Yueting Han. I'm currently a PhD student from [MathSys CDT](https://warwick.ac.uk/fac/sci/mathsys/) at the University of Warwick. My research direction is network modelling of behavioural ecology in digital ecosystems (e.g., online media and digital market). Topics of particular interest are social network dynamics, mesoscale structure (e.g., community detection and bow-tie structure), agent-based modelling and simulation. During my research, I pay particular attention to network visualisation.

&nbsp;


## Research Projects
### A. Modelling and Predicting Online Vaccination Views using Bow-tie Decomposition
> Y. Han, M. Bazzi, and P. Turrini, ["Modelling and Predicting Online Vaccination Views using Bow-tie Decomposition"](https://royalsocietypublishing.org/doi/10.1098/rsos.231792). *Royal Society Open Science* 11, 231792. (2024)

This paper analyses the information exchange between Facebook pages with different vaccination stances (anti-, pro-, and neutral), from the lens of bow-tie structure — a network structure that groups users of information “creators”, “magnifiers”, “listeners”, etc. 

We not only uncover statistically different bow-tie structures associated with each vaccination group, but also show its efficacy in predicting page fan count increase through both machine learning and mechanistic simulation methods. Grounded in real data with generative modelling frameworks, this work encourages further research on bow-tie structure, particularly in the realm of opinion dynamics.

Data and relevant code for this research work are stored in GitHub Repo: [BT_Vaccination_Views](https://github.com/YuetingH/BT_Vaccination_Views) and have been archived within the [Zenodo repository](https://zenodo.org/records/10513913).

<img src="Network_Visualization/Vaccine_Views_Dataset.png" style="width:600px;"/>


### B. Graph-Based Anomaly Detection in Healthcare Data
>MathSys 2021-22 MSc group project at University of Warwick.

Our external partners at [Kirontech](https://www.kirontech.com/) offer a Health Insurance Platform that helps insurance payers deal with anomalies in their insurance claims. Healthcare data naturally involves a number of relevant interactions between different entities. Kirontech has yet to explore graph-based anomaly detection (GBAD) techniques.

The goal of this project is to adopt different GBAD methods on Kirontech's real-life dataset and provide evidence that graph-based data is useful to examine different anomalies.

See details in GitHub Organization: [Kirontech-Project](https://github.com/Kirontech-Project).


<img src="Network_Visualization/Kirontech.png" style="width:600px;"/>

&nbsp;

## Technologies and Tools

![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-Julia-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-MATLAB-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Software-Gephi-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Software-Tulip-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/OS-Linux-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)


### Network-related Programming
>I led support classes for network-related programming using Python in 4th-year / MSc-year Maths module MA4M4: Topics in Complexity Science (2022/23) at the University of Warwick. 

Some resources about public datasets and coding examples are documented in GitHub Repo: [MA4M4_2023](https://github.com/YuetingH/MA4M4_2023).

---

### Network Visualisation Resources
### A. Python Packages
- **nxviz**: https://github.com/ericmjl/nxviz
- **ForceAtlas2**: https://github.com/bhargavchippada/forceatlas2
- **curved_edges**: https://github.com/beyondbeneath/bezier-curved-edges-networkx


### B. Softwares
There are many visualization tools available for network analysis, which are detailedly evaluated [here](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5540468/).  Two softwares among them are used in this project. We particularly list the installation method for Ubuntu since it is our case.

#### 1. Gephi
- **Website**: https://gephi.org/
- **Technology**: C++, Qt
- **Platform**: Windows, Mac, Linux
- **Installation for Ubuntu**: https://lucahammer.com/2020/02/26/how-to-install-gephi-0-9-2-on-ubuntu-18-04

Gephi is an open-source graph analysis and visualization tool. We use it to manually adjust graph layout by applying **ForceAtlas2**. 

#### 2. Tulip
- **Website**: https://tulip.labri.fr/site/
- **Technology**: Java
- **Platform**: Windows, Mac, Linux
- **Installation for Ubuntu**: [Tulip_quickstart.pdf](Network_Visualization/Tulip_quickstart.pdf)

Tulip is another open-source graph visualisation and analysis tool. Here it is applied for **edge bundling**.

Explanations and other platforms for **edge bundling** are available [here](https://courses.isds.tugraz.at/ivis/surveys/ss2017/ivis-ss2017-g4-survey-edge-bundling.pdf).