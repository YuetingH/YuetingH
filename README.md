# Hi there 👋

My name is Yueting Han. I am currently a MSc student from [MathSys CDT](https://warwick.ac.uk/fac/sci/mathsys/) at University of Warwick. My main research interest is network modelling, keen on its visualization!

&nbsp;


## Network Modelling

### Graph-Based Anomaly Detection in Healthcare Data
>MathSys 2021-22 MSc group project at University of Warwick.

Our external partners at [Kirontech](https://www.kirontech.com/) offer a Health Insurance Platform that helps insurance payers deal with anomalies in their insurance claims. Healthcare data naturally involves a number of relevant interactions between different entities. Kirontech has yet to explore graph-based anomaly detection (GBAD) techniques.

**The goal of this project is to adopt different GBAD methods on Kirontech's real-life dataset and provide evidence that graph-based data is useful to examine different anomalies.**

See details in GitHub Organization: [Kirontech-Project](https://github.com/Kirontech-Project).


<img src="Network_Visualization/Community_Detection.png" style="width:700px;"/>

&nbsp;

## Technologies and Tools

![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-Julia-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-MATLAB-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Software-Gephi-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Software-Tulip-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/OS-Linux-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)

---

### Programming Syntax
See relevant notes in my GitHub Repo [Syntax_Notebook](https://github.com/YuetingH/Syntax_Notebook).

---

### Network Visualization Resource
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

Gephi is an open-source graph analysis and visualization program. We use it to manually adjust graph layout by applying **ForceAtlas2**. 

#### 2. Tulip
- **Website**: https://tulip.labri.fr/site/
- **Technology**: Java
- **Platform**: Windows, Mac, Linux
- **Installation for Ubuntu**: [Tulip_quickstart.pdf](Network_Visualization/Tulip_quickstart.pdf)

Tulip is another open-source graph visualization and analysis tool. Here it is applied for **edge bundling**.

Explanation and other platforms for **edge bundling** are available [here](https://courses.isds.tugraz.at/ivis/surveys/ss2017/ivis-ss2017-g4-survey-edge-bundling.pdf).