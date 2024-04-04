---
permalink: /
title: "Welcome to my Webpage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
permalink: /
---

I am a Ph.D. student in particle physics at the University of Milan and a member of the [NNPDF](https://nnpdf.mi.infn.it){: .btn--research}  collaboration
in which I work as a code developer.
Check the NNPDF
[Github page <i class="fab fa-fw fa-github" width="40" height="40"></i>](https://github.com/NNPDF "Github page"){: .btn--icon} if you want to learn about the various tools used in our analyses.

With a background in theoretical physics in the field of particle physics, my research focuses on the high precision study of the internal
structure of the proton using machine learning tool, like neural networks, analyzing experimental data collected at particle accelerators
like [LHC](https://home.cern/science/accelerators/large-hadron-collider){: .btn--research}  at [CERN](https://home.cern){: .btn--research} .
This results in the extraction of the so-called parton disrtibution functions (PDFs), i.e. functions that describe the proton in terms of
the distribution of its constituents (quarks and gluons).
This is fundamental for the physics program of all the particle accelerators in high energy physics, like the LHC at CERN, since the PDFs
enter in the computation of all theory predictions in the hadron collisions.

The two follwing pictures show (on the left) the neural network used in the analysis and (on the right) the set of datapoints used.
The data comes from a variety of independent experiments like [ATLAS](https://atlas.cern){: .btn--research} , [CMS](https://home.cern/science/experiments/cms){: .btn--research} ,
 [LHCb](https://home.cern/science/experiments/lhcb){: .btn--research} , [HERA](https://en.wikipedia.org/wiki/HERA_(particle_accelerator)){: .btn--research} ,
 [SLAC](https://en.wikipedia.org/wiki/SLAC_National_Accelerator_Laboratory){: .btn--research}  and others.
Both pictures are taken from the [NNPDF4.0QED paper <i class="ai ai-inspire" width="40" height="40"></i>](https://inspirehep.net/literature/1918284 "Inspire page"){: .btn--paper}.

<div style="text-align:center">
  <img src="images/neuralnetwork.png" alt="Neural network used in the analysis" width="350">
  <img src="images/datapoints.png" alt="Dataset" width="350">
</div>
<br>

The following picture shows the results of the analysis, i.e. the PDFs

<div style="text-align:center">
  <img src="images/PDFs.png" alt="PDFs." width="400">
</div>




I am also a computer science enthusiast: during my research career I worked with a variety of programming languages, but in particular
with C++ and Python.
I have hands-on experience with various machine learning tools, like Keras and Tensorflow.

Check my [Github page <i class="fab fa-fw fa-github" width="40" height="40"></i>](https://github.com/niclaurenti "Github page"){: .btn--icon} for more informations on my (public) projects.

<!-- Check also my [LinkedIn page](https://www.linkedin.com/in/niccolò-laurenti/){: .btn--paper} -->


My Research Projects
--------------------

The main research projects that I worked on during my research career are the following:

### Including Electrodynamics effects in PDFs determination

The main project of my Ph.D. was the inclusion of Electrodynamics effects in PDFs determination.

Usually, the PDFs are determined considering only the effects coming from the strong interaction, i.e. the so-called
Quantum Chromodynamics (QCD), since it is the dominant effect.

However, if one wants to achieve a precision of the order of percent in the theory predictions, then the effects coming
from the electromagnetic interaction, i.e. Quantum Electrodynamics (QED), cannot be neglected.
It follows that the proton's components aquire a new member: the photon!
The photon PDF is somehow special: while the other PDFs cannot be computed but must be extracted from data, the photon can be
computed with an approch called LuxQED method, see [arXiv:1607.04266 <i class="ai ai-inspire" width="40" height="40"></i>](https://inspirehep.net/literature/1475703 "Inspire page"){: .btn--paper} and [arXiv:1708.01256 <i class="ai ai-inspire" width="40" height="40"></i>](https://inspirehep.net/literature/1614486 "Inspire page"){: .btn--paper}, with an equation that links it to the electron-proton scattering predictions.

The following picture, taken from the [NNPDF4.0QED paper <i class="ai ai-inspire" width="40" height="40"></i>](https://inspirehep.net/literature/2747770 "Inspire page"){: .btn--paper}, shows the comparison of the photon PDFs from the most recent analysis

<div style="text-align:center">
  <img src="images/ratio_plot_pdfs_gamma.png" alt="phPDFs." width="400">
</div>


### Developing an approximation for electron-proton scattering at third order in the strong coupling

The project I worked on during my Master Thesis was the construction
of an approximation for the electron-proton scattering, the so-called deep inelastic scattering (DIS),
at the third order in the expansion in the strong coupling $$\alpha_s$$ (the so-called next-to-next-to-next-to leading order 
or in brief N$$^3$$LO) with the heavy quark mass dependence, that is not known yet.

Indeed all the quantities in particle physics are computed as a power expansion in $$\alpha_s$$.
So the theoretical predictions for DIS are computed as
<div style="text-align:center">
$$
C = C^{(0)} + \alpha_s C^{(1)} + \alpha_s^2 C^{(2)} + \alpha_s^3 C^{(3)} + \mathcal{O}(\alpha_s^4)
$$
</div>
This terms are fully known up to $$C^{(2)}$$, but the very last one, i.e. $$C^{(3)}$$, is not.
My work was to combine various limits to construct an approximation for this unknown term.

In order to do it, I wrote the `C++` code [Adani <i class="fab fa-fw fa-github" width="40" height="40"></i>](https://github.com/niclaurenti/Adani "Github page"){: .btn--icon}, now public.
The main methodology and the results are shown in my [Master Thesis <i class="ai ai-inspire" width="40" height="40"></i>](https://inspirehep.net/literature/2750247 "Inspire page"){: .btn--paper}. 

These results have also been used in the [N$$^3$$LO PDFs determination <i class="ai ai-inspire" width="40" height="40"></i>](https://inspirehep.net/literature/2762925 "Inspire page"){: .btn--paper} by NNPDF.

Other Interests
---------------

Other than physics and coding I have other interests:
- I started playing basketball at a very young age (6 years old) with [Minibasket Roma Team-up](http://www.minibasketromateamup.it){: .btn--research} ,
and then I continued with Sam Basket Roma (that unfortunately no longer exists) where I played in all the youth categories and in
the italian C Silver series.
In March 2020 with the start of the COVID-19 pandemic I ended my basketball career. Such a huge loss for the whole italian 
basketball community. Check [this page](/basketballcareer/){: .btn--pagebtn} for more details.
- Since spring 2023 I am an amateur runner. My aim is to run at least an half-marathon, but there is still a long way to go.
- I am an amateur cook: my best disher are all the ones coming from the Roman cousine like spaghetti alla carbonara, cacio e pepe, 
coda alla vaccinara, but also desserts like tiramisù, panna cotta and a lot more.



Contacts
------
Contact me at one of these e-mails:
- [niclaurenti@gmail.com](mailto:niclaurenti@gmail.com){: .btn--research} 
- [niccolo.laurenti@unimi.it](mailto:niccolo.laurenti@unimi.it){: .btn--research} 
- [niccolo.laurenti@mi.infn.it](mailto:niccolo.laurenti@mi.infn.it){: .btn--research} 
