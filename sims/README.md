Simulation log
==============


** dAu 200 GeV **

- set 0: 200 GeV, b<2 fm, sig_parton=0.75 mb, FVTX pT filter, 5k events/job, 10k jobs (50M total)
- set 1: 200 GeV, b<2 fm, sig_parton=0.75 mb, FVTX 1<|eta|<3 only, 5k events/job, 10k jobs (50M total)
- set 2: 200 GeV, b<2 fm, sig_parton=1.50 mb, FVTX 1<|eta|<3 only, 5k events/job, 10k jobs (50M total)
- set 3: 200 GeV, b<2 fm, sig_parton=1.50 mb, FVTX pT filter, 5k events/job, 10k jobs (50M total)
- set 4: 200 GeV, b<20 fm, sig_parton=1.50 mb, FVTX pT filter, 5k events/job, 10k jobs (50M total)
- set 5: 200 GeV, b<20 fm, sig_parton=1.50 mb, FVTX pT filter, 5k events/job, 10k jobs (50M total)
    + Changed binning on N_charge (500, -0.5, 499.5)
    + Add 2D for <<4>>
    + Add parton_pplane.C
- set 6: 200 GeV, b<2 fm, sig_parton=1.50 mb, FVTX pT filter, 5k events/job, 1k jobs (5M total)
    + Modified parton_pplane.C to use particles in FVTX range for Nch dependence
- set 7: 200 GeV, b<2 fm, sig_parton=1.50 mb, FVTX pT filter, 5k events/job, 1k jobs (5M total)
    + Fixed parton_pplane.C to normalize FVTX pT dep efficiency
- set 8: 200 GeV, b<2 fm, sig_parton=1.50 mb, FVTX pT filter, 5k events/job, 10k jobs (50M total)

- set 10: 200 GeV, b<20 fm, sig_parton=0.75 mb, FVTX pT filter, 5k events/job, 10k jobs (50M total), 2 May 2017
    + After modifying cumulants.C, parton_pplane.C, event_plane.C


** pAu 200 GeV **

- set 0: 200 GeV, b<2 fm, sig_parton=1.50 mb, FVTX pT filter, 5k events/job, 10k jobs (50M total)


** AuAu 200 GeV **

- set 0: 200 GeV, b<20 fm, sig_parton=1.50 mb, FVTX pT filter, 1k events/job, 1k jobs (1M total)
- set 1: 200 GeV, b<20 fm, sig_parton=1.50 mb, FVTX pT filter, 500 events/job, 2k jobs (1M total)
    + After fixing parton_pplane.C

** pPb 5.02 TeV **

- set 0: 5020 GeV, b<2 fm, sig_parton=1.50 mb, FVTX pT filter, 1k events/job, 1k jobs (1M total)
- set 0: 5020 GeV, b<2 fm, sig_parton=1.50 mb, FVTX pT filter, 5k events/job, 2k jobs (10M total)

** PbPb 5.02 TeV **

- set 0: 5020 GeV, b<20 fm, sig_parton=1.50 mb, FVTX pT filter, 500 events/job, 2k jobs (1M total)





** dAu 200 GeV **
- set 10: 200 GeV, b<20 fm, sig_parton=0.75 mb, FVTX pT filter, 5k events/job, 10k jobs (50M total), 2 May 2017
    + After modifying cumulants.C, parton_pplane.C, event_plane.C
- set 11: 200 GeV, b<20 fm, sig_parton=0.75 mb, FVTX pT filter, 5k events/job, 10k jobs (50M total), 3 May 2017
    + After modifying fvtx efficiencies
    
** dAu 62.4 GeV **
- set 10: 62.4 GeV, b<20 fm, sig_parton=0.75 mb, FVTX pT filter, 5k events/job, 10k jobs (50M total)
    + After modifying cumulants.C, parton_pplane.C, event_plane.C
- set 11: 62.4 GeV, b<20 fm, sig_parton=0.75 mb, FVTX pT filter, 5k events/job, 10k jobs (50M total), 3 May 2017
    + After modifying fvtx efficiencies

** dAu 39 GeV **
- set 10: 39 GeV, b<20 fm, sig_parton=0.75 mb, FVTX pT filter, 5k events/job, 10k jobs (50M total), 4 May 2017
    + After modifying fvtx efficiencies

** dAu 19.6 GeV **
- set 10: 19.6 GeV, b<20 fm, sig_parton=0.75 mb, FVTX pT filter, 5k events/job, 10k jobs (50M total), 4 May 2017
    + After modifying fvtx efficiencies


** dAu BES (200, 62.4, 39, 19.6) **
- set 19: 11 May 2017 - b<20 fm, sig_parton=0.75 mb, FVTX pT eta filter, 1k events/job, 1k jobs (1M total)
    + Test run after modifying centrality bin limits
- set 20: 11 May 2017, b<20 fm, sig_parton=0.75 mb, FVTX pT eta filter, 5k events/job, 10k jobs (50M total)

