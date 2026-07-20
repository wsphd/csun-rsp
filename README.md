# High-Performance Computing (Resources and Capabilities)


![https://github.com/wsphd/csun-hpc](images/qr.svg "https://github.com/wsphd/csun-rsp")\
<https://github.com/wsphd/csun-rsp/>

**High-Performance Computing (Resources and Capabilities)**\
**Brief for Office of Research and Sponsored Programs**\
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
    * Everyone (especially Faculty) wants replication, reproducibility, and robustness
    * Everyone (especially Admininstration) wants scale, sustainability, and support
  * partly driven by diminishing returns to Moore's law (need more <ins>G</ins>PUs than <ins>C</ins>PUs)
  * partly driven by shift from closed-form (equations) data analysis to iterative-based (algorithms) data analysis
  * partly driven by campus distinctive mission (even similarly-sized CSUs are unique)


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

* campus Champions (mostly IT-ish) Help on Research Computing and Data from around the CSU
  * CSU Chancellor's Office - Matt Hughes (Infrastructure), Kendra Ard (Applications), Carol Kiliany (Systemwide RCTA group coordination)
  * Cal Poly Humboldt - Ravi Chalasani (Applications), Casey Hefner (Infrastructure), A. Cade Webb (Admin), Bethany Gilden (Admin), Brian Campbell (Applications)
  * Cal Poly Pomona - Alex Harwood (Admin), David Drivdahl (Applications), Curtis Carpenter (Infrastructure and Applications)
  * CSU Bakersfield - Alberto Cruz (Applications), Brian Chen (Admin), Chris Diniz (Admin), Charles Lam (Applications), Ernest Richards (Infrastructure), Nick Rowland (Infrastructure), Joe Nailor (Infrastructure), Jaimi Paschal (Applications), Anjana Yatawara (Applications)
  * CSU Chico - Scott Clavarie (Infrastructure), Elbert Chan (Infrastructure)
  * CSU Dominguez Hills - Bill Elbettar (Infrastructure and Applications)
  * CSU Fullerton - Willie Peng (Admin and Infrastructure), Dhusdee Chandswang (Identity Management), Taylor Livingston (Admin)
  * CSU Monterey Bay - Rick Sibinski (Infrastructure)
  * CSU Northridge - Zack Hillbruner (IT, Infrastructure), Yolanda Barrett (ECS, Applications)
  * CSU Sacramento - Peggy Kay (Admin), Mark Hendricks (Admin), Carl Oakes (Infrastructure)
  * CSU San Bernardino - Dung Vu (Infrastructure and Applications), James Macdonnell (Applications), Nabeel Alzahrani (Data), Samuel Sudhaker (Admin), Gerald Au (Admin)
  * Fresno State - Bao John (Admin), Vinay Gowdra-Halappa (Infrastructure)
  * San Diego State - Henry Li (Infrastructure/especially CENIC AIR-TIDE), Kyle Krick (Applications), Michael Farley (Admin), James Frazee (Admin), Anthony Harris (Infrastructure)
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
  * FABRIC is Adaptive ProgrammaBle Research Infrastructure for Computer Science and Science Applications (FABRIC)
  * PATh High-Throughput Computing (PATh) (OSG batch-style processing)
  * Open Science Grid (OSG)/OSPool/HTCondor
  * Open Science Data Federation (OSDF)

* National Institutes for Health (NIH)
  * NIH Cloud Lab - Science and Technology Research Infrastructure for Discovery, Experimentation, and Sustainability (STRIDES)

* National Aerospace and Space Agency (NASA)
  * NASA Center for Climate Simuolation (NCCS) Prism GPU cluster
  * NASA Advanced Supercomputing (NAS) Cabeus supercomputer

* Department of Energy (DOE)
  * Argonne Leadership Computing Facility (ALCF) AI Testbed
  * National Energy Research Scientific Computing Center (NERSC)
  * Oak Ridge Leadership Computing Facility (OLCF)
  * American Science Cloud (AmSC)

* Oregon State University Open Source Lab (OSL)

* D-Wave LEAP Quantum Launchpad/D-Wave Learn Program (D-Wave)

* Although perhaps not widely known...
  * ,,, all of these resources can be used by students for research, including undergraduates
  * ,,, nearly all of these resources can be used by faculty and students for instruction
  * ,,, "science driver" means, in practice, "scientific method" (i.e., a broader definition than for an NSF grant/award proposal)

* HPC-related NSF initiatives
  * National Artificial Intelligence Research Resource (NAIRR) Pilot
  * (TIP) AI Ready America
  * (CISE) Expeditions in Computing
  * (OAC)
    * Integated Systems and Services
    * Campus Cyberinfrastructure (CC*)
    * Cyberinfrastructure for Sustained Scientific Innovation

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
  * Pelican Platform
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

* CSUN IT keeps Single-Sign On (SSL) and federated identity (CILogon) working

* Wayne S. (DNCBE)
  * Initial Faculty Conversations
    * has briefed all relevant Faculty Senate standing committees but the Library Committee
    * has presented at a Faculty Retreat (we have more time there)
    * has briefed both prior ECS and SCM Deans
  * Initial Students Conversations
    * has briefed relevant students at the annual OUR conference
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
  * Initial Students Conversations
    * has briefed relevant students at the annual OUR conference
  * others


## Open Issues

* Opportunities/Challenges
  * It could be that this type of work is needed *even* at an R3 because we are large, important, engaged, and diverse

  * Existing and New Faculty need to know what's available, what's useful, what's supported
  * Expanded opportunities for external funding

  * Workforce opportunities (undergraduate and graduate research, grad. school, CI skills for AI, etc.)
  * For example, LACCD is attached to the NRP (with the servers at LAVC)
  * Far beyond JuypterHub, a non-chargeback system for sandboxing and experimentation is huge (with no local clients or servers)

* Risks/Tensions
  * Persistent storage (with, perhaps, F.A.I.R. principles, etc.)
  * The above systems can do CUI (but need to follow the NSF rules) but not (P4) classified, PII, HIPPA, or ITAR data
    * e.g., new M.S. in Health Analytics (but there are others)

  * Research is discipline-specific and very individualistic (even more so than instruction)
    * some skills, knowledge, abilities are better off decentralized than centralized

  * Some cultural changes
    * For this type of work, we will need to embrace open source software
      * (side note: the CSU should have an Open Source Program Office too)
    * For this type of work, everyone needs to know that there is some learning curve (but Wayne tries to keep it low)

  * Reputational Risk
    * We want to offer state-of-the-art resources and capabilities but some services are provided by non-CSU/non-CSUN providers

* Short-term goals/issues
  * Collaboriation/Learning
    * Presumably, every research-computing-intensive faculty member is (or can be) collaborating others on campus and elsewhere
      * so, each administrator and staff member should do the same with a colleague on another CSU campus (on the IT-ish side, see my brief list above)
  * I need to brief the current ECS and SCM Deans
  * There is a Research conference from STEM*NET at CSU Fullerton next semester (Wed. March 24 - Fri. March 26, 2027)
  * I think someone from *both* IT and RSP think about joining at least one CaRCC affinity group

  * I tend to know the IT-ish groups but I am less familiar with the support structures for RSP managers and professionals
    * National Council of University Research Administrators (NCURA)
    * Society of Research Administrators International (SRA)
    * National Organization of Research Development Professionals (NORDP)
    * Research Administrators Certification Council (RACC)

* Longer-term goals/ideas
  * I/We needs to go to the Library Committee (of the Senate) or something deeper
    * ...and something beyond Data Management Plan (even *that* is hard)
      * for storage, our researchers might need: general, collaborative, computational, secure, data sharing/publishing
      * among others, Findable, Accessibile, Interoperable, Reproducible (FAIR) principles
    * Coalition for Networked Information (CNI)
    * Research Data Alliance (RDA)
    * Open Storage Network (OSN)
    * others...
  * I/We/someone needs to go to the Provost's Council (I can be there if Ron/Jawa needs me)
  * Ron can brief the Cabinet (I can be there if he needs me)

  * We need to also brief the DFOs
    * without chargebacks, like for AWS, the Dean's Office might know what people are doing
    * at some point, there might be "token budgets" for expensive AI uses beyond the OpenAI contract

  * If persistent, engaged discussions aren't happening at the Chancellor's Office (CO), frankly, we should push it (grin)
    * this includes AI but is larger than AI

* We could build some type of organizational structure for this activity (see several other CSU campuses)
  * Research Computing and Data (RCD) is definitely an "all of University" issue (see "CaRCC" five "faces" above)
  * The campus needs to decide its posture on research support in general and research computing/data support specifically
    * (aligned with existing campus strategy)
  * varying CSU models
    * CSUN (minimalist), "catch-as-catch-can", "hug-my-computer"
    * CSUSB (maximalist), "Build-Operate-Transfer" (BOT) - do everything for you and then turn it over to you when completed
    * (something in the middle)
  * The campus will need "wrap-around" analysis and support from multiple units
    * "intake" form
    * "referral" procedure

  * The campus will need some type of organizing/advisory body at some point
  * The campus would benefit from Research Computing "Fellows" just like have in other places
  * We need recurring, regularlized Research Computing and Data activity - like FacDev and IT (and others) do now
    * or perhaps a slight addition to the Research Fellow symposium (Library?)
    * or perhaps a slight addition to the Jerome Richfield Fellow talk (RSP?)
    * or perhaps add it to the monthly newsletter (beyond prior workshops in obtaining an ORCID ID)

* Eventually, Wayne can't do this forever (and is the wrong person anyway)

