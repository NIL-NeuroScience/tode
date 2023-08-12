# Tissue Oxygen Depth Explorer (TODE): An Interactive Database for Microscopic Oxygen Imaging Data
Tissue Oxygen Depth Explorer (TODE) v1.0 is a MATLAB-based database with graphical user interface (GUI) to simplify access and visualization.The datasets included with TODE v1.0 were generated as part of our recent 2P-PLM-based study on oxygen metabolism across cortical layers in awake mice under ‘resting-state’ conditions [1]. Individual datasets are defined in a MATLAB file (“database.mat”) stored in the main data folder. This definition file contains a structural array containing metadata and dataset-specific settings for the GUI display. Individual datasets contain raw and processed phosphorescence decay data from Oxyphor 2P phosphorescence lifetime measurements at eleven penetrating arterioles in depths between 0 and 500 μm below the cortical surface. These datasets were generated from primary data stored by the imaging system using custom-written MATLAB scripts as described above and in [1]. The database also contains image stacks of every penetrating arteriole visualized with intravascular FITC- or Alexa 680-Dextran as well as low-magnification overviews of the surface vasculature. Low-magnification overviews show maximum intensity projections of image stacks acquired at 4× or 5× magnification.  An export option allows storing the data for each acquired cortical depth of each penetrating arteriole as MATLAB data file for further use. 

# MATLAB App

# sourceCode

# standalone App

# References
[1] Mächler, P., N. Fomin-Thunemann, M. Thunemann, M. J. Saetra, M. Desjardins, K. Kilic, L. N. Amra, E. A. Martin, I. A. Chen, I. Sencan-Egilmez, B. Li, P. Saisan, J. X. Jiang, Q. Cheng, K. L. Weldy, D. A. Boas, R. B. Buxton, G. T. Einevoll, A. M. Dale, S. Sakadzic and A. Devor (2022). "Baseline oxygen consumption decreases with cortical depth." PLoS Biol 20(10): e3001440.
