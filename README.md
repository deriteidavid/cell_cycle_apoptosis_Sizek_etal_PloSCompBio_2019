# Supporting Information - Jupyter Notebook

## Boolean model of growth signaling, cell cycle and apoptosis predicts the molecular mechanism of aberrant cell cycle progression driven by hyperactive PI3K
Herbert Sizek<sup>1,#a</sup>, Andrew Hamel<sup>1,#b</sup>, Dávid Deritei<sup>2,3</sup>, Sarah Campbell<sup>1</sup>, Erzsébet Ravasz Regan<sup>1,*<sup>

<sup>1</sup> - Biochemistry and Molecular Biology, The College of Wooster, Wooster, OH, United States of America <br>
<sup>#a</sup> - Current Address: Epic Systems Corporation, Verona, Wisconsin, United States of America <br>
<sup>#b</sup> - Current Address: Department of Ophthalmology and Ocular Genomics Institute, Massachusetts Eye and Ear, Harvard Medical School, Boston, MA, United States of America<br>
<sup>2</sup> - Department of Physics, Pennsylvania State University, State College, PA, United States of America<br>
<sup>3</sup> - Department of Network and Data Science, Central European University, Budapest, Hungary<br>
<sup>*</sup> - Corresponding author<br>
<br>

### Abstract

The PI3K/AKT signaling pathway plays a role in most cellular functions linked to cancer progression, including cell growth, proliferation, cell survival, tissue invasion and angiogenesis. It is generally recognized that hyperactive PI3K/AKT are oncogenic due to their boost to cell survival, cell cycle entry and growth-promoting metabolism. That said, the dynamics of PI3K and AKT1 during cell cycle progression are highly nonlinear. In addition to negative feedback that curtails PI3K activity, protein expression of its subunits has been shown to oscillate in dividing cells. The low-PI3K/low-AKT1 phase of these oscillations is required for cytokinesis, indicating that oncogenic PI3K may directly contribute to genome duplication. To explore this, we construct a Boolean model of growth factor signaling that can reproduce PI3K oscillations and link them to cell cycle progression and apoptosis. The resulting modular model reproduces hyperactive PI3K-driven cytokinesis failure and genome duplication and predicts the molecular drivers responsible for these failures by linking hyperactive PI3K to mis-regulation of Polo-like kinase 1 (Plk1) expression in late G2. To do this, our model captures the role of Plk1 in cell cycle progression and accurately reproduces multiple effects of its loss: G2 arrest, mitotic catastrophe, chromosome mis-segregation and aneuploidy due to premature anaphase, and cytokinesis failure leading to genome duplication, depending on the timing of Plk1 inhibition along the cell cycle. Finally, we offer testable predictions on the molecular drivers of PI3K oscillations, the timing of these oscillations with respect to division, and the role of altered Plk1 and FoxO activity in genome-level defects caused by hyperactive PI3K. Our model is an important starting point for the predictive modeling of cell fate decisions that include AKT1-driven senescence, as well as the non-intuitive effects of drugs that can alter the progression of mitosis.

### The notebook

The **SI_notebook.ipynb** Jupyter Notebook contains the steps and procedures to reproduce the key findings of our paper (in press).
The notebook doesn't reproduce *all* the results published in the paper, however it provides almost all tools for anyone interested in doing similar studies, mostly in form of functions.
We will keep updating it with new implementations as soon as we have them.

The Boolean models and supporting files are included in the repository. 

The necessary python packages to run the notebook:<br>
numpy, matplotlib, seaborn (optional)<br>

BooleanNet - https://github.com/ialbert/booleannet <br>
NetworkX - https://networkx.github.io/

Every other function used in the notebook is defined "in house". <br>

Comments and suggestions are welcome!
