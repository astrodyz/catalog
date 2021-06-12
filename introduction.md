### Introduction of the catalog-planet_high_V&planet_medium_V&planet_low_V

#### author astrodyz

columns

KIC: the identification of planet host star in the Kepler Input Catalog
gmag: gmag
gmag_err: the error of gmag
kmag: kmag
kmag_err: the error of kmag
parallax: parallax (corrected by Berger2020)
parallax: the error of parallax

...

You can find more details of the definition of the columns in the catalog provided by Berger2020 (from column RUWE to TAMS)

DAI_cdpp3: Robust RMS CDPP for a searched transit duration of 3 hours. The robust root-mean-square (RMS) combined differential photometric precision (CDPP) is an empirical estimate of the noise in the relative flux time series observations. TPS computes a non-stationary time series of CDPP, which sets the significance level of detected transit signals.
DAI_cdpp6: Robust RMS CDPP for a searched transit duration of 6 hours.
DAI_cdpp12: Robust RMS CDPP for a searched transit duration of 12 hours.

neglect columns "DAI_std_vra" to "DAI_pmdec_eror"

dutycycle: The fraction of data cadences within the span of observations that contain valid data and contribute toward detection of transit signals. The values for Duty Cycle ranges from 0.0 and 1.0.
dutycycle_post: The duty cycle calculated after the transit search is complete and all transit signals have been removed from the light curve. This metric is useful in identifying targets where large amounts of data were removed as a result of multiple planet search iterations.
dataspan: The time elapsed in days between the first and last cadences containing valid data.
dataspan_post: The data span calculated after the transit search is complete and all transit signals have been removed from the light curve. This metric is useful in identifying targets where large amounts of data were removed as a result of multiple planet search iterations.

You can find more details of the definition of the columns named from "B2018_teff" to "B2018_binaryflag" (Berger2018)
B2018_evState: 0 main-sequence, 1 or 2 not main-sequence? (you should check the meaning in the catalog offered in Berger2018)
B2018_binaryflag: 0 single; 1 binary? (you should check the meaning in the catalog offered in Berger2018)

You can find more detail of the definition of the columns named from "koi_disposition" to "koi_model_snr" in the KOI DR25 or search the following web: https://exoplanetarchive.ipac.caltech.edu/docs/program_interfaces.html#defcols

iso_koi_prad: the planet radius in the unit of Earth radii utlizing the stellar parameters offered by Berger2020
iso_semi_major_axis: the semi_major_axis in the unit of au utlizing the stellar parameters offered by Berger2020
iso_koi_teq: the effective temperature in the unit of K utlizing the stellar parameters offered by Berger2020

q: see definition in my paper Dai2021
vec2D: see definition in my paper Dai2021