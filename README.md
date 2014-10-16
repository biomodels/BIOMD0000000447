# BIOMD0000000447: MODEL1303130000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000447.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000447.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000447 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Venkatraman2012 - Interplay between PLS and TSP1 in TGF-β1 activation

The interplay between PLS (Plasmin) and TSP1 (Thrombospondin-1) in TGF-β1
(Transforming growth factor-β1)is shown using mathematical modelling and _in
vitro_ experimentents.

This model is described in the article:

[Plasmin triggers a switch-like decrease in thrombospondin-dependent
activation of TGF-β1.](http://identifiers.org/pubmed/23009856)

Venkatraman L, Chia SM, Narmada BC, White JK, Bhowmick SS, Forbes Dewey C Jr,
So PT, Tucker-Kellogg L, Yu H.

Biophys J. 2012 Sep 5;103(5):1060-8.

Abstract:

Transforming growth factor-β1 (TGF-β1) is a potent regulator of extracellular
matrix production, wound healing, differentiation, and immune response, and is
implicated in the progression of fibrotic diseases and cancer. Extracellular
activation of TGF-β1 from its latent form provides spatiotemporal control over
TGF-β1 signaling, but the current understanding of TGF-β1 activation does not
emphasize cross talk between activators. Plasmin (PLS) and thrombospondin-1
(TSP1) have been studied individually as activators of TGF-β1, and in this
work we used a systems-level approach with mathematical modeling and in vitro
experiments to study the interplay between PLS and TSP1 in TGF-β1 activation.
Simulations and steady-state analysis predicted a switch-like bistable
transition between two levels of active TGF-β1, with an inverse correlation
between PLS and TSP1. In particular, the model predicted that increasing PLS
breaks a TSP1-TGF-β1 positive feedback loop and causes an unexpected net
decrease in TGF-β1 activation. To test these predictions in vitro, we treated
rat hepatocytes and hepatic stellate cells with PLS, which caused proteolytic
cleavage of TSP1 and decreased activation of TGF-β1. The TGF-β1 activation
levels showed a cooperative dose response, and a test of hysteresis in the
cocultured cells validated that TGF-β1 activation is bistable. We conclude
that switch-like behavior arises from natural competition between two distinct
modes of TGF-β1 activation: a TSP1-mediated mode of high activation and a PLS-
mediated mode of low activation. This switch suggests an explanation for the
unexpected effects of the plasminogen activation system on TGF-β1 in fibrotic
diseases in vivo, as well as novel prognostic and therapeutic approaches for
diseases with TGF-β dysregulation.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL1303130000](http://identifiers.org/biomodels.db/MODEL1303130000) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


