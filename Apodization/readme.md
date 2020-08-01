* *pipeline_mock.py* includes the python functions to generate theoretical spectra.

* *mask_k.fits* is a healpix map file describing the mask for 2018 CMB lensing convergence map

* *mask_q.fits* is a healpix map file depicting the mask for our selected BOSS quasar sample. 
  Multiple cuts are applied: 2.2 <=z<=3.4; NGC only; FIRST sample rejected; 5<g<22; -28.74<=MI(z=2)<=-23.78

* *sphtfunc.py* is a modified version, in which I add a *seed* parameter in *synalm* and *synfast*. Then I just replace the original one and then I can use the *seed* parameter when using *hp.synalm* and *hp.synfast*.

* *example.ipynb* shows how I construct theoretical spectra and generate correlated CMB and quasar maps.

* *kernel_size.py* is what I used to generate 200 mocks.

- Folder *result* shows the result for this test , *result.ipynb*  show the final result.



