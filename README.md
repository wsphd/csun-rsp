# High-Performance Computing (Resources and Capabilities)


![https://github.com/wsphd/csun-hpc](images/qr.svg "https://github.com/wsphd/csun-rsp")\
<https://github.com/wsphd/csun-rsp/>

**High-Performance Computing (Resources and Capabilities)**\
**Brief for Office of Research and Sponsorded Programs**\
**Ranjit Philip and Wayne Smith**\
**California State University, Northridge (CSUN)**\
**Fall, 2026**


## Links/References

* I've removed the links on this page so that we can focus on our discussion.
  * [CSUN IT/FTC Technology Resources for Research](https://www.csun.edu/it/academic-technology/faculty-technology-center-ftc/technology-resources-research)
  * [Wayne's CSUN High-Performance Computing Resources](https://github.com/wsphd/csun-hpc)
    * This presentation is mostly adapted from this web page, so further links are there (same general order and headings).


## Introduction/Background/Motivation

* Some faculty need more computing, storage, or networking than the University can provide.
  * chiefly driven by growth of data (mostly STEM but SocialSTEM, Business, CTVA, Digital Humanities, etc. too)
  * partly driven by diminishing returns to Moore's law (need more <ins>G</ins>PUs than <ins>C</ins>PUs)
  * partly driven by shift from closed-form (equations) analysis to iterative-based (algorithms) analysis
  * partly driven by campus distinctive mission (teaching always primary but research still there and still important)
  * partly driven by leadership (we have to prioritize resources and capabilities)


## Faculty/Disciplines

* CSUN is a big place--there are many faculty doing interesting things with HPC

* Some folks need help with both on-premisis infrastructure and remote infrastucture (clusters)
  * Ravi Absol (Chem), Xunfei Jiang (CompSci), Rachel Mackelprang (Bio)

* Some folks need help with just remote infrastructure (clusters)
  * Regan Mass (Geography), Xiyi Hang (ECS), Scott Kleinman (English)

* Some folks need help with just knowing about the resources (and their grad. students can do the rest)
  * Nhut Ho (MechEng), Marjan Asadinia (CompSci)

* Some folks need help with just seeing a complete analytical workflow (application) from scratch
  * Dongling Huang (Marketing), Akash Gupta (SysOpsMgt), Yuan Lu (Accountancy)

* Some folks don't need any help at all (i.e., **I learn from them**)
  * Steve Fitzgerald (CompSci), Jussi Eloranta (Chem), Nick Kioussis (Physics), Jeremy Yoder (Bio), Bingbing Li (MSE)
  * and others I don't even know...

* And there are still plenty of folks for whom a (University provided) notebook PC, Box, and, say, SPSS is fine


## Some preliminary CSU contacts

* IT-ish Help on Research Computing and Data from around the CSU
  * CSU Chancellor's Office - Matt Hughes (Engineering), Kendra Ard (Applications), Carol Kiliany (Systemwide RCTA group coordination)
  * Cal Poly Humboldt - Ravi Chalasani (Applications), Casey Hefner (Engineering), Cade Webb (Admin), Bethany Gilden (Admin)
  * Cal Poly Pomona - Alex Harwood (Admin), David Drivdahl (Applications), Curtis Carpenter (Engineering and Applications)
  * CSU Bakersfield - Alberto Cruz (Applications), Brian Chen (Admin), Chris Diniz (Admin), Charles Lam (Applications), Ernest Richards (Engineering), Nick Rowland (Engineering), Joe Nailor (Engineering), Jaimi Paschal (Applications), Anjana Yatawara (Applications)
  * CSU Chico - Scott Clavarie (Engineering), Elbert Chan (Engineering)
  * CSU Dominguez Hills - Bill Elbettar (Engineering and Applications)
  * CSU Fresno - Bao John (Admin), Vinay Gowdra-Halappa (Engineering)
  * CSU Fullerton - Willie Peng (Admin and Engineering), Dhusdee Chandswang (Identity Management)
  * CSU Monterey Bay - Rick Sibinski (Engineering)
  * CSU Northridge - Zack Hillbruner (IT, Engineering), Yolanda Barrett (ECS, Applications)
  * CSU Sacramento - Peggy Kay (Admin), Mark Hendricks (Admin), Carl Oakes (Engineering)
  * CSU San Bernardino - Dung Vu (Engineering and Applications), James Macdonnell (Applications), Nabeel Alzahrani (Data), Samuel Sudhaker (Admin), Gerald Au (Admin)
  * San Diego State - Henry Li (Engineering/especially CENIC AIR-TIDE), Kyle Krick (Applications), Michael Farley (Admin), James Frazee (Admin), Anthony Harris (Engineering)
* (at CSUN each service Department needs to find their counterparts)


## JupyterHub

* CSUN Apporto "myCSUNSoftware" (little or no GPUs), CSU-TIDE (some GPUs), CAL-ICOR (many GPUs)
  * simple command line in R, Python, or Julia but it is interactive through a Web browser GUI
  * we can use the JupyterHubs elsewhere too, for example on LibreTexts


## High-Performance Computing Resources

* National Science Foundation (NSF)
  * mostly Office of Advanced Cyberinfrastructure (OAC)
  * some Division of Computer and Network Systems (CNS)

  * Advanced Cyberinfrastructure Coordination Ecosystem: Services & Support-Cyber Infrastructure (ACCESS-CI)
    * Jetstream2 (from Indiana University)
    * and about 30 more Resource Providers
    * Cloudbank2
      * public clouds (e.g., Amazon Web Services, Google Compute Platform, MS-Azure, etc.)
  * National Research Platform (NRP)
  * National Data Platform (NDP)
  * NSF National Artificial Intelligence Research Resource Pilot (NAIIR)
  * FABRIC is Adaptive ProgrammaBle Research Infrastructure for Computer Science and Science Applications (FABRIC)
  * PATh High-Throughput Computing (PATh) (OSG batch-style processing)

* National Institutes for Health (NIH)
  * NIH Cloud Lab - Science and Technology Research Infrastructure for Discovery, Experimentation, and Sustainability (STRIDES)

* Department of Energy (DOE)
  * Argonne Leadership Computing Facility (ALCF) AI Testbed
  * National Energy Research Scientific Computing Center (NERSC)
  * Oak Ridge Leadership Computing Facility (OLCF)
  * American Science Cloud (AmSC)

* Oregon State University Open Source Lab (OSL)

* D-Wave LEAP Quantum Launchpad/D-Wave Learn Program (D-Wave)

* Although not widely known, nearly all of those resources can be used for instruction and can be used by students (research/instruction)

* AI-related resources
  * Jetstream2 (IU) offers 8 petaflops of capacity for AI models (mostly open weight models--pre-built and custom)
    * this can be used for high-end users with big AI requirements and little or no AI budget
  * NRP hosts 74 GPUs just for open-weight (open source) AI models via OpenWebUI (GUI) or the OpenAI API (just like ChatGPT)
    * this can be used for high-end users with big AI requirements and little or no AI budget
    * within reason, there are no limits (for now)
  * NSF offers a new system (National Deep Inference Project-nsf.ai) only for AI research (including by students)


## Conferences/Fellowships

* There are plenty of zero-cost and low-cost U.S. domestic events for learning about HPC resources at the _Application_-level.

| Name          | Venue         | Cost         |Timeframe         |
| ------------- | ------------- |------------- |------------- |
| [Practice & Experience in Advanced Research Computing<br>(PEARC)]          | varies  | mid $ | late July | 
| [RCD Nexus Day (precedes PEARC)]          | varies  | $0 | late July | 
| [Science Gateways Community Institute (SGCI)]          | varies  | $0 (NSF) | varies | 
| [A Center of Excellence in Science Gateways (SGX3)]          | varies  | $0 (NSF) | varies | 
| [Confab (DOE)]          | varies  | low $ | early April | 
| [Institute for Mathematical and Statistical Innovation (IMSI)]          | varies  | $0 (NSF) | varies | 
| [US-RSE Conference (US-RSE)]          | varies  | $0 (Sloan) | early October | 
| [IEEE eScience]          | varies  | mid $ | mid September | 
| [1st Workshop on Workflows, Intelligent Scientific Data, and Optimization for Automated Management (WISDOM)]          | San Diego  | mid $ | early September | 
| [Researcher Workshop (ACES)]          | Columbus, OH | $0 (NSF) | mid-July | 
| [JupyterCon 2025 (JupyterCon)]          | San Diego  | mid $ | early November |
| [Research Evaluation and Analytics Capacity Hub (REACH)]          | (varies)  | $0 (NSF) | late April |

* There are plenty of zero-cost and low-cost U.S. domestic events for learning about HPC resources at the _Infrastructure_-level.

| Name          | Venue         | Cost         |Timeframe         |
| ------------- | ------------- |------------- |------------- |
| [CENIC Community Technology Affinity Group (C2TAG)]          | La Mirada, CA (and virtual)  | $0 (CENIC) | quarterly | 
| [Research Computing at Smaller Institutions (RCSI)]          | Swarthmore, PA  | $0 (NSF) | early June | 
| [Intersect Training (INTERSECT)]          | Princeton, NJ  | $0 (NSF) | mid June | 
| [National Research Platform (NRP)]          | UCSD, CA  | $600 | late January | 
| [Supercomputing (SC)]          | St. Louis, Denver, Atlanta  | low $ | mid November | 
| [Corporation for Networking and Research (CENIC)]          | varies  | low $ | late March | 
| [Southern California Linux Expo (SCaLE)]          | Pasadena, CA  | low $ | early March | 
| [Rocky Mountain Advanced Computing Consortium (RMACC)]          | Boulder, CO  | low $ | late May | 
| [OpenInfraDays (OpenInfra at SCaLE)]          | Pasadena, CA  | low $ | early March | 


## National Workshops

* There are plenty of _in-person_ events for learning about HPC resources.

| Name          | Venue         | Cost         |Timeframe         |
| ------------- | ------------- |------------- |------------- |
| [Minority-Serving Cyberinfrastructure Capabilities (MS-CC)]          | varies  | $0 (NSF) | late May | 
| [Open Science Grig (OSG)]          | U of Wisconsin-Madion, WI  | $0 (NSF) | late June |
| [ByteBoost Cybertraining Program (ByteBoost)]          | Carneigie Mellon U.  | $0 (NSF) | early August | 
| [Throughput Computing Week (HTC25)]          | in-person (U. of Wisc./Madison) and virtual | $125 in-person, $0 virtual | early June  | 
| [HPC and Data Science Summer Institute (SDSC)]          | UCSD, CA  | $350 | late July - early August |
| [NERSC International HPC Summer School (NERSC)]          | varies  | $0 (DOE) | early July |
| [KNIT Community Workshop (FABRIC)]          | varies  | $0 (NSF) | mid March
| [INTERSECT Research Software training (INTERSECT)]          | Princeton/Alabama  | $0 (NSF) | mid July |
| [SHINE Workshop (SHINE)]          | Iowa City  | $0 fees | mid August |
| [ESIIL Innovation Summit (ESIIL)]          | U of Colorado  | $0 fees, $0 (NSF) | late September |
| [Building Research Innovation at Community Colleges - Research Data Management (BRICCs-RDM)]          | Texas A&M  | $0 (NSF) | early July |


## Upskilling - Professional Associations/Societies

* Faculty - These general-purpose, multidiscplinary HPC resources should be of use to _Faculty_ over time.
  * Open Science Data Federation (OSDF)
  * ACM HPC (ACMHPC)
  * Advanced Cyberinfrastructure - Research and Education Facilitators (ACI-REF)
  * R OpenSci (ROpenSci)
  * PyOpenSci (pyOpenSci)
  * PREreview -  Open PrePrint Reviews (PREreview)
  * SciPyi (SciPy)
  * JuliaCon (annual Summer conference abstracts, proceedings)
  * Consortium for Advanced Data Assimilation Research and Education (CADRE)
  * High Performance Computing Collaboratory (HPC<sup>2</sup>)
  * ACM SIGHPC Edu (SIGHPC-Edu)
  * Framework for Open and Reproducible Research Training (FORRT)
  * OpenMP (OpenMP)
  * Open Accelerated Computing (OpenACC) (C/C++ optimizations for research, annual Summer conference)
  * NumFOCUS (NumFOCUS) (open resource software practices)
  * Consortium for the Advancement of Scientific Software (CASS) (DoE sponsored)
  * Center for Open-Source Research Software Stewardship and Advancement (CORSA)
  * LF AI & Data (AI Innovation)
  * US Research Software Sustainability Institute (URSSI)
  * Open Molecular Software Foundation (OMSF)
  * ZENODO (open data/scholarship/publication repository - managed by CERN and OpenAIRE)
  * Software Carpentries (software engineering)
  * The Carpentries (data science and coding)
  * Massachusetts Green High Performance Computing Center (MGHPCC)
  * Workflows Community)
  * (and check your discipline's pre-conference workshops and related conference themes for HPC events)

* Faculty - These _open source_, _discipline-specific_ open source software environments are commonly used on HPC clusters.
  * Fluid Dynamics - [OpenFOAM (OpenFOAM)]
  * Molecular Dynamics/Mechanical Forcefields - [AMBERMD (AMBERMD)]
  * 3D Creation/Gaming - [UnReal Engine (UNREAL)]
  * Visual Immersion and Sharing - [Smart Amplified Group Environment) (SAGE3)]
  * Mathematical Optimization - [HiGHS Solver (HiGHS)]
  * Earth Sciences - [Open, Reproducible, and Scalable Geoscience (PanGeo)]
  * Earth Science - [Climate Sensitive Infectious Disease (CSID) Network]
  * Scientific UI/UX Development - Strudel Science (STRUDEL)]
  * Pegasus Scientific Workflow Management (PEGASUS)]

