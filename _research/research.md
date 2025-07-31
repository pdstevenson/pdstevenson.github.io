---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Nuclear Structure and Reactions

With PhD students [Isaac Hobday](https://www.surrey.ac.uk/people/isaac-hobday); [Khlood Al-Harthi](https://www.surrey.ac.uk/people/khlood-alharthi); [Lance Li](https://www.surrey.ac.uk/people/lance-li); and with many collaborators

Atomic nuclei are made up of protons and neutrons.  Understanding nuclear properties such as their size, shape, binding energy, and excited state spectrum is the remit of *nuclear structure*.  We work on theoretical models which in some way or another involve wrangling the many-body Schrödinger equation and the complicated nucleon-nucleon interactions into a form that allow for practical calculations to help us understand nuclear structure from a microscopic (= at the level of individual neutron and proton wave functions) level.

The basic approach in my work is the self-consistent mean field using Skyrme-type effective interactions;  from there the effects of interaction properties are explored, and approximations relaxed to go beyond the restrictions of the mean-field approach.  

The picture below shows some recent calculations of octupole excitations in even-even nuclei around <sup>208</sup>Pb

<img src="/files/spectra.png" alt="octupole spectra" width="50%">

Nuclear reactions involve the interaction of nuclei with another object which could be another nucleus, or some external probe such as a photon.  The decay of nuclei in which the multiple objects are in the final state can also be considered as a kind of nuclear reaction.  Applying a time-depedent version of the mean-field methods used for structure calculations allow details of structure and reactions to be described in a single framework.  Applications include deep-inelastic reactions, Coulomb excitation, fusion and fission reactions, and a number of exotic relatives such as quasifission and fusion-fission.  

The principal code used for these calculations, Sky3d, is published and freely available.  The code is hosted at [github](https://github.com/manybody/sky3d) and the latest published version, [Sky3d, 1.2 is available from Computer Physics Communications](https://doi.org/10.1016/j.cpc.2024.109239)

The picture below (from [Phys. Rev. C 103, L031304 (2021)](http://dx.doi.org/10.1103/PhysRevC.103.L031304)) shows the fission pathway of the nucleus <sup>240</sup>Pu at finite temperature, showing different allowed trajectories caused by the statistical fluctuations inherent in quantum mechanics

<img src="/files/fission.png" alt="fission pathway" width="50%">

## Quantum Computing

With current MSc students Lloyd La Ronde, Robbie Giles, and James Garcia; withPhD student [Joe Gibbs](https://scholar.google.com/citations?hl=en&user=FvrrWhAAAAAJ) and previous PhD students [Isaac Hobday](https://www.surrey.ac.uk/people/isaac-hobday) and [Lance Li](https://www.surrey.ac.uk/people/lance-li); with current postdoc [Chandan Sarma](https://www.surrey.ac.uk/people/chandan-sarma) and previous postdoc [Bharti Bhoy](https://www.surrey.ac.uk/people/bharti-bhoy); with [James Benstead](https://scholar.google.com/citations?hl=en&user=25DxbjwAAAAJ), [Jim Al-Khalili](https://www.surrey.ac.uk/people/jim-al-khalili), [Bhoomika Maheshwari](https://scholar.google.com/citations?hl=en&user=f_gKvV8AAAAJ) and other collaborators

Quantum computers are previously hypothetical and now realised devices which make use of properties of quantum mechanics to allow certain calculations to be achieved much more efficiently than on regular computers.  In particular, simulating many-body quantum systems (such as nuclei) is theoretically possible on quantum computers in a way that copes with the huge combinatorial increase in complexity of the problem when the number of nucleons becomes large.  

Our work is on developing quantum algorithms that are able to perform practical calculations of nuclear properties and running them on todays limited-qubit and noisy quantum computers, as well as planning for future systems of larger noise-free (or error-corrected) qubits.

The picture below (from [ New Journal of Physics 26, 075001 (2024)](https://iopscience.iop.org/article/10.1088/1367-2630/ad5756) shows a quantum circuit used to prepare the ground state wave function of Ni-58 in a shell model picture in which two neutrons are created (with the "X" gates) and then distributed across other single particle levels (via the "G<sup>2</sup>" gates)

<img src="https://arxiv.org/html/2402.15577v1/x3.png" alt="quantum circuit" width="50%">

## Nuclear Data and Machine Learning

With PhD student [Sam Sullivan](https://www.surrey.ac.uk/people/samuel-sullivan); with [Payel Das](https://www.surrey.ac.uk/people/payel-das), James Benstead, Aaron Stott and Lee Morgan

Nuclear data in general means all of the experimental data that has been compiled from years of experiments covering nuclear structure and reactions.  Some of the data is excellent, while some has large error bars, and yet more lacks information about errors or is partially complete in some way.  In other cases of interest, desired data does not exist becase the experiments required to measure the data are not practical or have otherwise not been performed.  

We use machine learning methods to evaluate nuclear data and to understand how we might use models as a proxy for existing databases.  As a starting point, see [EPJ Web of Conf. 284, 03007 (2023)](https://www.epj-conferences.org/articles/epjconf/abs/2023/10/epjconf_nd2023_03007/epjconf_nd2023_03007.html) for some pre-machine-learning explorations of data of interest.  The plot below shows various ways of representing neutron resonance structures across a wide range of incident neutron energy.  Plot from paper linked to above.

<img src="/files/ndata.png" alt="neutron capture cross section data" width="50%">

## Other Work

With MPhys student Ben King, and with [Marco Sacchi](https://www.surrey.ac.uk/people/marco-sacchi), [Louie Slocombe](https://www.surrey.ac.uk/people/louie-slocombe), [Evan Cryer-Jenkins](https://orcid.org/0000-0003-2549-0280) and others

As well as the main research areas mentioned above, I work on generic computational methods beyond their application just to nuclear physics or quantum computing problems;  in quantum biology and chemistry, particularly in quantum tunnelling in DNA;  in special relativity where a student project (by Evan Cryer-Jenkins) led to a paper on visualisation of Terrell rotations.

The picture below from the special relativity work ([Proc. Roy. Soc. A 476, 20190703 (2020)](http://dx.doi.org/10.1098/rspa.2019.0703)) shows combined distortion and redshift effects on a fast-moving cyclist as seen by a left and right eye in combination.

<img src="/files/cyclist.png" alt="relativistic cyclist" width="50%">
