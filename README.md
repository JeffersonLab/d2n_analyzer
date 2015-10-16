Tue Mar 23 21:21:23 EDT 2010  [ Brad Sawatzky -- brads@jlab.org ]
- resynced to CVS version
- modified src/THaDecData.C:
  - commented out the VdcEff() call on line 680 -- I don't think we care about
    those histos for offline analysis
- applied Diana's patch to src/THaNormAna.C (THaNormAna-23Mar2010.diff) that
  adds the updated bcm calibration constants.
- analogous patch applied to  BBNormAna/BBNormAna.cxx (BBNormAna/BBNormAna-23Mar2010.diff)
