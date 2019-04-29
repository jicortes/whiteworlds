This repository contains the simulation results used for https://arxiv.org/abs/1810.00776

The results have been stored as Python dictionaries in JSON format. The dictionaries contain a white dwarf's identification number (from CatSim) as keys. Each key possesses the following values:

            - 'umag': white dwarf magnitude in u-filter
            - 'gmag': white dwarf magnitude in g-fitler
            - 'rmag': white dwarf magnitude in r-filter
            - 'imag': white dwarf magnitude in i-filter
            - 'zmag': white dwarf magnitude in z-filter
            - 'ymag': white dwarf magnitude in y-filter
            - 'M_Ms': white dwarf mass in solar masses
            - 'R_Rs': white dwarf radius in solar radii
            - 'rho': white dwarf density
            - 'Teff': white dwarf effective temperature in Kelvin
            - 'wd': white dwarf spectral type (either DA or DB)
            - 'per': orbital period of the injected planet
            - 'rp': planet radius in stellar radii
            - 'b': impact parameter
            - 'phi': inferior conjunction in radians 
            - 'ar': semi-major axis in stellar radii
            - 'snr': signal-to-noise ratio, as defined in 1810.00776
            - 'detect': '0' for non-detection, '1' for detection
            - 'cf': the geometric probability for a detection occurring 
