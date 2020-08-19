---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
author_profile: true
title: "About me"
---

I am a Particle Physics PhD student in the [LHCb Collaboration](https://lhcb-public.web.cern.ch/) at CERN, based in the University of Bristol. My research experience includes extensive programming, statistical analyses and machine learning. 

See below for details on my PhD and other projects. Please also follow the menu to see my key [publications]({% link _pages/Publications.md %}), [talks]({% link _pages/talks.md %}), [CV]({% link _pages/CV.md %}), and [other interests]({% link _pages/interests.md %}). 

## PhD Project
The LHCb Experiment is a highly specialised particle detector, using data collected from proton collisions at the Large Hadron Collider at [CERN](https://home.cern/) to answer fundamental physics questions such as why there is more matter than anti-matter in the Universe. As part of my PhD I was able to spend a long-term attachment of 15 months at CERN, where I collaborated further with colleagues outside my institute and acquired more hands-on experience with the detector itself. 

My thesis focuses on the measurement of the decay $B^0 \rightarrow D^0 \overline{D}{}^0 K^+ \pi^-$, and I am the lead proponent of the first observation of this mode. Studying this decay has major implications for decays such as $B^0 \rightarrow K^{\ast0}\mu^+\mu^-$, which have shown tensions with the Standard Model of particle physics. Studying the structures in $B^0 \rightarrow D^0 \overline{D}{}^0 K^+ \pi^-$ will shed light on the theoretical uncertainties involved, and dictate the models that may be used to describe potential 'New Physics' processes. 

In order to make a measurement of this decay, a number of data mining methods are used to extract the interesting signal out of "noise", ie. the multitude of other events seen by the detector. For example, in this analysis I use an optimised neural network to classify signal from the so-called combinatorial background. This blue signal region in the figure below demonstrates the observation of events corresponding to $B^0 \rightarrow D^0 \overline{D}{}^0 K^+ \pi^-$.

![DDKpi_plot](/assets/images/DDKpi_plot.png)

## RISE Germany Internship
As part of the DAAD German Exchange Service, I was awarded a placement at TU Dortmund where I worked with PhD students at the IceCube experiment on improving measurements with ML. IceCube is a neutrino observatory located at the South Pole searching for neutrinos arriving at Earth from high-energy astrophysical events. 

One of the challenges posed by an experimental setup based at the South Pole is the lack of resources available for on-line data analysis. This means that collected data is only fully exploited with several months delay after being shipped to laboratories around the world. Using supervised machine learning techniques, namely Random Forest regression algorithms, I obtained an improvement upon the rudimentary reconstruction of particle energies that could be carried out at the Pole. Such an improvement can allow for the identification of interesting astrophysical events in real-time, and therefore open up the possibility for a host of follow-up studies by other observatories and telescopes. 

The figure shows the reconstructed energy after application of the Random Forest, against the predicted energy from simulation, showing high correlation.

![Muon_energy](/assets/images/muon_energy.png)

## TORCH Project
TORCH is a novel detector technology due to be installed in a future upgrade of the LHCb Experiment. The detector will allow improved identification of charged particles with cutting-edge timing and precision. I have worked on test-beam campaigns where a prototype is deployed in a beam from the LHC complex, and on the calibration of front-end electronics. 

The electronics used in TORCH have a characteristic response to the amount of charge injected in them, ie. the signals received from particles in the detector. The amount of charge is translated into the width of the electronic signal, and this needs to be calibrated for every chip used in the detector. I set up a calibration system which uses a microprocessor to control individual channels in the chip, automated by a LabView programme, and measure this characteristic charge-to-width relation. The figure below shows this relation for a particular board, where a simple model is used to fit the data through Maximum Likelihood Estimation.  

![TORCH_calib](/assets/images/torch_calib.png)
