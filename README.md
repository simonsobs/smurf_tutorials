# SMuRF Tutorials
This repository contains guides for setting up and operating the SMuRF System.


## Notebooks
### Primary notebooks
These tutorials should be completed in the following order and cover:
1. **Sodetlib_Tutorial**
 - Reviews how to create a `DetConfig` object and how to use it to obtain a `SmurfControl` object. 
 - Reviews different config objects contained in `DetConfig` object
 - Describes how to run sodetlib functions from the jupyter or ipython interface.
2. **Tuning**
 - Setting amplifier biases
 - Finding resonance frequencies
 - Setting on tones
 - Setting up flux ramp and frequency tracking
 - Streaming data
3. **Data**
 - Instantiating `pysmurf` in offline mode
 - Reading and ploting tune data
 - Reading and plotting streamed data
3.5. **G3 Data**
 - Taking and loading data in the G3 format.
4. **TES Biasing**

### Additional Notebook References
These additional notebooks can be used as additional references to the setup references listed below and the primary notebooks listed above but are not maintained like the primary notebooks.
1. Setup
 - For setting up the SMuRF hardware.
2. EPICS, Rogue, and Pysmurf

## Setup References
The following links should be used for SMuRF hardware and software setup before following the tutorials in these notebooks.
- [Hardware setup guide](http://simonsobservatory.wikidot.com/smurfsetup)
- [Software setup guide](http://simonsobservatory.wikidot.com/smurf-software-setup)

## Documentation
- [Pysmurf docs](https://pysmurf.readthedocs.io/en/main/?badge=main)
- [SODETLIB docs](https://simons1.princeton.edu/~jlashner/sodetlib/)