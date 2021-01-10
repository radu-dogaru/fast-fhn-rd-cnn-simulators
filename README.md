# fast-fhn-rd-cnn-simulators
Four simulators for reaction-diffusion cellular nonlinear networks running on Google COLAB 

Four different implementations of Fitz-Hugh Nagumo Reaction Diffusion CNN. 
PYCUDA implementation runs faster but other implements are considered as well (having simpler, fully Pythonic, descriptions):

NUMBA (a bit slower but fully described in Python)
NUMPY (quite fast using CPU only, useful for reference and comparisons)
CUPY (supports GPU with a code almost identical with the one in NUMPY, relatively slow for GPU support)
Relevant papers (drafts attached): Please cite them if you find the code useful for your research

[1] R. Dogaru and L. O. Chua, "Edge of Chaos and Local Activity Domain of FitzHugh-Nagumo Equation", in International Journal of
Bifurcation and Chaos (IJBC), Volume: 8, Issue: 2(1998) pp. 211-257. https://www.worldscientific.com/doi/abs/10.1142/S0218127498000152

This paper gives a detalied methodology to identify useful regions in the parameter space of a FitzHugh Nagumo cellular nonlinear network model as well as several examples of emergent phenomena. They can be tested using these simulators. 

[2] R. Dogaru, "Applications of Emergent Computation in Reaction-Diffusion CNNs for Image Processing," 2013 19th International Conference on Control Systems and Computer Science, Bucharest, 2013, pp. 370-377, doi: 10.1109/CSCS.2013.39. (attached here as draft IAFA_2013_draft.pdf )

In this paper some examples for various dynamical regimes are given with an emphasis on image processing applications.

[3] Radu Dogaru, Ioana Dogaru, "High Productivity Cellular Neural Network Implementation on GPUs using Python",
published in Proceedings of the Workshop in Information Technology and Bionics (Symposium in Memory of Tamás Roska), Budapest, 23–24 June 2015, ISBN 978-963-89880-3-4, pp. 23-27 (attached here as draft CNN_simulator_2015_draft.pdf)

In this paper extension of the NUMBA model to the Cellular Neural Network model is explained. 

Copyright Radu and Ioana Dogaru; Last update 10 January 2021


<a href="https://colab.research.google.com/github/radu-dogaru/fast-fhn-rd-cnn-simulators/blob/fhn_rd_cnn__fast_simulator.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
