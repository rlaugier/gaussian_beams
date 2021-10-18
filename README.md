# Spectrograph radiometry study

This work was carried out as part of the SCIFY project for the design of Hi-5.

## Purpose

These notebooks are meant to provide design guidelines for the implementation re-imaging and spectroscopy at the outputs of single mode fiber waveguides (photonics).

## Gaussian spectrograph psf

`gaussian_spectrograph_psf.ipynb` uses centrosymmetric Gaussian beams. It serves 2 main objectives:

- Determine the size of the circular pupil allowing a given throughput from the Gaussian beam.
- Determine the PSF obtained from such a Gaussian beam truncated by the pupil.
	- In particular, determine by how much the pupil must be oversized to obtain the same resolution (here, FWHM) compared to a uniform illumination.
	- Draw the regions in the image plane (in detector pixels) where the contrast is greater than a certain value
	- Draw the regions in the object plane (in µm) where where the contrast is greater than a certain value (i.e. to determine the minimum spacing of outputs)


## Acknowledgement

This project was funded by an ERC Consolidator grant from the European Research Council (grant agreement No.\ 866070)

