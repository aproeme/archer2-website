---
layout: post
title: ARCHER2 Weekly Newsletter
date: 2023-07-19 11:00:00
author: ARCHER2 Service
tags: [newsletters] 
categories: [news]
---


- [Coupling LAMMPS and OpenFOAM for Multi-Scale Models]({{ page.url }}#coupling-lammps-and-openfoam-for-multi-scale-models), Online, Today Wednesday 19th July 2023 14:00 - 16:00 BST
- [Parallel Performance Analysis using Scalasca]({{ page.url }}#parallel-performance-analysis-using-scalasca)
- [Change to default version of ONETEP on ARCHER2]({{ page.url }}#change-to-default-version-of-onetep-on-archer2)
- [Recently added known issues]({{ page.url }}#recently-added-known-issues)
- [Upcoming ARCHER2 training]({{ page.url }}#upcoming-archer2-training)

<!--more-->


## Coupling LAMMPS and OpenFOAM for Multi-Scale Models

Online webinar, Wednesday 19th July 2023 14:00 - 16:00 BST

Mirco Magnini and Gabriele Gennari (University of Nottingham), Edward Smith (Brunel University London), Gavin Pringle (EPCC, University of Edinburgh)

The next generation of science depends on solving the problem of linking simulations at different scales. In many physical processes, phenomena happening at the molecular scale determine the large-scale dynamics of the system. Boiling represents one such problem, where bubbles nucleating at the nanoscale depart from hot surfaces owing to fluid dynamics forces originating from millimetre-scale flow structures. To date, there is no existing modelling framework that can simultaneously capture all the relevant scales of this flow, that require molecular dynamics simulations at the nanoscale coupled with traditional continuum-scale techniques based on the control-volume formulation of the Navier-Stokes equations.

The objective of this project is to deliver a coupling platform, optimised for parallel computing, linking two popular molecular-scale and continuum-scale simulation tools that are already supported on ARCHER2, namely LAMMPS for molecular dynamics simulations (MD) and OpenFOAM for computational fluid dynamics (CFD) simulations. This will be achieved by extending the functionality of the coupling framework CPL library , developed by one of the investigators. The coupling is oriented towards the multi-scale simulation of nucleate boiling, where molecular dynamics resolves the near-wall field where nucleation occurs and continuum-scale fluid dynamics is used far from the wall where the bubble develops.

In this webinar, we will:

- Introduce the project and the rationale behind MD-CFD coupling.
- Present CPL library and the coupling framework.
- Demonstrate how to evoke CPL library via the ARCHER2 module through examples including minimal dummy scripts, 
- Couette flow and finally the full boiling case.

[Full details and join link](https://www.archer2.ac.uk/training/courses/230719-openfoam-lammps-vt/)


## Parallel Performance Analysis using Scalasca

22 - 23 August 2023 09:30 - 16:30 BST in [Oxford](https://www.archer2.ac.uk/training/locations/oxford-dtc)

[Scalasca](https://www.scalasca.org/) is a software tool that supports the performance optimization of parallel programs by measuring and analyzing their runtime behaviour. It uses execution profiles and traces generated by the community-developed Score-P instrumentation and measurement infrastructure. The analysis identifies potential performance bottlenecks – in particular those concerning communication and synchronization – and offers guidance in exploring their causes.

[Scalasca](https://www.scalasca.org/) targets mainly scientific and engineering applications based on the programming interfaces MPI and OpenMP, including hybrid applications based on a combination of the two. The tool has been specifically designed for use on large-scale systems, but is also well suited for small- and medium-scale HPC platforms. The software is available for free download under the New BSD open-source license.

This course will cover how to use the tools in practice, delivered by members of their development team. Practical exercises will be conducted on the UK National HPC Service ARCHER2, an HPC Cray EX system; attendees will be given accounts on ARCHER2 for the duration of the course. Although example parallel programs will be provided, attendees are encouraged to analyse the performance of their own applications on ARCHER2.

[Full details and registration]( https://www.archer2.ac.uk/training/courses/230822-scalasca/)



## Change to default version of ONETEP on ARCHER2

The default version of ONETEP on ARCHER2 was changed to a newer version `onetep/6.1.43.0-CCE-LibSci` on Mon 17 July 2023. The current default version is `onetep/6.1.9.0-CCE-LibSci` 

If you wish to continue to use the older version after this change, you will need to change your job submission scripts to explicitly load the older version.
   

## Recently added known issues
 
The "[Known Issues](https://docs.archer2.ac.uk/known-issues/)" page of the ARCHER2 Documentation
<https://docs.archer2.ac.uk/known-issues/>
lists all current open known issues including a description of the issue, its symptoms and any work-arounds.

- No recent issues


## Upcoming ARCHER2 Training

- [Message-passing Programming with MPI](https://www.archer2.ac.uk/training/courses/210000-mpi-self-service/), Online, always-open self-service course
- [Shared Memory Programming with OpenMP](https://www.archer2.ac.uk/training/courses/210000-openmp-self-service/), Online, always-open self-service course
- [QM/MM with GROMACS + CP2K](https://www.archer2.ac.uk/training/courses/220000-gromacs-self-service/), Online, Always open - self-service course <br><br>
- [Coupling LAMMPS and OpenFOAM for Multi-Scale Models](https://www.archer2.ac.uk/training/courses/230719-openfoam-lammps-vt/), Online, Wednesday 19th July 2023 14:00 - 16:00 BST
- [Slurm: Scheduling jobs on ARCHER2](https://www.archer2.ac.uk/training/courses/230726-slurm-vt), Online, Wednesday 26th July 2023 15:00 - 16:00 BST
- [Parallel Performance Analysis using Scalasca](https://www.archer2.ac.uk/training/courses/230822-scalasca/) , Oxford, 22 - 23 August 2023 09:30 - 16:30 BST 

[Further details of upcoming training](https://www.archer2.ac.uk/training/#upcoming-training)

We always welcome researchers wishing to present their work in a webinar - please contact the [Service Desk](https://www.archer2.ac.uk/support-access/servicedesk.html) if you would be interested in presenting your work.

[Twitter](https://twitter.com/ARCHER2_HPC)

[Recordings of past courses](https://www.archer2.ac.uk/training/materials/)

[Recordings of past virtual tutorials](https://www.archer2.ac.uk/training/materials/webinars)