# McGill_Radio_Journal_Club

# Radio Journal Club Documentation
A compilation of the readings and resources from the McGill Cosmology Lab radio journal club.

1. "Calibration of Quasi Redundant Interferometers"
		This paper discusses the CorrCal technique for calibrating radio interferometers. The paper can be found at https://arxiv.org/abs/1701.01860
    
2. "An Overview of CHIME, the Canadian Hydrogen Intensity Mapping Experiment"
		This paper discusses the instrument design for CHIME, a radio interferometer designed for 21cm cosmology and Transient detection. The paper can be found at https://arxiv.org/pdf/2201.07869
    
3. "PROBING DARK ENERGY WITH BARYONIC ACOUSTIC OSCILLATIONS FROM FUTURE LARGE GALAXY REDSHIFT SURVEYS"
	This paper discusses the science and measurements behind the Baryon Acoustic Oscillations. The paper can be found at https://arxiv.org/pdf/astro-ph/0307460
  
4. "Detection of Cosmological 21 cm Emission with the Canadian Hydrogen Intensity Mapping Experiment"
		This paper covers the CHIME stacked emission detection of cosmological 21cm emission. The paper can be found at https://arxiv.org/abs/2202.01242
    
5. "Optical intensity interferometry with the Cherenkov Telescope Array"
	This paper discussed optical intensity interferometry techniques. The paper can be found at https://www.sciencedirect.com/science/article/pii/S0927650512001314?via%3Dihub

6. This journal club attempted to use methods from two papers to build a model of image reconstruction from intensity interferometry. Intensity interferometry only provides the Fourier magnitudes, not the phases, so algorithms are needed to recover images. The papers used for the methods were "Two-dimensional image recovery in intensity interferometry using the Cauchy-Riemann relations" found at https://www.researchgate.net/publication/253762857_Two-dimensional_image_recovery_in_intensity_interferometry_using_the_Cauchy-Riemann_relations and "Investigation of the Cauchy–Riemann equations for one-dimensional image recovery in intensity interferometry" found at https://opg.optica.org/josaa/abstract.cfm?uri=josaa-21-5-697 . Nicholas Huang implemented a toy model of the phase reconstruction that can be found here https://github.com/ndhuang/phase_reconstruction/blob/main/phase_reconstruction.py .

7. "The Payload for Ultrahigh Energy Observations (PUEO):A White Paper" discussed an balloon instrument for neutrino observations. The focus was on the similar instrumentation between the payload and our radio observatories, and what techniques we might share. The paper can be found at https://arxiv.org/pdf/2010.02892 .
    
8. A double feature on "A Digital Calibration Source for 21 cm Cosmology Telescopes" found at https://www.worldscientific.com/doi/epdf/10.1142/S2251171722500167 and "Bistatic noise radar: Demonstration of correlation noise suppression" https://ietresearch.onlinelibrary.wiley.com/doi/epdf/10.1049/rsn2.12345 . These are similar techniques for using Psuedo random noise sources for calibration in two different fields.

9. A double feature on "REAL TIME DETECTOR FOR CYCLOSTATIONARY RFI IN RADIO ASTRONOMY" found at https://www.eurasip.org/Proceedings/Eusipco/Eusipco1998/sessions/Th%20A/ThA%20P-6b/1865/ARTICLE7.PDF and "Cyclostationary approaches for spatial RFI mitigation in radio astronomy" found at https://www.sciencedirect.com/science/article/pii/S1631070511002118 . These papers discuss a technique that looks at repeating features in RFI to single out man-made sources of interference.

10. A double feature on sea-cliff interferometry and GNSS Reflectometry. Papers are found at https://www.publish.csiro.au/ph/pdf/PH530420 and https://wires.onlinelibrary.wiley.com/doi/epdf/10.1002/wat2.1167 .

11. A double feature on using radio sources, like the sun, for monitoring of glaciers- "Glaciological Monitoring Using the Sun as a Radio Source for Echo Detection" and "In Situ Demonstration of a Passive Radio Sounding Approach Using the Sun for Echo Detection" Papers can be found at https://doi.org/10.1029/2021GL092450 and https://sci-hub.se/https://ieeexplore.ieee.org/document/8418789 . 

12. "Auxiliary antenna-assisted interference mitigation for radio astronomy arrays" focused on using a secondary tracking antenna to monitor and remove RFI sources from radio interferometers. Paper can be found at https://ieeexplore.ieee.org/document/1381737 .

13. "Altitude Estimation of Radio Frequency Interference Sources via Interferometric Near Field Corrections" discussed a method for focusing RFI sources, like airplanes, that are in the near field of the instrument. This is a preliminary step towards being able to subtract them out. The paper can be found at https://arxiv.org/abs/2502.08867 . 

14. "A Clock Stabilization System for CHIME/FRB Outriggers" described the techniques used for clock synchronization in the CHIME outriggers. This was of particular interest due to the difficulty in synchronizing clocks for VLBI, where interferometric stations are not closely located. The paper can be found at https://iopscience.iop.org/article/10.3847/1538-3881/ac397a .

15. "Inverse Synthetic Aperture Radar Imaging of Space Targets Using Wideband Pseudo-Noise Signals with Low Peak-to-Average Power Ratio" presented a technique for generating an optimized signal for SAR imaging. The paper mostly focused on the radar signal characteristics. The paper can be found at https://elib.dlr.de/204355/1/remotesensing-16-01809.pdf . Joshua found a helpful tutorial on SAR that can be found at https://elib.dlr.de/82313/1/SAR-Tutorial-March-2013.pdf . Matt shared an AI generated audio summary of the paper, which can be found at https://notebooklm.google.com/notebook/e2e1f81a-98b7-4a14-a2d3-7cfd8029c0ee?artifactId=881a4bc3-f78c-4cd0-a5d4-4907fdd489a7 .

16. "Arecibo Radar Observations of Near-Earth Asteroid (3200) Phaethon During the 2017 Apparition" discussed more radar techniques. The paper can be found at https://arxiv.org/pdf/1902.00969 . Ketan made a notebook to demonstrate some of these techniques.
