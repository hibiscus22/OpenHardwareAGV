[![Project License](https://img.shields.io/badge/license-CERN-green)](https://github.com/hibiscus22/OpenHardwareAGV/blob/main/LICENSE)
![File Count](https://img.shields.io/github/directory-file-count/hibiscus22/OpenHardwareAGV)
[![GitHub stars](https://img.shields.io/github/stars/hibiscus22/OpenHardwareAGV?style=social)](https://github.com/hibiscus22/OpenHardwareAGV/stargazers)
![GitHub Forks](https://img.shields.io/github/forks/hibiscus22/OpenHardwareAGV?style=social)


# OpenHardwareAGV
Repository that hopefully may guide you in the construction of an Open Source Vehicle. Thanks for visiting!

## What is this exactly?

A Open Source Hardware (OSH) repository for an Autmated Guided Vehicle (AGV), a mobile robot used in factories mostly to carry things. 

This is intented to be a modular framework which may lay the foundations towards building many different and configurable vechiles depending on its purpose, thus gaining an edge above closed source vehicles.

Ideally, each different vehicle project will be given its own branch, if this grew bigger we could set a brach per vehicle usage or what turns out the most useful.

## Installation

As there is no real code for this yet, you may only find useful having the files on your own computer so you can make any adaptation to our designs. To download this repository, just run 

```sh
git clone https://github.com/hibiscus22/OpenHardwareAGV
```
on your work directory. All files from the main branch should be downloaded onto it.

If what what you intent to download is another branch from the repo, then run:

```sh
git clone --branch <branchname> https://github.com/hibiscus22/OpenHardwareAGV
```


## What we've done so far (what you can find in the report):
- Main Branch (generals)
    - Defined and limited a specific used for AGV: towing AGV which can work as underride.
    - Display the components and basics of AGV building
    - Chose and applied an OSH method (Oberloier and Pearce)
    - Developed and studied choosing methods for battery, motors, mechanics, sensors, and more superficially, processsing hardware and software
    - Worked on how to get the vehicle through the industrial standard (ISO 3691-4:2020)
    - CAD models of the frame and bodywork, tested with Finite Element Analysis.
- Construction Branch
    - Showing the process of construction 
    - Testing of previous work



## What we want to accomplish
- Building more real models
- Creating a consistent section with the software
    - Movement Control
    - Guidance
    - Fleet control
- Testing
    - If the chosen components are feasible
    - Passing the standard
- Do a decent github <:
    - Make general brach a bit clearer
    - Workflow
    - More contributors