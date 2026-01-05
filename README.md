# Felix's Works and Collaborations
**UC Berkeley** (**Coming Soon**)

**NSF's NOIRLab**  
[F. Pat et al., “Reconstructing and Classifying SDSS DR16 Galaxy Spectra with Machine-Learning and Dimensionality Reduction Algorithms,” ASP Conference Series Vol. 525 (2022).](https://www.aspbooks.org/publications/525/067.pdf)
![umap](https://github.com/felixpat10/Felix-Pat/blob/f521f868d6cdb0be5912f9fbb7c42d79a2a06870/media/umap.gif)  
Optical spectra of galaxies and quasars from large cosmological surveys are used to measure redshifts and infer distances. They are also rich with information on the intrinsic properties of these astronomical objects. However, their physical interpretation can be challenging due to the substantial number of degrees of freedom, various sources of noise, and degeneracies between physical parameters that cause similar spectral characteristics. To gain deeper insights into these degeneracies, we apply two unsupervised machine learning frameworks to a sample from the Sloan Digital Sky Survey data release 16 (SDSS DR16). The first framework is a Probabilistic AutoEncoder (PAE), a two-stage deep learning framework consisting of a data compression stage from 1000 elements to 10 parameters and a density estimation stage. The second framework is a Uniform Manifold Approximation and Projection (UMAP), which we apply to both the uncompressed and compressed data. Exploring across regions on the compressed data UMAP, we construct sequences of stacked spectra which show a gradual transition from star-forming galaxies with narrow emission lines and blue spectra to passive galaxies with absorption lines and red spectra. Focusing on galaxies with broad emission lines produced by quasars, we find a sequence with varying levels of obscuration caused by cosmic dust. The experiments we present here inform future applications of neural networks and dimensionality reduction algorithms for large astronomical spectroscopic surveys.  

Tutorials for galaxy spectra analysis  
[Intro to Spectroscopy from the GOGREEN DR2 Dataset](https://github.com/astro-datalab/notebooks-latest/blob/master/03_ScienceExamples/GOGREEN_GalaxiesInRichEnvironments/4_GOGREENDr2Spec1DRedshift.ipynb)  
![spectra](https://github.com/felixpat10/Felix-Pat/blob/f521f868d6cdb0be5912f9fbb7c42d79a2a06870/media/spectra.png)  
This notebook aims to illustrate 1D and 2D spectrum emission line features and how to derive the redshift and equivalent width of the [O II]3727 doublet from a Gaussian fit. Additionally, it shows how to display a galaxy image, plot its 1D and 2D spectrum, and fit the emission line to calculate the redshift and equivalent width to compare to the GOGREEN database values.

**CERN, ATLAS Collaboration**  
[Performance of Boosted Z Boson Tagger Using Unsupervised Learning in ATLAS](https://repository.arizona.edu/handle/10150/668692)
![mass](https://github.com/felixpat10/Felix-Pat/blob/f521f868d6cdb0be5912f9fbb7c42d79a2a06870/media/mass.png)  
To detect and explore possible candidates for dark matter and physics beyond the Standard Model (BSM),
we use ATLAS’s recently developed Unified Flow Objects (UFOs) large-radius jets for tagging boosted
hadronic decays of the 𝑍0 boson (𝑍′)1. For the 𝑍′ tagger, we introduce the Clustering Autoencoder (CAE)
which integrates two unsupervised learning frameworks for the classification and mass decorrelation of
UFO jets. The first framework is a fully-connected autoencoder (AE) that reduces the number of input jet
substructure variables into a latent space of three dimensions, and the second framework is a Uniform
Manifold Approximation and Projection (UMAP) algorithm which reduces the AE latent space further
to two dimensions. Afterwards, a neural network score is constructed by transforming the UMAP latent
space to a histogram as a function of each event’s representative Euclidean space. We compare the CAE
tagger performance to previous cut-based tagger and deep neural network (DNN) tagger performances
through signal efficiency and background rejection rates. Though the 𝑍′ tagger underperforms tenfold
compared to previously tested taggers, the CAE presents a realistic approach of training without the UFO
jets’ weights and labels. Most importantly, the tagger we present here shows an important step towards
scaling into high dimension analysis for physics BSM.
