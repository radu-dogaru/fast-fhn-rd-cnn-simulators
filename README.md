# fast-fhn-rd-cnn-simulators
Four simulators for reaction-diffusion cellular nonlinear networks running on Google COLAB 

Four different implementations of Fitz-Hugh Nagumo Reaction Diffusion CNN. PYCUDA implementation runs faster but other implements are considered as well (having simpler, fully Pythonic, descriptions):

NUMBA (a bit slower but fully described in Python)
NUMPY (quite fast using CPU only, useful for comparisons)
CUPY (supports GPU with a code almost identical with the one in NUMPY, relatively slow for GPU support)
Relevant papers (drafts attached): Please cite them if you find the code useful for your research

[1] https://www.worldscientific.com/doi/abs/10.1142/S0218127498000152

[2] R. Dogaru, "Applications of Emergent Computation in Reaction-Diffusion CNNs for Image Processing," 2013 19th International Conference on Control Systems and Computer Science, Bucharest, 2013, pp. 370-377, doi: 10.1109/CSCS.2013.39. Four different implementations of Fitz-Hugh Nagumo Reaction Diffusion CNN. PYCUDA implementation runs faster but other implements are considered as well (having simpler, fully Pythonic, descriptions):

NUMBA (a bit slower but fully described in Python)
NUMPY (quite fast using CPU only, useful for comparisons)
CUPY (supports GPU with a code almost identical with the one in NUMPY, relatively slow for GPU support)
Relevant papers (drafts attached): Please cite them if you find the code useful for your research

[1] https://www.worldscientific.com/doi/abs/10.1142/S0218127498000152

[2] R. Dogaru, "Applications of Emergent Computation in Reaction-Diffusion CNNs for Image Processing," 2013 19th International Conference on Control Systems and Computer Science, Bucharest, 2013, pp. 370-377, doi: 10.1109/CSCS.2013.39. (attached here as draft IAFA_2013_draft.pdf )

In that paper some examples for various dynamical regimes are given.

[3] Radu Dogaru, Ioana Dogaru, "High Productivity Cellular Neural Network Implementation on GPUs using Python",
published in Proceedings of the Workshop in Information Technology and Bionics (Symposium in Memory of Tamás Roska), Budapest, 23–24 June 2015, ISBN 978-963-89880-3-4, pp. 23-27

(attached here as draft CNN_simulator_2015_draft.pdf)

Copyright Radu and Ioana Dogaru; Last update 10 January 2021


