Note: In order to open the links in a separate window, hold ctrl on Windows or Command on mac while clicking (GitHub doesn't support presetting this) :(

<a href = "http://nbviewer.jupyter.org/github/aboomer07/ESV_Proof/blob/master/ESV_Proof.ipynb?flush_cache=True" target="blank">Link to Notebook Viewer</a>

# Sensitivity Analysis

## Explanation of Notebook

This notebook started out addressing a dataset related to my internship with Earth Economics. I was asked to read through a research paper (PDF shown below), and use the sensitivity analysis method shown on the data provided to me related to the organizations project. I am not able to show the data from Earth Economics, but I can show the process applied to the data in the research paper shown below. 

After replicating the sensitivity analysis method in the paper on the data specific to the Earth Economics project, I realized the results were off. I set up a proof to simplify the equations in the orginal paper, and was able to show a few critiques of the method when applied to the Ecosystem Service Valuation (ESV) function. The coefficient of sensitivity (CS) is independent of adjustments to the inputs, all CS values are less than 1, and all the CS values summed across the land types add to 1.

This is important because the CS values are supposed to be a measure of elasticity, where values above 1 imply less robust estimates, and values under 1 imply robust estimates. The proof, which was just an algebraic simplification (laid out below in LaTex code) of the formulas, shows that the CS just calculates the percentage of the ESV a specific land type makes up out of the total.

I have displayed the PDF of the research paper in the notebook below, but the link to access it on the Professor's website is: <a href = "https://agrilife.org/kreuter/files/2013/01/Change-in-ecosystem-service-values-in-SanAntonio-areaTexas_6.pdf" target = "_blank">Link to Original Paper</a>

Additionally, while all of the work I show below is original, after sharing this notebook with my supervisor, we found that there was a critique paper already written whose process I had unknowlingly replicated (more or less). The link to the abstract for that paper is: <a href = "https://www.sciencedirect.com/science/article/pii/S2212041616301668" target = "_blank">Link to Critique</a>

**Note: CS and ESV formulas are defined below in the notebook**
