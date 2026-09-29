# 👤 About me
I'm a fifth year Engineering Physics student with a somewhat unorthodox Master's in Cybersecurity at the Royal Institute of Technology (KTH). My background combines advanced mathematics, data analysis, and machine learning with hands-on experience in network programming and systems security. 

My bachelor's thesis explored optimisation algorithms for federated learning, comparing convergence and fairness across clients in a simulated environment, work that clutivated my interest in machine learning and privacy-preserving technologies. Right now, I am deepening my knowledge of neural networks and deep learning, aiming to understand how these methods can be applied to network security problems.

## ⚙️ Tech Stack 
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![Bash Script](https://img.shields.io/badge/bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Databricks](https://img.shields.io/badge/databricks-%23FF3621.svg?style=for-the-badge&logo=databricks&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%23257BD6.svg?style=for-the-badge&logo=docker&logoColor=white)

<!-- Logos are created with shields.io by URL in the following way, 
https://img.shields.io/badge/name-%23hexcolor.svg?style=for-the-badge&logo=logo&logoColor=white

- name : text
- %23hexcolor.svg : 23% = #, hexcolor = color in hex,
- ?style=for-the-badge : bold badge style
- &logo=logo : icon for the logo
- &logoColor=white : sets the text color against the background
-->

## 🔨 Projects

<!--### Network system security environment [repo](https://github.com/Sekuil/networking-monorepo)-->

### Static Analysis for Supply Chain Attack Detection in Python Packages [repo](https://github.com/winkelmannfelix/DD2525-project)
This project extends a static analysis tool, GuardDog, with an LLM extension to reduce false positives. GuardDog uses Semgrep rules to flag malicious content and code in PyPI packages but is known to produce false positives, which is problematic in automatic pipelines. The evaluation used a dataset of 10,000 confirmed malicious PyPI packages along with 15,000 benign PyPI packages. The goal was to analyse the static analysis rules used in GuardDog and determine to what extent an LLM would help.

### Advanced Encryption Standard (AES) Implementation [repo](https://github.com/Sekuil/aes-implementation)
Implemented a basic version of AES encryption in python that uses ECB mode.

### Optimisation Algorithms for Federated Learning [repo](https://github.com/lkwenn/Bachelor-s-Thesis-Project-M6)
Bachelor's thesis that explored and tested optimisation algorithms for federated learning, a machine learning approach where models are trained collaboratively across multiple devices without sharing raw data. The thesis compared five algorithms, FedAvg, FedAdam, FedYogi, AdaFedAdam, and FedAvg-M, on the CIFAR10 and Fashion-MNIST datasets under varying degrees of data heterogeneity. The algorithms were evaluated on both accuracy and fairness across clients. In conclusion the FedAvg-M algorithm, which adds a momentum term and shared search direction, consistently achieved the best overall performance and fastest convergence. 

### Simulation of a Two-Stage Rocket Launch [repo](https://github.com/Sekuil/rocket-simulation)
A physics based simulation of a two-stage super heavy-lift rocket, integrating thrust, gravity, and atmospheric drag with a 4th-order Runge-Kutta method to model its ascent. The project includes trajectory and velocity visualizations, and a fuel optimization sweep to determine the optimal stage 1/stage 2 fuel combintations to achieve escape velocity. 

### Autoencoder [repo](https://github.com/Sekuil/autoencoder)
A small deep learning project that explores autoencoders on synthetic trigonometric waveforms `A*sin(nx) + B*cos(nx)`. The project compares a standard unsupervised autoencoder against a variant with latent space supervision to test the autoencoders ability to reconstruct meaningful variables in the latent space.

### Yatzy game [repo](https://github.com/Sekuil/yatzy-gui)
A graphical Yatzy game built in Python with Tkinter, supporting multiple players in a single window. The game handles dice rolling and re-rolling, automatic score calculation for all Yatzy categories, and a full scoreboard with bonus tracking per player.