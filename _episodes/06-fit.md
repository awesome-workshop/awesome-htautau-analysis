---
title: "Step 4: Make a measurement"
teaching: 5
exercises: 10
questions:
- "How can we make a measurement?"
objectives:
- "Perform a fit representing a measurement"
keypoints:
- "The measurement fits for the signal strength (multiplier of the Standard Model expectation) of the Z to two tau lepton process."
---

This step performs a fit on the histograms of the visible mass plot to perform a measurement.

![](../fig/m_vis.png)

Because the contribution of the Higgs signal is too tiny with the inclusive selection, we fit fors the "signal" strength of the Z→ττ process. You can find the fitting implementation in the Python script `fit.py`. Use the following command to run the fit.

```bash
mkdir -p $HOME/awesome-workshop/fit
bash fit.sh $HOME/awesome-workshop/histograms/histograms.root $HOME/awesome-workshop/fit
```

The resulting plot (see below) shows the scan of the profile likelihood from which we can extract the best fit value of the signal strength modifier for the Z→ττ process and the uncertainty associated with this parameter.

![](../fig/fit.png)

{% include links.md %}
