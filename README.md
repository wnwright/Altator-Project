# Altator Project

# 🌀 Altator: Miniature Toroidal Plasma Demonstrator

**Altator** is a student-designed, tabletop toroidal plasma device created at MIT’s Plasma Science and Fusion Center (PSFC). Inspired by the heritage of Alcator C‑Mod, this transparent-glass tokamak provides a vivid, safe, and interactive way to showcase how plasmas are confined in toroidal magnetic fields.  
[Learn more at PSFC MIT](https://www.psfc.mit.edu/resources/news/new-discoveries-in-fusion-energy-research-6/)

---

## 🎯 Purpose & Objectives

- **Educational Outreach**: Brings plasma physics to public audiences by visibly displaying glowing plasma in a transparent vessel.  
- **Hands-On Training**: Immerses graduate students in systems- and project-level fusion engineering.  
- **Rapid Prototyping**: Demonstrates practical fusion technologies—RF coupling, vacuum systems, and magnet design—in a small-scale, replicable format.

---

## 🎓 Origins & Team

- Concept proposed by a group of ten graduate students (Nuclear Science & Engineering and Physics).
- Developed as an independent project—with initial seed funding and oversight from PSFC leadership—over approximately two years of evening-and-weekend work.
- Core contributors: John Ball, Jacob van de Lindt, Grant Rutherford, Audrey Saltzman, Thomas Varnish, Alex Velberg, Miguel Calvo‑Carrera, Tucker Evans, Shon Mackie, Scott Moroch.

---

## 📂 Repository Structure
- This repository serves as the repo for the Beckhoff PLC control system
- It should only include static files such as programs, function block, etc. NOT compiled binaries (such as /Boot files). The .gitignore should handle all this.

---

## Getting setup
- Please make sure that people are aware of any work being done, just to reduce liklihood of merge compatability
- Download the TwinCAT3 XAE with proper versions (in documentation)
- Fork this repo into your github account
- Clone the forked repo
- **Always check that you can login with the most recent repository release! Otherwise, there are mismatches between versions (someone either forgot to push or forgot to login their changes to the PLC)**
- Login to PLC to download the compiled binaries and test your code
- Assuming the downloaded repo is up-to-date, make changes on a separate branch and push to the master remote repo (assign code reviewers as need be)
