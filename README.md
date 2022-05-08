[![DOI](https://zenodo.org/badge/152933799.svg)](https://zenodo.org/badge/latestdoi/152933799)

# [Hidden Fluid Mechanics]

We present [hidden fluid mechanics] (HFM), a physics informed deep learning framework capable of encoding an important class of physical laws governing fluid motions, namely the Navier-Stokes equations. In particular, we seek to leverage the underlying conservation laws (i.e., for mass, momentum, and energy) to infer hidden quantities of interest such as velocity and pressure fields merely from spatio-temporal visualizations of a passive scaler (e.g., dye or smoke), transported in arbitrarily complex domains (e.g., in human arteries or brain aneurysms). Our approach towards solving the aforementioned data assimilation problem is unique as we design an algorithm that is agnostic to the geometry or the initial and boundary conditions. This makes HFM highly flexible in choosing the spatio-temporal domain of interest for data acquisition as well as subsequent training and predictions. Consequently, the predictions made by HFM are among those cases where a pure machine learning strategy or a mere scientific computing approach simply cannot reproduce. The proposed algorithm achieves accurate predictions of the pressure and velocity fields in both two and three dimensional flows for several benchmark problems motivated by real-world applications. Our results demonstrate that this relatively simple methodology can be used in physical and biomedical problems to extract valuable quantitative information (e.g., lift and drag forces or wall shear stresses in arteries) for which direct measurements may not be possible.



The required data (to be copied in the Data directory) and some Matlab scripts (to be copied in the Figures directory) for plotting purposes are provided in the following link:

   - [Data and Figures](https://bit.ly/2NRB65U)

In addition to the Data and Figures directories, the Results folder is currently empty and will be automatically populated after running the corresponding examples provided in the Source and Scripts directories.