* Staff - These HPC resources should be of use to _Staff_ over time.
  * [Campus Research Computing Consortium (CaRCC)]
    * five "faces" of research computing - Researcher-facing, Systems-facing, Data-facing, Strategy and Policy-facing, Emerging Centers-facing 
  * [US Research Software Engineering Association (US-RSE)]
    * career path, professional society, conferences, etc.

* Sundry - These charitable organizations occasionally provide funding for HPC-related and scientific software.
  * Chan/Zuckberberg Initiative (Essential Open Source Software for Science (Cycle 6))
  * Schmidt Sciences
  * Pasteur Labs
  * Kavli Foundation (general science)
  * Wellcome Trust (generally, health-related research software
  * Simons Foundation (generally, math and physical sciences software)
  * Sloan Foundation (generally, emerging technology of any type)
  * Allen Institute (generally, technologies related to biology, neuroscience, and similar areas)
  * Kapor Foundation (generally, technology equity) 
  * William T. Grant Foundation (generally, reducing youth inequity)
  * Code for Science and Society (generally, open source software)
  * The Neuro - Irv and Helga Cooper Foundation (generally, open science)
  * The Navigation Fund (generally, open science)


## Some Things that Have Been Done

* Wayne S. (DNCBE)
  * Initial Faculty Conversations
    * has briefed all relevant Faculty Senate standing committees but the Library Committee (need to go at some point)
    * has presented at a Faculty Retreat (we have more time there)
  * has attended multiple regional and national meetings at no cost (CSU/CSUN or College/Dept)
  * has developed initial relationships with key players in SoCal and within the CSU (and assisted other campuses too)
  * has helped some faculty and a few students
  * has tried to ensure that all resources are available to all faculty and students (especially historically underrepresented)
  * has tried to ensure that NSF-funded resources can be used productively by NIH-type researchers if NIH monies continue to dry up
  * is an "admin" on NRP
  * Appointed to the NSF ACCESS Researcher Advisory Committee (1 year of a three year appointment)
  * have been asked by the NSF to apply for a rotating position in NSF (not interested)

* Zack H. (CSUN IT)
    * coordinated the built-out of the infrastructure (systems and network) to connect to the NRP as a full participant
    * has presented at a Faculty Retreat (we have more time there)
    * is an "admin" on NRP
    * others


## Open Issues

* Research Computing and Data (RCD) is definitely an "all of University" issue (see "CaRCC" five "faces" above)
  * The campus needs to decide its posture on research support in general and research computing/data support specifically
    * (aligned with existing campus strategy)
  * The campus will need "wrap-around" analysis and support from multiple units
  * The campus need some type of organizing/advisory body at some point
  * The campus would benefit from Research Computing "Fellows" just like have in other places
  * We need recurring, regularlized activity - like FacDev and IT (and others) do now
* Some cultural changes
  * For this type of work, we will need to embrace open source software
    * (the CSU should have an Open Source Program Office too)
  * For this type of work, everyone needs to know that there is some learning curve (but Wayne tries to keep it low)
  * We need to also brief the DFOs
    * without chargebacks, like for AWS, the Dean's Office might know what people are doing
    * at some point, there might be "token budgets" for expensive AI uses beyond the OpenAI contract
* We need to go to the Provost's Council
  * For one thing, research is discipline-specific and very individualistic (even most so than instruction)
* Each administrator and staff member can meet with at least one counterpart at another CSU campus on this issue
  * (on the IT side, see my brief list above)
* There is a Research conference from STEM*NET at CSU Fullerton next semester
  * We should go (although, to be honest, CSUSUPERB can be a good affinity group too)
* There are many programmatic and instructional touchpoints too
  * For example, LACCD is attached to the NRP (with the servers at LAVC)
  * Far beyond JuypterHub, a non-chargeback system for sandboxing and experimentation is huge
  * We should go (although, to be honest, CSUSUPERB can be a good affinity group too)
* Eventually, Wayne can't do this forever (and is the wrong person anyway)

