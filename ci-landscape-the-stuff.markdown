---
author:
- Mike Renfro\inst{1,2}
institute:
  - \inst{1}Tennessee Tech University
  - \inst{2}Campus Champions Leadership Team
title: "The Cyberinfrastructure Landscape: Systems, Providers, Technologies"
date: 2025-06-23
aspectratio: 169
theme: Cookeville
colorlinks: true
linkcolor: white
filecolor: white
citecolor: blue
urlcolor: blue
section-titles: false
toc: false
---

### Who am I? (Who are any of us, really?)

::: {.columns align=center}
::: {.column width=50%}
#### Back in the day
- ME student at a medium-sized public STEM-ish university who should have studied more instead of helping people do things in computer labs.
- Sysadmin/CAD/FEA co-op student at Oak Ridge National Lab before SGI Irix got its cameo in "Jurassic Park" ("It's a Unix system: I know this!").
:::

::: {.column width=50%}
![Some skinny nerd, 1990]

[Some skinny nerd, 1990]: figures/mike-1990.jpg { width=100% }
:::
:::

::: notes
**(Skip this if this is the second of a two-part talk.)**

To give you a bit of an idea where I come from in all of this, my LinkedIn bio that has all the fancy language about decades of experience supporting engineering research really comes down to this:

I'm a self-diagnosed high-functioning ADHD guy who probably should have studied more than he helped people in computer labs.

I lucked into a couple of co-op years at Oak Ridge National Lab doing a mix of CAD support, Unix systems administration, and actual engineering.
:::

### Who am I? (Who are any of us, really?)

::: {.columns align=center}
::: {.column width=70%}
#### Now
- Three ME degrees from the now-R2 university (1995, 1998, 2018)
- Mostly-solo practitioner of all things RCD at the same university (2000--2017, 2017--)
- Perpetually online member of multiple RCD organizations (2018--)
- Member of Campus Champions Leadership Team (2022--), CaRCC Emerging Centers Steering Committee (2024--)
- Compulsive advice-giver
:::

::: {.column width=30%}
![Same nerd, not remotely skinny, 2023]

[Same nerd, not remotely skinny, 2023]: figures/mike-2023.jpg { width=100% }
:::
:::

::: notes
**(Skip this if this is the second of a two-part talk.)** That eventually turned into a bunch of degrees from my original university, which I like to call a masters in shaking things and a PhD in breaking things. I spent 17 years as an R&D engineer in a research center, and then as the first campus-wide HPC systems administrator in central IT. I'm a member of way too many RCD community groups, been on the Campus Champions leadership team for nearly 3 years, on the CaRCC Emerging Centers steering committee for about a year, and I'm a compulsive advice giver and rabbit-hole-chaser.

**(Keep this regardless.)** So, in terms of systems, providers, and technologies, there's a huge array of those out there. Rather than give you every detail about every one of them and running out of time, let me start with the resources you can use to *find* more of those resources, especially computational and storage resources outside your institution. Depending on your or your users' background, you might get overwhelmed by the variety of options, or your users might make a suboptimal choice based off what they're used to using, even when better resources exist.

So let's take a look at some of the federally-funded resources and how you can narrow things down a bit.
:::

# Computational and/or Storage Resources

## National Science Foundation

### ACCESS Allocations Portal

::: {.columns align=top}
::: {.column width=80%}

![](figures/access-allocations-home.png){ width=80% }

https://allocations.access-ci.org/

:::
::: {.column width=20%}
[![](figures/qr-access-allocations-home.png)](https://allocations.access-ci.org/)
:::
:::

::: notes
The critical mass of NSF-funded resources can be found via the Advanced Cyberinfrastructure Coordination Ecosystem: Services & Support program, or ACCESS.

And ACCESS' allocations portal is the starting point for getting set up on ACCESS, whether for yourself or for your researchers.
:::


### ACCESS Project Types

::: {.columns align=top}
::: {.column width=80%}

Explore

: for resource evaluation, grad student projects, small classes/training events, benchmarking, development/porting, other small-scale cases

Discover

: for grants with modest needs, Campus Champions, large classes/training events, NSF graduate fellowships, gateway development

Accelerate

: for experienced users with mid-scale needs, multi-grant programs, collaborative projects, growing gateways

Maximize

: largest-scale research activities

:::
::: {.column width=20%}
[![](figures/qr-access-allocations-project-types.png)](https://allocations.access-ci.org/project-types)
:::
:::

::: notes
The first thing ACCESS needs from you is a project categorization.

A whole lot of your use cases can be met with the lower two project types. They'll accommodate classes or training workshops, your NSF graduate fellowship recipients, and if you're a smaller institution, even these smaller project types can overwhelm your local resources.

But ACCESS can also accommodate the highest scale of research activities, all the way out to the ones that make international news for black holes and subatomic particle discoveries.
:::

### ACCESS Project Types

::: {.columns align=top}
::: {.column width=80%}

Explore, Discover, Accelerate:

- run for grant duration or 12 months
- can be requested any time
- allow multiple projects

Explore

: 400k credits, only an overview required

Discover

: 1.5M credits, 1-page proposal required

Accelerate

: 3M credits, 3-page max proposal required, subject to merit review

Maximize

: usually only 1 project allowed, 10-page max proposal required, subject to merit review, requests accepted every 6 months

:::
::: {.column width=20%}
[![](figures/qr-access-allocations-project-types.png)](https://allocations.access-ci.org/project-types)
:::
:::

::: notes
The ACCESS procedures are a vast improvement over XSEDE's in terms of barriers to entry, flexibility, and responsiveness.

No shade on XSEDE for what it enabled, but ACCESS learned a lot of lessons from XSEDE.

In particular, all but the highest tier of ACCESS request can be submitted at any time during the year, and have pretty small justification requirements.

Your project is awarded credits that can be applied to any ACCESS resource, and any unused resources can be exchanged back into credits. So you can do more exploration and maybe make a few more small mistakes without jeopardizing research progress.
:::


### ACCESS Resource Catalog

::: {.columns align=top}
::: {.column width=80%}

![](figures/access-resource-catalog.png){ width=90% }

:::
::: {.column width=20%}
[![](figures/qr-access-resource-catalog.png)](https://allocations.access-ci.org/resources/)
:::
:::

::: notes
As you're working on the documentation for the ACCESS project you'll submit, you can also check out ACCESS' resource catalog.

It has somewhere on the order of 20 different services listed, and there's no way you'll want to go through all of them one at a time.

So they provide some plain-language filters on the right where you and your researchers can narrow down the type of resource you're interested in, and then you can get more information on each of them by clicking their entry in the list on the right.

I'm going to give you a brief survey of some of the newest and maybe the most interesting resources on the list, but by all means, explore through all the filtering options to find what works best, and reach out to ACCESS or others in the RCD communities for advice if needed.
:::

### **New**: DeltaAI at National Center for Supercomputing Applications (NCSA)

::: {.columns align=top}
::: {.column width=80%}

- 152 NVIDIA Grace-Hopper nodes, with 288 cores and 4 NVIDIA H100 GPUs (96 GB) each
- Superchip architecture
- 6 PB Lustre for `$HOME` and `$SCRATCH`
- 200 Gb HPE/Cray Slingshot networking

:::
::: {.column width=20%}
[![](figures/qr-delta-ai.png)](https://docs.ncsa.illinois.edu/systems/deltaai/)
:::
:::

::: notes
One of the newest systems, DeltaAI, is at the University of Illinois' National Center for Supercomputing Applications.

NCSA is basically the motherland of academic supercomputing for me, and their new DeltaAI system is very GPU-heavy for any and all accelerated simulation, AI, deep learning, and similar applications.
:::

### Delta at National Center for Supercomputing Applications (NCSA)

::: {.columns align=top}
::: {.column width=80%}

- All using AMD 7763 CPUs
- 132 nodes with 128 cores and 256 GB RAM
- 100 nodes with 64 cores, 256 GB RAM, and 4 NVIDIA A40 CPUs
- 100 nodes with 64 cores, 256 GB RAM, and 4 NVIDIA A100 GPUs
- 6 nodes with 128 cores, 2048 GB RAM, and 8 NVIDIA A100 GPUs
- 1 node with 128 cores, 2048 GB RAM, and 8 AMD MI100 GPUs
- Same storage and networking as DeltaAI

:::
::: {.column width=20%}
[![](figures/qr-delta.png)](https://docs.ncsa.illinois.edu/systems/delta/)
:::
:::

::: notes
Also at NCSA, the DeltaAI's predecessor, Delta, is also very GPU-heavy.

Those may not contain the absolute newest, most bleeding-edge hardware, but 800+ Ampere GPUs is nothing to sneeze at.
:::

### Stampede3 at Texas Advanced Computing Center (TACC)

::: {.columns align=top}
::: {.column width=80%}

- **New**: 24 Sapphire Rapids nodes with 1024 GB RAM, and 4 NVIDIA H100 (96 GB) GPUs
- 20 Intel Sapphire Rapids nodes each with 4 Intel GPUs, 128 GB HBM
- 560 Intel Sapphire Rapids nodes (no GPUs), 128 GB HBM
- 1060 Intel Skylake nodes, 192 GB RAM
- 224 Intel Ice Lake nodes, 256 GB RAM
- 10 PB VAST (`$SCRATCH`) + 1 TB Lustre (`$WORK`)
- 100 Gb Omni-Path networking
- Intended for:
  - parallel applications scalable to 10,000+ cores
  - general purpose computing
  - throughput computing

:::
::: {.column width=20%}
[![](figures/qr-stampede3.png)](https://docs.tacc.utexas.edu/hpc/stampede3/)
:::
:::

::: notes
Texas Advanced Computing Center at UT Austin has Stampede3, an absolutely enormous HPC installation with over 1800 nodes and a mix of Intel and NVIDIA GPUs, high bandwidth memory, and high speed networking.

Though it's more than capable of handling application runs at the tens of thousands of cores scale, they'll also take smaller sized jobs and high throughput computing applications.

This just launched in late 2023, is a successor to TACC's successful Stampede and Stampede2 installations, and in mid-2025, they added several nodes with H100 GPUs.
:::


### Bridges-2 at Pittsburgh Supercomputing Center (PSC)

::: {.columns align=top}
::: {.column width=80%}

- 488 nodes with 128 AMD 7742 cores and 256 GB RAM
- 16 nodes with 128 AMD 7742 cores and 512 GB RAM
- 4 nodes with 96 Intel Cascade Lake cores and 4096 GB RAM
- **New**: 10 nodes with 104 Intel Sapphire Rapids cores, 2048 GB RAM, and 8 NVIDIA H100 GPUs (80 GB)
- 31 nodes with 40 Intel Cascade Lake cores, 102--512 GB RAM, and 8 NVIDIA V100 GPUs (16--32 GB)
- 1 node with 48 Intel Skylake cores, 1536 GB RAM, and 16 NVIDIA V100 GPUs (32 GB)
- 15 PB Lustre for `$PROJECT`
- 200 Gb Infiniband networking

:::
::: {.column width=20%}
[![](figures/qr-bridges-2.png)](https://www.psc.edu/resources/bridges-2/)
:::
:::

::: notes
Bridges-2 at the Pittsburgh Supercomputing Center managed by Carnegie Mellon and the University of Pittsburgh is a long-standing resource spanning the XSEDE and the ACCESS programs.

Again, not all of it is the most bleeding edge hardware, but for certain applications, their extreme memory nodes with 4 TB of RAM each are invaluable.

Recently, they beefed up their GPU capacity with several nodes with 8 H100 GPUs in them.

Bridges-2 has long been my go-to resource when my users outgrow what I can do, or when a backhoe takes out my data center's power, leading to a weeks-long storage outage in 2023.
:::

### Derecho at National Center for Atmospheric Research (NCAR)

::: {.columns align=top}
::: {.column width=80%}

- All using AMD 7763 CPUs
- 2488 nodes with 128 cores and 256 GB RAM
- 82 nodes with 64 cores, 512 GB RAM, and 4 NVIDIA A100 GPUs (40 GB)
- 200 Gb HPE/Cray Slingshot networking
:::
::: {.column width=20%}
[![](figures/qr-derecho.png)](https://arc.ucar.edu/docs)
:::
:::

::: notes
Predominantly serving research for atmospheric, climate, and other Earth system processes, the National Center for Atmospheric Research's Derecho system is very CPU-heavy, with over 300,000 CPU cores in one system.

It also has a few hundred A100 GPUs, but the CPU capacity is one of the key differentiators for Derecho.
:::

### Anvil at Purdue University

::: {.columns align=top}
::: {.column width=80%}

- Supporting CPU, GPU simulation and large memory simulation
- "Composable Subsystem" offers Kubernetes support for science gateways and other workloads
- All using dual AMD 7763 CPUs (128 cores)
- 1000 CPU nodes with 256 GB RAM, 32 with 1024 GB RAM
- 16 GPU nodes with 512 GB RAM and 4 NVIDIA A100 GPUs

:::
::: {.column width=20%}
[![](figures/qr-anvil.png)](https://www.rcac.purdue.edu/anvil#docs)
:::
:::

::: notes
Purdue's Anvil facility straddles a line between traditional simulation and private cloud workloads.

One unique attribute of Anvil is their Composable Subsystem that offers Kubernetes container support for inferencing, specialized large language models, science gateways, and other application hosting.
:::


### Jetstream2 at Indiana University

::: {.columns align=top}
::: {.column width=80%}

- Hybrid cloud platform for flexible, on-demand, programmable cyberinfrastructure tools
- Interactive virtual machine services
- Infrastructure and orchestration services for research and education
- AMD Milan CPUs (128 per node)
- 360 NVIDIA A100 GPUs
- 512--1024 GB RAM
- 100 Gb Ethernet

:::
::: {.column width=20%}
[![](figures/qr-jetstream2.png)](https://docs.jetstream-cloud.org/)
:::
:::

::: notes
Jetstream2 at Indiana University is a private cloud environment focused on on-demand cyberinfrastructure needs.

It runs OpenStack on the backend, and you can use it to provide long-running VMs for research purposes, whether or not those VMs have computationally intensive workloads.

But for the ones that are computationally intensive, Jetstream's nodes are pretty dense on CPUs and GPUs.

I used Jetstream2 for a workshop I hosted at PEARC last year, and I absolutely wouldn't have been able to conduct that workshop without them. So many thanks to the Jetstream2 folks.
:::

### ACES at Texas A&M University

::: {.columns align=top}
::: {.column width=80%}

- 130 nodes, 11888 cores
- Mostly Intel Sapphire Rapids, some Intel Ice Lake, Intel Cascade Lake, and AMD Rome
- Tons of mostly-composable accelerators:
  - GPUs: NVIDIA H100 and A30, Intel (coming soon)
  - FPGAs: Bittware Agilex, Intel D5005
  - Coprocessors: NextSilicon
  - Optane memory modules
- Non-composable accelerators:
  - Graphcore IPUs: GC200, Bow-2000
  - NEC Vector Engine: Type 20B-P
- 2.3 PB Lustre
- 200 Gb Infiniband networking

:::
::: {.column width=20%}
[![](figures/qr-aces.png)](https://hprc.tamu.edu/kb/Quick-Start/ACES/)
:::
:::

::: notes
The last ACCESS facility I want to talk about is ACES at Texas A&M.

It's quite a bit different than the other systems we've looked at.

Its niche is in software-defined architectures and composability of resources more than raw compute power.

They've got a mix of Intel and AMD CPUs, but the main draw there is the wide range of accelerators: not just GPUs. but FPGAs, coprocessors, vector engines, and intelligence processing units.

Most of those accelerators can be shared across multiple nodes, leading to an incredibly flexible facility for some of the more uncommon use cases.
:::

## Department of Energy

### Advanced Scientific Computing Research (ASCR)

::: {.columns align=top}
::: {.column width=80%}

![](figures/doe-ascr.png){ width=80% }

:::
::: {.column width=20%}
[![](figures/qr-ascr.png)]()
:::
:::

::: notes
The other main federal agency I think of for scientific research is the Department of Energy.

Oak Ridge National Lab is about 90 minutes away from me, and we've had close relationships for graduate programs, collaborative research, and other work.

So Oak Ridge's Leadership Computing Facility is part of DOE's Advanced Scientific Computing Research arm, or ASCR.

If ACCESS isn't the best fit for what you're doing, or especially if there's DOE interest in your research, give ASCR a look.
:::

### Accessing ASCR Facilities

::: {.columns align=top}
::: {.column width=80%}

- [Innovative and Novel Computational Impact on Theory and Experiment (INCITE)](https://www.alcf.anl.gov/science/incite-allocation-program): multi-year awards for open science using majority of machine at Oak Ridge or Argonne
- [ASCR Leadership Computing Challenge (ALCC)](https://science.osti.gov/ascr/Facilities/Accessing-ASCR-Facilities/ALCC): 1-year awards for advancing DOE mission or broadening the community capable of using large computing resources at Oak Ridge, Argonne, or NERSC
- [Energy Research Computing Allocations Process (ERCAP)](http://www.nersc.gov/users/accounts/): 1-year awards for advancing DOE Office of Science and SBIR/STTR mission at NERSC
- Center Reserves: 1-year awards for advancing science and engineering fields at [Oak Ridge](https://www.olcf.ornl.gov/support/getting-started/olcf-director-discretion-project-application/), [Argonne](http://www.alcf.anl.gov/directors-discretionary-dd-program), or [NERSC](https://www.nersc.gov/users/accounts/allocations/first-allocation/)

:::
::: {.column width=20%}
[![](figures/qr-ascr-accessing.png)](https://science.osti.gov/ascr/Facilities/Accessing-ASCR-Facilities)
:::
:::

::: notes
There's four main avenues into ASCR resources, each with their own niche and access to different facilities.

INCITE is based out of the Oak Ridge and Argonne labs, and is suited for open science applications that can scale to the majority of a top-10 HPC.

ALCC can help you on a year-by-year basis if your research aligns with DOE missions, or if it broadens the community that can make good use of HPC facilities at Oak Ridge, Argonne, or NERSC at Lawrence Berkeley.

ERCAP is for projects with SBIR/STTR relationships that also align with DOE Office of Science priorities.

And there's a small amount of resources left to each facility's director's discretion that fall into the "Center Reserves" category.

All of these programs are linked on this slide for easier access.
:::


## Joint NSF, other federal agencies and non-governmental partners

### National Artificial Intelligence Research Resource (NAIRR) Pilot

::: {.columns align=top}
::: {.column width=80%}
Early concept for a shared national research infrastructure connecting US researchers to:

- computational and AI,
- data,
- software,
- training, and
- educational

resources. Many of the federally-funded resources are available through ACCESS or other routes, but **NAIRR also facilitates access to commercial resources including AI models,  inference services, and software as a service offerings**.
:::
::: {.column width=20%}
[![](figures/qr-nairr.png)](https://nairrpilot.org/)
:::
:::

::: notes
Last, but not least, are the resources under the umbrella of the National AI Research Resource, or NAIRR, Pilot project.

In a lot of cases, the federally-funded resources provided through NAIRR can also be reached through ACCESS or other means, and those other means might actually be a better or easier fit for your researchers' needs.

But NAIRR is unique in receiving donations from over 25 non-governmental partners throughout the AI and cloud hyperscaler markets. If your researchers need to go beyond the hardware provided by previously-mentioned facilities, NAIRR is invaluable.
:::

# Services/Consultancies

## MATCH Plus

### Multi-tier Assistance, Training & Computational Help (MATCH) Plus

::: {.columns align=top}
::: {.column width=80%}

MATCH Plus:

- takes requests from researchers with a support need,
- identifies a student and mentor that can provide that support,
- connects the researcher to the student and mentor with regular meetings and updates,
- for 5--10 student hours and 2--3 mentor hours per week for 3--6 months,
- at **no charge**.

:::
::: {.column width=20%}
[![](figures/qr-match.png)](https://support.access-ci.org/match/overview)
:::
:::

::: notes
In the services and consulting area, ACCESS supports a few different options.

The MATCH Plus program can be a lifesaver for under-resourced research projects, or for new users.

They take requests from any researcher with a need for computational help, and matches them up with both a student and a mentor for the student to provide that support.

These engagements typically run for 3--6 months for a 5--10 hours per week for the student and 2--3 hours per week for the mentor.

From that, your project can possibly be scaled up from desktop scale to an introductory HPC scale, bottlenecks and optimizations can be identified, or you can get extra assistance migrating a workload to an ACCESS resource.

MATCH Plus engagements have absolutely zero charge to the researcher, so please make use of them.
:::

## MATCH Premier

### Multi-tier Assistance, Training & Computational Help (MATCH) Premier

::: {.columns align=top}
::: {.column width=80%}

MATCH Premier:

- takes requests from already-funded projects,
- identifies an expert consultant and arranges payment,
- for a 6--12 month period.

:::
::: {.column width=20%}
[![](figures/qr-match.png)](https://support.access-ci.org/match/overview)
:::
:::

::: notes
For established projects with available budget, a higher tier called MATCH Premier is available.

This is better suited for projects that might benefit from a post-doctoral student or research scientist, but your insitution might not have those available, or at least not available in time.

These are paid engagements between the researcher and the expert consultant, and ACCESS facilitates making those connections.
:::

## Engagement and Performance Operations Center (EPOC)

### Engagement and Performance Operations Center (EPOC)

::: {.columns align=top}
::: {.column width=80%}
> EPOC provides researchers with a holistic set of tools and services needed to debug performance issues and enable reliable and robust data transfers. By considering the full end-to-end data movement pipeline, EPOC is uniquely able to support collaborative science, allowing researchers to make the most effective use of shared data, computing, and storage resources to accelerate the discovery process.

-- https://epoc.global/
:::

::: {.column width=20%}
[![](figures/qr-epoc.png)](https://epoc.global/)
:::
:::

::: notes
The Engagement and Performance Operations Center (EPOC) consults on reducing bottlenecks in network performance, data transfer, and similar areas.

They offer a "roadside assistance" service for reactive troubleshooting of network problems.

They also offer an "application deep dive" service that looks more closely at application workflows, Science DMZs, and related areas to evaluate bottlenecks and potential capacity issues in a more proactive way.

They also provide network monitoring tools like NetSage to more practively discover and resolve performance issues.
:::

## Science Gateways

### Science Gateways

::: {.columns align=top}
::: {.column width=80%}

> [Science g]ateways are online interfaces that give researchers, educators, and students easy access to shared resources that are otherwise inaccessible or unaffordable for a large segment of the scientific community.
>
> ...
>
> The SGCI was founded to provide services and resources that advance the state of the art in science gateways, that help gateway creators use accepted practices in developing and operating gateways, and that catalyze the formation of a community that may be diverse in discipline but has a common need to advance science through gateways.

:::

::: {.column width=20%}
![](figures/sgx3.png)

![](figures/sgci.png)

[![](figures/qr-sg.png)](https://sciencegateways.org)
:::
:::

::: notes
The Science Gateways Community Institute and the SGX3 center of excellence provide an invaluable resource to your software-facing folks.

Science gateways are usually web-based interfaces to computational resources, and can greatly reduce the barriers to entry for those resources.

They've got interests in workforce development, broadening the community using advanced cyberinfrastructure, providing expert advice, and steering future software and gateway development practices.
:::

# Tools and Software

## OpenHPC

### OpenHPC

::: {.columns align=top}
::: {.column width=80%}
> OpenHPC is a Linux Foundation Collaborative Project whose mission is to provide a reference collection of open-source HPC software components and best practices, lowering barriers to deployment, advancement, and use of modern HPC methods and tools.
>
> OpenHPC components and best practices will enable and accelerate innovation and discoveries by broadening access to state-of-the-art, open-source HPC methods and tools in a consistent environment, supported by a collaborative, worldwide community of HPC users, developers, researchers, administrators, and vendors.

-- https://openhpc.community/about-us/

:::

::: {.column width=20%}
![](figures/ohpc_logo.png)

[![](figures/qr-openhpc.png)](https://openhpc.community/)
:::
:::

::: notes
The OpenHPC project has been an abolute life saver for me.

They provide a completely free and open source suite of components to build HPC architectures with a minimum of effort.

I've had every one of my student workers build a virtual OpenHPC environment on their laptop, and they've all managed to get one running within a working day (with a little bit of advice sometimes).

If your HPC environment was a turnkey vendor product and it's running out its support lifecycle, OpenHPC can give that cluster an extended lifespan.

It can also let you focus your budget on hardware and people rather than licensing fees, for those where that makes sense.
:::

## Open XDMoD

### Open XDMoD

::: {.columns align=top}
::: {.column width=80%}
![](figures/open-xdmod.png)
:::
::: {.column width=20%}
[![](figures/qr-open-xdmod.png)]()
:::
:::

::: notes
Open XDMoD from the University of Buffalo is an invaluable tool to quantify your HPC's usage trends, and then communicate that to reesarchers, leadership, or other stakeholders.

Open XDMoD has helped me stop so many conversations that started with "I'm not getting enough access to the cluster" and wound up in a much more productive direction as a result.

Also totally free and open source, with a long history of development and support.

This is one of the tools that makes an under-resourced institution look more professional.
:::

## Open OnDemand

### Open OnDemand

::: {.columns align=top}
::: {.column width=80%}
![](figures/ood-lrc.png)
:::
::: {.column width=20%}
[![](figures/qr-open-ondemand.png)]()
:::
:::

::: notes
Open OnDemand from the Ohio Supercomputer Center is an outstanding tool to make things easier on new users, and experienced users often like it as well.

It provides a web interface to your HPC users' files, web-based terminals to your login systems, monitoring of jobs, facilitates graphical desktop access to your cluster nodes, and lets you build or use application forms to streamline common computational tasks.

Your security people will be happy that it can be integrated with whatever multi-factor authentication you're using elsewhere, and you'll probably hear good things from your users about it.
:::

## Spack

### Spack

::: {.columns align=top}
::: {.column width=80%}

- Spack is a package management tool designed to support multiple versions and configurations of software on a wide variety of platforms and environments.
- It was designed for large supercomputing centers, where many users and application teams share common installations of software on clusters with exotic architectures, using libraries that do not have a standard ABI.
- Spack is non-destructive: installing a new version does not break existing installations, so many configurations can coexist on the same system.

-- https://spack.readthedocs.io/

:::
::: {.column width=20%}
[![](figures/qr-spack.png)]()
:::
:::

::: notes
My last tool is Spack, which provides a framework and tooling to build software packages.

It integrates with the modules system you might already have, and makes it much easier to support optimized builds of computational tools compared to what you might get with a simple configure/make/make install set of commands.

They usually offer full-day workshops at PEARC, and all their training material is online. But attending the workshop in person was invaluable for me and one of my students in getting past a few hurdles.
:::
